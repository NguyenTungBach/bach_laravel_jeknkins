pipeline {
    agent any

    stages {
        stage('Run Clone Test') {
            steps {
                script {
                    git 'https://github.com/NguyenTungBach/bach_laravel_jeknkins.git'
                }
            }
        }
        stage('Setting the variables values hello world') {
            steps {
                 sh '''#!/bin/bash
                         echo "hello world"
                 '''
            }
        }
    }
}
