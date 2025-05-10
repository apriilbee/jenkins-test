pipeline {
    agent any

    stages {
        stage('GitHub Trigger Test') {
            steps {
                echo "✅ Jenkins pipeline was successfully triggered by a GitHub commit."
                echo "Timestamp: ${new Date()}"
                echo "Build URL: ${env.BUILD_URL}"
            }
        }
    }
}
