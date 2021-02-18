pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                echo 'Hello world!' 
                sleep time: 1000, unit: 'MILLISECONDS'
                input 'Do you want to run main.js?'
                sh 'node main.js'
                echo 'Test webhook 4';
            }
        }
    }
}
// pipeline {
//     agent { docker { image 'node:14-alpine' } }
//     stages {
//         stage('build') {
//             steps {
//                 sh 'npm --version'
//             }
//         }
//     }
// }