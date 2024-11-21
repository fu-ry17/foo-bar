@Library('jenkins-shared-library') _

pipeline {
    agent any
    
    options {
        disableConcurrentBuilds()
    }
    
    stages {
        stage('Generate Pipelines') {
            steps {
                script {
                    monorepo()
                }
            }
        }
    }
} 