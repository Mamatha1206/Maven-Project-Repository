// maven-project/Jenkinsfile
@Library('my-shared-library') _  // Import the shared library

pipeline {
    agent any  // Use any available agent

    stages {
        stage('Build') {
            steps {
                script {
                    mavenBuild()  // Call the shared library function to perform the Maven build
                }
            }
        }
    }
}
