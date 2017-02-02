#!groovy

pipeline {
    agent any
    stages {
       stage ('Dockerfile') {
          steps {
            sh 'which docker'
            sh 'make BIND_DIR=.'
          }
        }
        // stage ('Build') {
        //     agent {
        //         dockerfile {
        //             reuseNode true
        //         }
        //     }
        //     steps {
        //         //sh 'make build'
        //         sh 'make binary'
        //     }
        // }
    }
}
