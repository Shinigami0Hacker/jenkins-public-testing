pipeline {
  agent any
  
    stages{
      stage('Clone'){
        git branch: 'main', url: 'https://github.com/Shinigami0Hacker/jenkins-public-testing' 
      }
      stage('Say hello'){
        sh 'python3 main.py'
      }
    }
  
}
