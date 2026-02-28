//declarative pipeline 
// stages we divide into multiple stage

pipeline {
    agent any
    
    stages {
        stage ('STAGE1') {
            steps {
                echo "This is the stage 1"
                sh 'sleep 5'
            }
        
        }
        stage ('STAGE2') {
            steps {
                sh '''
                   #!/bin/bash
                   pwd
                   ls -lrt
                   sleep 5
                '''
                echo "This is the stage 2"
            }
        }
}
}