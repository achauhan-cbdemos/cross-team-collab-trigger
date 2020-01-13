pipeline {
    agent any

    triggers {
        eventTrigger simpleMatch('cloudbees-js@1.0.0')
    }

    stages {
        stage('Npm Example') {
            steps {
                echo 'a new npm package triggered this Pipeline'
            }
        }
    }
}
