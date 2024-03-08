pipeline {
    agent any
    
    stages {
       
        stage('Run Script') {
            steps {
                // Change directory to the cloned repository

                    sh 'chmod +x your_script.sh' // Make the script executable if necessary
                    sh './your_script.sh' // Execute the script
                

            }
        }
    }
}
