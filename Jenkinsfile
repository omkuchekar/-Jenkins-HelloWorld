pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'My build stage'
            }
        }
        stage('Test'){
            steps{
                echo 'My Test stage'
            }
        }
        stage('Deploy'){
            steps{
                echo 'My Deploy stage'
            }
        }
    }
    post{
        always{
            emailext body: 'Test mail from jenkins pipeline', subject: 'Test from Jenkins pipeline status', to: 'omkuchekar@gmail.com'
        }
        
    }
}
