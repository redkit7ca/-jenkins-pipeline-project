pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Compiling the java source code'
                sh 'javac Hello.java'
            }
        }
        stage('run') {
            steps {
                echo 'Running the compiled java code.'
                sh 'java Hello'
            }
        }
    }
}
// pipeline {
//     agent any
//     stages {
//         stage('run') {
//             steps {
//                 echo 'Clarusway_Way to Reinvent Yourself'
//                 sh 'python --version'
//                 sh 'python pipeline.py'
//             }
//         }
//     }
// }

// pipeline {
//     agent any

//     stages {
//         stage ('Compile Stage') {

//             steps {
//                 withMaven(maven : 'maven_3_5_0') {
//                     sh 'mvn clean compile'
//                 }
//             }
//         }

//         stage ('Testing Stage') {

//             steps {
//                 withMaven(maven : 'maven_3_5_0') {
//                     sh 'mvn test'
//                 }
//             }
//         }


//         stage ('Deployment Stage') {
//             steps {
//                 withMaven(maven : 'maven_3_5_0') {
//                     sh 'mvn deploy'
//                 }
//             }
//         }
//     }
// }
