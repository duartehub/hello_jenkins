pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh 'make hello'
            }
        }
        stage('world') {
            steps {
                echo "world world"
            }
        }
    }
}
