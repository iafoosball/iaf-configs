pipeline {

    agent any
    environment {
        COMPOSE_PROJECT_NAME = "${env.JOB_NAME}-${env.BUILD_ID}"
    }
    stages {
        stage ("Build") {
            steps {
                sh "ls -al"
            }
        }
}
}
