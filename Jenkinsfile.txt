pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                date
                echo 'Hello world! ...' 
                pwd
            }
        }
    }
}