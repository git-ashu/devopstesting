pipeline {
    agent { label 'maven-node' }

    stages {
        stage('Clone') {
            steps {
                git branch: 'main', url: 'https://github.com/git-ashu/devopstesting.git'
            }
        }
    }
}
