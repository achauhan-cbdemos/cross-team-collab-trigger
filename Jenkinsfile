pipeline {
    agent any

    triggers {
        eventTrigger simpleMatch('cloudbees/java-build-tools:LATEST')
    }

    stages {
        stage('Docker Example') {
            steps {
                echo 'a new docker image triggered this Pipeline'
            }
        }
    }
}
