pipeline {
    agent {
        node {
            label 'maven'
        }
    }

    stages {
        stages('Clone-code') {
          steps {
              git branch 'main' , url: 'https://github.com/shubhamsavan/tweettrend-new.git'
            }
        }
    }
}
