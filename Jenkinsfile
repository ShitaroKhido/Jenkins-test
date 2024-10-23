pipeline {
    agent any

    triggers {
        pollSCM('* * * * *') // Polls the SCM every minute for changes
    }

    stages {
        stage('Hello') {
            steps {
                echo 'Hello, World!'
            }
        }
    }
}