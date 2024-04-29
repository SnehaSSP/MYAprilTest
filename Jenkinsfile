pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                // Checkout the code from the Git repository
                git branch: 'main', url: 'https://github.com/SnehaSSP/MYAprilTest.git'
            }
        }
        
        stage('Run Python Scripts') {
            steps {
                // Run the first Python script
                sh 'python hello.py'
                
                // Run the second Python script
                sh 'python hello1.py'
            }
        }
    }
}
