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
                dir('cluster-backup') {
                    // Run script located inside the repository
                    sh 'chmod +x your_script.sh' // Make the script executable if necessary
                    sh './your_script.sh' // Execute the script
                }
            }
        }
    }
}
