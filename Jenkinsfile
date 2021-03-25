pipeline {
    agent { docker { image 'node:14-alpine' } }
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello, world!"'
                sh '''
                  echo "Multiline!!!"
                  ls -lah
                '''
            }
        }
    }
}
