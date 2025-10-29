pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'hello from jenkins'
            }
        }
        stage('Deploy') {
            steps {
                sh '''
                sudo cp index.html /var/www/html/
                echo "Deployment done!"
                '''
            }
        }
    }
}

