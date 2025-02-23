#!groovy


pipeline {
    agent {
        label 'master'
        }
    options {
        timestamps ()
        }
    stages {
        stage("first_step") {
            steps {
                sh 'echo "hello_world"'
                }
        }
    }
}
