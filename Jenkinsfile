pipeline {
    agent any

    parameters {
        string(name: 'VERSION', defaultValue: '1.0.0', description: 'Build Version')
    }

    stages {
        stage('Build') {
            steps {
                //echo 'Building version ${parameters.VERSION}'
                echo 'Building Project...'
//                 sh 'cd untitled'
                sh 'chmod +w ./untitled/gradlew'
                sh ' chmod +w ./untitled/gradlew
                ./untitled/gradlew build'
            }
        }
//         stage('Test') {
//             steps {
//                 //echo 'Testing version ${parameters.VERSION}'
//                 echo 'Testing Project...'
//                 sh './gradlew test'
//             }
//             post {
//                 always {
//                     junit "build/reports/tests/**/*.html"
//                 }
//             }
//         }
    }
}