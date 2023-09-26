pipeline {
    agent any 

    stages {
        stage('Dependencies') {
            steps {
                echo 'Fetching dependencies...'
		echo 'Dependencies - NIL'
                            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                echo 'Tests - NIL'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the binary...'
                echo 'Build - NIL'
                }
            }
        }

 
         


        stage('Package') {
            steps {
                echo 'Packaging the binary...'
                echo 'Nothing available'
            }
        }

        stage('Cleanup') {
            steps {
                echo 'Cleaning up...'
                sh 'make clean'
            }
        }
    }

    post {
        always {
            echo 'This will always run'
        }
        success {
            echo 'Pipeline completed successfully!'
        }
        failure {
            echo 'Pipeline failed :('
        }
    }
}

