pipeline { 
    agent any

    stages {
        stage('Clone Repo') {
            steps {
                git branch: 'main', url: 'https://github.com/vaibhav-kam/devops-html-demo.git'
            }
        }
        stage('Show HTML File') {
            steps {
                sh 'cat index.html'
            }
        }
    }
}
