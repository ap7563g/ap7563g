pipeline {
    agent any

    stages {
        stage('Building') {
            steps {
                echo 'The Code will be now be build into an artifact'
            }
        }
        stage('Artifact Archiving') {
            steps {
                echo 'The Artifact will be uploaded to an artifact repository'
            }
        }
        stage('Testing') {
            steps {
                echo 'The Artifact will be tested'
            }
        }
        stage('Staging') {
            steps {
                echo 'The Artifact staged onto the staging server'
            }
        }
        stage('Deploy') {
            steps {
                echo 'The Software will now be deployed'
            }
        }

    }
}
