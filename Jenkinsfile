pipeline {
    agent any

    triggers {
        eventTrigger jmespathQuery("eventName=='helloWorld'")
    }

    stages {
        stage('Example') {
            steps {
                echo 'received helloWorld'
            }
        }
    }
}
