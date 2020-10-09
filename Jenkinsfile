pipeline{
    agent any
    tools{
       maven 'Maven-3.6'
       }
    stages{
        stage('chekcout'){
            steps{
                git 'https://github.com/Dhaamodharan/my-app.git'
                }
              }
        stage('build'){
            steps{
                sh 'mvn clean package'
              }
        }
        stage('deploy'){
            steps{
                echo 'deployment of maven is success'
              }
        }
    }
}
