pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                sh "date"
                // emailext body: 'This is test mail. pls ignore.', subject: 'Test Mail', to: 'sandeepprajapati1@gmail.com'
                fileExists '/etc/sample.py' {
                    echo "File path exists"
                } 
                //else {
                //    echo "File path not found."
                //}                   
                sh "echo $HOME , welcome ....."
                sh "echo $USER"
                echo 'Hello world! ...' 
                sh "pwd"
                echo "This is a sample print line."
                echo "$HOME"
                echo "$USER"
                echo "$SHELL"
                sh "pwd"
                sh "ls"
            }
        }
    }
}
