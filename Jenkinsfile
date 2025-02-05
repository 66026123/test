pipeline {
    agent any
    triggers {
        githubPush(secret: 'my-secret-key') // ตรวจสอบ Secret
    }
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/66026123/test.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building the project...'
                // เพิ่มคำสั่งสำหรับการ build เช่น การใช้ Docker หรือการคอมไพล์โค้ด
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the project...'
                // เพิ่มคำสั่งสำหรับการ deploy เช่น การใช้ Docker หรือ Ansible
            }
        }
    }
}
