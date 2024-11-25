pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'hello again'
                pwd
                make hello
            }
        }
        stage('world') {
            steps {
                echo "world world"
            }
        }
    }
}
