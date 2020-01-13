pipeline {
    agent any

    stages {
        stage('Docker Example') {
            steps {
                echo 'new docker image got published'
                publishEvent simpleEvent('cloudbees/java-build-tools:LATEST')
            }
        }
    }
}
