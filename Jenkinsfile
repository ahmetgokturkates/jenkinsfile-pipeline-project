pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "Gokturk's python job"
                sh "python --version"
                sh "python pipeline.py"
            }
        }
    }
}