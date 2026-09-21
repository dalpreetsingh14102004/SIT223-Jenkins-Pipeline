pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Task: Build the code by compiling and packaging the application.'
                echo 'Tool: Maven'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Task: Run unit tests and integration tests to verify the application.'
                echo 'Tool: JUnit'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Task: Analyse the code and check that it meets industry standards.'
                echo 'Tool: SonarQube'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Task: Scan the code to identify security vulnerabilities.'
                echo 'Tool: Snyk'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Task: Deploy the application to a staging server.'
                echo 'Tool: AWS EC2'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Task: Run integration tests in the staging environment.'
                echo 'Tool: Selenium'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Task: Deploy the application to the production server.'
                echo 'Tool: AWS EC2'
            }
        }
    }
}
