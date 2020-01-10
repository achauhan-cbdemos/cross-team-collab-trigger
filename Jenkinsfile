pipeline {
    agent any

    triggers {
        eventTrigger simpleMatch("helloWorld")
    }
    stages {
        stage('Example') {
            steps {
                echo 'received helloWorld'
            }
        }
    }
}
