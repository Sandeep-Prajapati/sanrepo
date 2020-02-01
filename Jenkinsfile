pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                sh "date"
                sh "lsb_release -a"
                sh "uname -a"
                echo 'Hello world! ...' 
                sh "pwd"
            }
        }
    }
}