pipeline {
    agent any
    stages{
        stage ('clone'){
        steps{
            checkout scm 
        }
    }
    stage ('bulid'){
        steps{

        sh "python -u /Users/alshamari/A1/application/api.py"   
        }
    }
    
}
}

