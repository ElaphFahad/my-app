pipeline {
    agent any 
    stages {
        stage('clean and build') { 
            steps {
                // 
              sh "mvn clean"
            }
        }
        stage('Test') { 
            steps {
              sh "mvn test"
                // 
            }
        }
        stage('Deploy') { 
            steps {
              sh"mvn package"
                // 
            }
        }
    }
}
