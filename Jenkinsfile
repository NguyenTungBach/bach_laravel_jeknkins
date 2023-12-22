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
        stage('Run Artisan Command config clear') {
            steps {
                script {
                    bat 'composer update && php artisan config:clear'
                }
            }
        }

    }
}
