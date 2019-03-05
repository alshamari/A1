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

        sh "python -u api.py"   
        }
    }
    
}
}

