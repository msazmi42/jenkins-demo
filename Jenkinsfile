pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Code checked out from Git ................brightsunMD'
            }
        }

        stage('Run Demo') {
            steps {
                bat 'run.bat'
            }
        }
    }
}