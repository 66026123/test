pipeline {
    agent any
    triggers {
        githubPush(secret: 'my-secret-key')  // ตรวจสอบ Secret
    }
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/66026123/test.git'
            }
        }
    }
}

