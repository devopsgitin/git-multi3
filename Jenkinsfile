pipeline {
    agent any
    stages {
        stage ("MAIN BRANCH") {
            when {
                branch 'main'
            }
            steps {
                sh 'cat "main.txt"'
            }
        }
        stage ("FEATURE1 BRANCH") {
            when {
                branch 'feature1'
            }
            steps {
                sh 'cat "feature1.txt"'
            }
        }
    }
}
