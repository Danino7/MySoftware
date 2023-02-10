pipeline {
    agent any

    stages {
        stage('click') {
            steps {
                bat 'dir'
                bat 'click.py'
                bat 'welcome.py'
            }
        }
    }
}
