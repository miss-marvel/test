pipeline {
    agent { label 'master'}
    
    stages {
        stage('git-hub') {
            steps {
                echo "Cloning git project Test"
                // git branch: 'main', url: 'https://github.com/miss-marvel/test.git'
            }
        }
        
        stage('Build') {
            steps {
                echo "Building block"
            }
        }
        
        
    }
}