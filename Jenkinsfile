pipeline {
    agent any
    stages {
        stage('Example Build') {
            steps {
                echo 'Hello World'
            }
        }
        stage('stage1') {
            when {
                branch 'production'

                }
            }
            steps {
                echo 'Deploying'
            }
        }
        
        stage('stage2') {
            steps {
                echo 'Deploying'
            }
        }
    }
}