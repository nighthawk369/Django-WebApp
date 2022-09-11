pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                echo "hello from builing......."
                sh 'docker build --tag testjen django_web_app/'
            }
        }
        stage('Test') { 
            steps {
                echo "hello from testing......." 
            }
        }
        stage('Deploy') { 
            steps {
                echo "hello from deploying......." 
            }
        }
    }
}
