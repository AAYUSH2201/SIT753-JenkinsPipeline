pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building application using Maven'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Running tests using JUnit and Selenium'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Analysing code using SonarQube'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Running security scan using OWASP Dependency Check'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Deploying application to AWS EC2 staging server'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Running staging integration tests using Selenium'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Deploying application to production AWS EC2'
            }
        }
    }
}
