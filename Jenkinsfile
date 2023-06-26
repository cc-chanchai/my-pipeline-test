pipeline {
    agent { docker { image 'maven:3.9.0-eclipse-temurin-11' } }
    echo "##############################"
    sh 'docker --version'
    cho "##############################"
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
