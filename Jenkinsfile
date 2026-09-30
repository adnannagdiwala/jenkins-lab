pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }

        stage('Run') {
            steps {
                sh 'java -cp target/jenkins-lab-1.0.jar HelloWorld'
            }
        }
    }
}
