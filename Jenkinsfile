pipeline {
    agent any

    stages {
        stage('click') {
            steps {
                sh 'python3 click.py'
                sh 'python3 welcome.py'
            }
        }
    }
}
