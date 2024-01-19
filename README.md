pipeline {
    agent any

    stages {
        stage('Hello World 2') {
            steps {
                echo 'Hello, World!'
            }
        }
    }
}
