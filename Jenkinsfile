pipeline {
    agent any  
    stages {
        stage('clone repo') {
            steps {
                git url : 'https://github.com/rakesh15565/raki.git' , branch : 'main'
            }
        }
        stage ('compile java'){
            steps{
                bat 'java hello.java'
            }
        }
        stage ('run java'){
            steps{
                bat 'java hello.java'
            }
        }
    }
}