pipeline {
    environment {
        registry = "cybernonk404/devops_node_test"
        registryCredential = 'MyDocker'
        dockerImage = ''
    }
    
    agent any

    stages {
        stage('Preparation') {
            steps {
                echo 'Clone Git Repo'
                git 'https://github.com/Cybernonk404/devops_nodejs'
            }
        }
        
        stage('Test') {
            steps {
                echo 'Node JS Test'
            }
        }
    }
}