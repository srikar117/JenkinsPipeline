// auto trigger demo
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the code using Maven to compile and package the application.'
            }
        }
        stage('Unit and Integration Tests') {
            steps {
                echo 'Running unit tests with JUnit and integration tests with Selenium.'
            }
        }
        stage('Code Analysis') {
            steps {
                echo 'Analysing code quality and standards using SonarQube.'
            }
        }
        stage('Security Scan') {
            steps {
                echo 'Scanning for vulnerabilities using OWASP Dependency-Check.'
            }
        }
        stage('Deploy to Staging') {
            steps {
                echo 'Deploying the application to a staging server on AWS EC2.'
            }
        }
        stage('Integration Tests on Staging') {
            steps {
                echo 'Running integration tests on the staging environment using Postman.'
            }
        }
        stage('Deploy to Production') {
            steps {
                echo 'Deploying the application to a production server on AWS EC2.'
            }
        }
    }
}