/* Jenkinsfile (Declarative Pipeline) */
/* Requires the Docker Pipeline plugin */
/* pipeline {*/
/*    agent { docker { image 'php:8.3.0-alpine3.19' } }*/
/*    stages {*/
/*        stage('build') {*/
/*            steps {*/
/*                sh 'php --version'*/
/*            }*/
/*        }*/
/*    }*/
/*}*/

Jenkinsfile (Declarative Pipeline)
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}