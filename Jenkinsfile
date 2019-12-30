//comment
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                //git poll: true, url: 'https://github.com/AbrahamMG11/test-jenkins.git'
                git 'https://github.com/cloudogu/jenkinsfiles'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                //sh 'make check'
                //junit 'reports/**/*.xml' 
                echo 'Deploying....'
            }
        }
    }
}
