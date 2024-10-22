// Uses Declarative syntax to run commands inside a container.
pipeline {
    agent {
        kubernetes {
            yamlFile 'myAgent.yaml'
        }
    }
    stages {
        stage('Main') {
            steps {
                sh 'hostname'
                echo 'Hello, world!'
            }
        }
    }
}
