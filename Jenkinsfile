pipeline{
    agent any
    stages{
        stage('Bulid Maven'){
            steps{
                sh 'pwd'
                sh 'mvn clean install package'
            }
        }
        stage('Copy Artifacts'){
            steps{
                sh 'pwd'
                sh 'cp -r target/*.jar docker'
            }
        }
        
    }
}
