pipeline {
    agent {
        node {
            label 'maven'
        }
    }

    stages {
        stage('Clone-code') {
            steps {
                script {
                    git branch: 'main', url: 'https://github.com/shubhamsavan/tweet-trend-new.git'
                }
            }
        }
    }
}
