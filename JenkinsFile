pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                git 'https://github.com/simon-ouyang-rb/java-rest-api-calculator.git'
                sh './mvnw clean compile'
            }
        }
    }
}
