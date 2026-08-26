pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Install Pytest') {
            steps {
                bat '"C:\\Users\\Abhigyan Anand\\AppData\\Local\\Programs\\Python\\Python313\\python.exe" -m pip install pytest'
            }
        }

        stage('Run Tests') {
            steps {
                bat '"C:\\Users\\Abhigyan Anand\\AppData\\Local\\Programs\\Python\\Python313\\python.exe" -m pip install pytest'
            }
        }
    }
}
