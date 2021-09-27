pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World This is upendra"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
