pipeline {
    agent { label 'maven-node' }
    
    tools {
     maven "maven"   
    }

    stages {
        stage('Clone') {
            steps {
                git branch: 'main', url: 'https://github.com/git-ashu/devopstesting.git'
            }
        }
         stage('Build') {
            steps {
                sh 'mvn clean install'
            }
        }
    }
}
