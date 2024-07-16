pipeline{
    agent any
    stages{
        stage('run script'){
            steps{
                sh "sudo chmod +x ./deploy.sh"
                sh "./deploy.sh"
            }
        }
    }
}