pipeline {
    agent any
    tools {
        maven "maven 3.8.8"
    }
    stages {
        stage ('maven') {
            steps {
                echo "hello maven"
                sh "mvn --version"
            }
        }
    }
}
