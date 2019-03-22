/* NOTE: this Pipeline mainly aims at catching mistakes (wrongly formed Dockerfile, etc.)
 * This Pipeline is *not* used for actual image publishing.
 * This is currently handled through Automated Builds using standard Docker Hub feature
*/
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }
}

// vim: ft=groovy
