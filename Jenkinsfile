

pipeline {

  agent any

  triggers {
    githubPush()
  }

  stages {

        // Build stage
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }

        // Test stage
        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }
        
        // Deployment stage
        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
  }

}
