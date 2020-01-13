pipeline {
    agent any

    stages {
        stage('Example') {
            steps {
                echo 'new maven artifact got published'
                publishEvent simpleEvent('com.example:my-jar:0.5-SNAPSHOT:jar')
            }
        }
    }
}
