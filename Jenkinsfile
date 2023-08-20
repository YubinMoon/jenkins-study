pipeline {
    agent { docker "python:3.10" }
    stages {
        stage("run python") {
            steps {
                sh 'python hello.py'
            }
        }
    }
}
