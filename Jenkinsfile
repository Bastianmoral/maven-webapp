pipeline {
    agent any
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                git branch: 'main', credentialsId: '83ab0e95-ed21-4147-922c-76110b4d4eb9', url: 'https://github.com/Bastianmoral/maven-webapp'

            }
        }
    }
}
