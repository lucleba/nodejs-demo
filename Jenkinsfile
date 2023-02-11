pipeline {
    agent any 
    stages {
        stage('Clone') { 
            // Truy cập vào project -> chọn Pipeline Syntax
            // Trong "Sample Step" chọn công việc mình muốn làm -> Generate Pipeline Script
            steps {
                git 'https://github.com/lucleba/nodejs-demo.git' 
            }
        }
        // stage('Build') { 
        //     steps {
        //         // 
        //     }
        // }
        // stage('Test') { 
        //     steps {
        //         // 
        //     }
        // }
        // stage('Deploy') { 
        //     steps {
        //         // 
        //     }
        // }
    }
}