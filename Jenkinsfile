pipeline {
    agent any

    stages {
        stage('Clone Code') {
            steps {
                echo "Code pulled from GitHub"
            }
        }

        stage('Deploy using Ansible') {
            steps {
                sh 'ansible-playbook deploy.yml'
            }
        }
    }
}
