#!groovy


pipeline {
    agent any
    options {
        timestamps ()
        }
    stages {
        stage("first_step 🚀 ") {
            steps {
                sh 'echo "hello_world"'
            }
        }
        stage("second 🚀 ") {
            steps {
                sh 'echo \'my second file "hello world"\' > /tmp/second.txt'
                sh 'cat /tmp/second.txt'
            }
        }
    }
}
