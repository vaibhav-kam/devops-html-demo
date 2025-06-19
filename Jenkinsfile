pipeline { 
    agent any

    stages {
        stage('Clone Repo') {
            steps {
                git branch: 'main, url:' 'https://github.com/vaibhav-kam/devops-html-demo.git'
            }
        }
        stage('Show HTML File') {
            steps {
                echo "Printing contents of index.html"
                sh 'cat index.html'
            }
        }
    }
}
