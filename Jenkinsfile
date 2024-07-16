pipeline{
    agent any
    stages{
        stage('run script'){
            steps{
                sh "chmod +x ./deploy.sh"
                sh "./deploy.sh"
            }
        }
    }
}