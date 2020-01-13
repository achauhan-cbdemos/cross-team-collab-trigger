pipeline {
    agent any

    triggers {
        eventTrigger simpleMatch('com.example:my-jar:0.5-SNAPSHOT:jar')
    }

    stages {
        stage('Maven Example') {
            steps {
                echo 'a new maven artifact triggered this Pipeline'
            }
        }
    }
}
