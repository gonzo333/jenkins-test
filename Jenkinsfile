pipeline {
    agent any
    tools {
        maven "maven-3"
    }
    stages {
        stage('Build') {
            steps {
                cleanWs()
                sh("git config --global user.email \"pawelnowaczek88@gmail.com\"")
                sh("git config --global user.name \"gonzo333\"")
                git 'https://github.com/gonzo333/test.git'
            }
        }
    }
}
