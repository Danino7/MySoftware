pipeline {
    agent any

    stages {
        stage('click') {
            steps {
                python3 click.py
                python3 welcome.py
            }
        }
    }
}