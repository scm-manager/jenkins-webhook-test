pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('build') {
            steps {
                echo "hello from maven?"
                sh 'mvn --version'
            }
        }
    }
}