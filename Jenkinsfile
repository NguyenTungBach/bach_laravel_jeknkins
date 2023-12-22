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
                    bat 'cd /d E:\\HocWeb\\PHP\\"Bài Tập PHP"\\DemoLaravelJenkins && php artisan config:clear'
                }
            }
        }

    }
}
