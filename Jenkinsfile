pipeline {
    agent any
    
    stages {
        stage('Clone') {
            steps {
                // Sử dụng lệnh git để clone repository
                git branch: 'main', url: 'https://github.com/buituansonHE172207/jenkin_github.git'
            }
        }
    }
}
