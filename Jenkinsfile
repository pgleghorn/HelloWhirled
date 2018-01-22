pipeline {
    agent any 

    stages {
        stage('Build') { 
            steps { 
                sh "mvn clean install"
            }
        }
        stage('Test'){
            steps {
                echo "hello"
            }
        }
        stage('Deploy') {
            steps {
                echo "hello"
            }
        }
    }
}
