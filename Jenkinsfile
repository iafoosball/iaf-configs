pipeline {
    agent any
    environment {
        COMPOSE_PROJECT_NAME = "${env.JOB_NAME}-${env.BUILD_ID}"
    }
    stages {
        stage ("Build") {
            steps {
                sh "docker network create -d bridge kong_iafoosball"
            }
        }
}
}
