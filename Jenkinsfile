pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'echo "Building..."'
                sh 'ls -la'
            }
        }

        stage('Test') {
            steps {
                sh 'echo "Testing..."'
                sh 'pwd'
                // Example of creating and moving a file, simulating test artifacts
                sh 'touch test.txt'
                sh 'mv test.txt test_directory/'
            }
        }

        stage('Deploy') {
            steps {
                sh 'echo "Deploying..."'
                // Assuming docker is installed and configured on Jenkins agent
                // Clone your project repository; in this case, using a generic Git command as a placeholder
                sh 'git clone https://gitlab.com/Reece-Elder/dockerfileexercise.git'
                sh 'cd dockerfileexercise'
                // Build and run your Docker container
                sh 'docker build -t myapp .'
                sh 'docker run -d -p 80:80 myapp'
            }
        }
    }
}
