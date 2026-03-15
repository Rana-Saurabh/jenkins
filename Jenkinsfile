pipeline {
    agent any

    stages {
        stage('Clone Success') {
            steps {
                echo "Repository cloned successfully"
            }
        }

        stage('Run App') {
            steps {
                sh 'python3 app.py'
            }
        }

        stage('Run Tests') {
            steps {
                sh 'bash test.sh'
            }
        }
    }
}

