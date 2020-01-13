pipeline {
    agent any

    triggers {
        eventTrigger jmespathQuery("contains(event, 'com.example:my-jar')")
    }
    stages {
        stage('Maven Example') {
            steps {
                echo 'a new maven artifact triggered this Pipeline'
            }
        }
    }
}
