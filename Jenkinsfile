pipeline {
    agent any //{
    //     // docker {
    //     //     image 'maven:3.9.6-eclipse-temurin-17-alpine'
    //     //     args '-v /root/.m2:/root/.m2'
    //     // }
    //     // label 'lua6hc_agent'
    // }

    stages {
        stage('Build') {
            steps {
                // sh 'mvn -B -DskipTests clean package'
                sh 'docker ps'
            }
        }
    }
}