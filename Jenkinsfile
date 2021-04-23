pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'mvn -version"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
