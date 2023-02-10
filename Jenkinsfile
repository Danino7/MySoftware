pipeline {
    agent any

    stages {
        stage('click') {
            steps {
                sh 'python3 click.py'
                sh 'welcome.py'
            }
        }
    }
}
