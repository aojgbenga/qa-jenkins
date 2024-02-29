pipeline {
    agent any 

    stages {
        stage('Build') {
            steps {
                sh 'echo "Simulating build process..."'
                // 'mvn compile'
            }
        }

        stage('Test') {
            steps {
                sh 'echo "Simulating test process..."'
                //'mvn test'
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
