pipeline {
    agent any
    stages {
        stage("build") {
            steps {
                sh """
                    docker build -t hello_akshay .
                """
            }
        }
        stage("run") {
            steps {
                sh """
                    docker run --rm hello_akshay
                """
            }
        }
    }

}
