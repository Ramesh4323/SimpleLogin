pipeline {
    agent any

    stages {
        stage('Deploy') {
            steps {
                bat '''
                if not exist C:\\xampp\\htdocs\\loginapp mkdir C:\\xampp\\htdocs\\loginapp
                xcopy /E /Y * C:\\xampp\\htdocs\\loginapp\\
                '''
            }
        }
    }
}