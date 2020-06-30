pipeline{
    agent any
    tools{
       maven 'Maven-3.6.3'
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
    }
}
