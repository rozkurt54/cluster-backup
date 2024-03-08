pipeline {
    agent any
    
    stages {
        stage('Clone Repository') {
            steps {
                // Checkout code from GitHub repository
                git branch: 'master', url: 'https://github.com/rozkurt54/cluster-backup.git'
            }
        }
        
        stage('Run Script') {
            steps {
                // Change directory to the cloned repository

                    sh 'chmod +x your_script.sh' // Make the script executable if necessary
                    sh './your_script.sh' // Execute the script

            }
        }
    }
}
