pipeline {
    agent any
    stages {
        stage("build") {  
            steps {
                echo "Build has started..."
            }
        }
        stage("test") {
            steps {
                echo "Testing started..."
                sh "sleep 2m 30s"
                echo "finished testing"
            }
        }
    }
}