pipeline {
    agent any  // This tells Jenkins to run the pipeline on any available agent

    stages {
        stage('Checkout') {
            steps {
                // Checkout the code from GitHub
                git 'https://github.com/SuprajaSandhya/devops.git'
            }
        }

        stage('Run Python Script') {
            steps {
                // Run the Python script
                sh 'python first.py'
            }
        }
    }
}
