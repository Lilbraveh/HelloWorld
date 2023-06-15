pipeline {
    agent any 

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh 'npm install' // Here, we assume that Node.js and npm are available on the Jenkins agent.
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                // Here, you should define the command to run your tests. For example:
                // sh 'npm test'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
                // Here, you should define the command to deploy your application. This will vary depending on your deployment process.
                // For instance, if you're deploying to a Docker container, you might build your Docker image and push it to a Docker registry here.
            }
        }
    }
}
