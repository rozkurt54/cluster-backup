pipeline {
    agent any
    
    stages {
       
        stage('Run Script') {
            steps {
                // Change directory to the cloned repository

                    sh 'chmod +x script.sh' // Make the script executable if necessary
                    sh './script.sh' // Execute the script
                

            }
        }
    }
}
