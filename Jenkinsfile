pipeline {
    agent any 

    stages (
        stage('docker-build-test-base') {
            steps {
                echo 'Bulding base image for api tests..'
                //sh "docker build -t equbovi4/api-tests-base . -f Dockerfile.base"
            }   
        }

        stage('docker-build-test-runner') {
            steps {
                echo 'Build runner image for api tests..'
                //sh "docker build -t equbovi4/api-tests-runner . -f Dockerfile.runner"
            }
        }
    )
}