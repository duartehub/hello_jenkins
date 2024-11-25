pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                make hello
                echo 'hello again'
            }
        }
        stage('world') {
            steps {
                echo "world world"
            }
        }
    }
}
