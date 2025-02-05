pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/66026123/test.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building the project...'
                // ใส่คำสั่ง build ที่ต้องการ
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the project...'
                // ใส่คำสั่ง deploy ที่ต้องการ
            }
        }
    }
}
