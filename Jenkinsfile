pipeline {
    agent any 

    stages {
        stage('Build') {
            steps {
                sh 'echo "Simulating build process..."'
                // If you have actual build commands, add them here (e.g., 'mvn compile')
            }
        }

        stage('Test') {
            steps {
                sh 'echo "Simulating test process..."'
                // If you have actual test commands, add them here (e.g., 'mvn test')
            }
        }

        stage('Deploy') {
            steps {
                sh 'echo "Simulating deployment process..."'
                sh 'mkdir deploy-output'  // Create a sample output directory
                sh 'touch deploy-output/deployment-artifact.txt' // Create a sample artifact
            }
        }
    }
}
