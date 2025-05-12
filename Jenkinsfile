pipeline {
    agent {
        node {
            label 'maven'
        }
    }

    stages {
        stage('Clone-code') {
            steps {
                git 'https://github.com/Salas2014/hello-world.git'
            }
        }
    }
}

