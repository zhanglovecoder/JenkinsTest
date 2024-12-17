pipeline {
    agent any
    environment {
        PYTHON_HOME='/usr/bin/python3'
    }
    stages {
        stage('Build') {
            steps {
                sh "${env.PYTHON_HOME}'python Myjenkinstest/test.py'" 
            }
        }
    }
}

