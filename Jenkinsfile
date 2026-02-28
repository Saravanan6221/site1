pipeline {
    agent any

    stages {
        stage('Deploy Site1') {
            steps {
                sh '''
                sudo rm -rf /var/www/site1/*
                sudo cp -r site1/* /var/www/site1/
                '''
            }
        }
    }
}
