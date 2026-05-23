pipeline {
    agent any 

    stages {
        stage("Clone"){
            steps {
                echo 'Code already cloned by SCM'
            }
        }
        stage("Compile"){
            steps{
                bat "javac HellWorld.java"
            }
        }
         stage("Run"){
            steps{
                bat "java HellWorld"
            }
        }
    }
}