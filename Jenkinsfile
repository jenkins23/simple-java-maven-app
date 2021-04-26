pipeline {
    agent {
        docker {
            image 'maven:latest'
        }
    }

    stages {

        stage('Maven test') {
            steps {
                    sh "mvn -version"
                }
            }
        }
}
