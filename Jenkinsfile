pipeline {
    agent any 

    stages {
        stage('Build') { 
            steps { 
                sh -c "mvn clean install"
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
