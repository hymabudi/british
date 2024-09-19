pipeline {
    agent any

    stages {
        stage('source') {
            steps {
                git branch: 'main', url: 'https://github.com/hymabudi/british.git'
            }
        }
        stage('list') {   // This stage should be within the same 'stages' block
            steps {
                sh 'ls -l'
            }
        }
    }
}
