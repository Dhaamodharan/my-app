pipeline{
    agent any
    
    stages{
        stage('chekcout'){
            steps{
                git 'https://github.com/Dhaamodharan/my-app.git'
                }
              }
        stage('build'){
            tools{
                maven 'Maven-3.8.1'
                   }
            steps{
                sh 'mvn clean package'
              }
        }
        stage('deploy'){
            steps{
                echo 'deployment of maven is success-through webhook'
              }
        }
    }
}
