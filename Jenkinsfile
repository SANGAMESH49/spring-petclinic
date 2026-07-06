pipeline {
    agent any

    stages {
        stage('git clone') {
            steps {
                git branch: 'main', url: 'https://github.com/Sumukha47/spring-petclinic.git'
            }
        }
        stage('generate a build') {
            steps {
                sh 'mvn package'
            }
        }
    }
}
