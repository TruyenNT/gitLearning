pipeline {
    agent any
        stages {
            stage('Build') {
                steps {
                    sh '/scripts/create_log_build.sh'
                }
            }
            stage('Test') {
                steps {
                    sh '/scripts/create_log_test.sh'
                }
            }
            stage('Deploy') {
                steps {
                    sh '/scripts/create_log_deploy.sh'
                }
            }
        }
}
