pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                script {
                    git 'https://github.com/phuongnd8888/Demo-CICD.git'
                }
                 
            }
        }

        // stage('Build and Package') {
        //     steps {
        //         script {
        //             echo 'Building and packaging the application...'
        //             sh 'docker build -t node-docker-demo .'
        //         }
        //     }
        // }

        // stage('Deploy') {
        //     steps {
        //         script {
        //             echo 'Deploying the application...'
        //             sh 'docker run -p 3000:3000 -d --name my-app node-docker-demo'
        //         }
        //     }
        // }
    }
}
