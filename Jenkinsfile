pipeline {
    agent { label maven-node }

    stages {
        stage('Clone') {
            steps {
                git branch: 'main', credentialsId: '2ee1f368-6c89-4579-81b1-ba3aad3b6100', url: 'https://github.com/git-ashu/devopstesting.git'
            }
        }
    }
}
