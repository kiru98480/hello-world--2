pipeline{
    agent any
    tools {
         maven 'maven'
         jdk 'java'
    }   
    stages{
//         stage('checkout'){
//             steps{
// #                checkout([$class: 'GitSCM', branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[credentialsId: 'github access', url: 'https://github.com/sreenivas449/java-hello-world-with-maven.git']]])
//                 git checkout scm
//             }
//         }
        stage('build'){
            steps{
               sh "echo hello"
            }
        }
//         stage('code analysis'){
//             steps{
//                  sonar-scanner
//             }
//         }
//         stage('artifact'){
//             steps{
//                  sh "export date=`date`"
//                  sh "aws s3 cp target/*.jar s3://bucket/$date"
//             }
//         }
//         stage('deploy'){
//             steps{
//                  andible-playbook ${param.environement}.yml
//            }
//         }
//         stage('verification'){
//             steps{
//                  andible-playbook ${param.environement}-validation.yml  >> output.txt
//            }
//        }
//        stage('post deployment message'){
//             steps{
//                  sh "echo deployment is success and please find the validation"
//                  sh "cat output.txt"
//            }
       }
}
