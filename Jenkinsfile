// pipeline {
//     agent { docker 'python:3.5.1' }
//     stages {
//         stage('build') {
//             steps {
//                 sh 'python --version'
//             }
//         }
//     }
// }

pipeline {
    agent { docker 'frolvlad/alpine-gcc' }
    stages {
        stage('build') {
            steps {
                sh 'gcc main.cpp'
            }
        }
    }
}