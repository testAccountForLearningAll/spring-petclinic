pipeline {
    agent any
    stages {
        stage('git clonning') {
            steps {
                git url:'https://github.com/testAccountForLearningAll/spring-petclinic.git', branch:'main'
            }
        }
        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}
