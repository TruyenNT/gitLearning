pipeline {
    agent any
        stages {
            stage('Build') {
                steps {
                    /scripts/create_log_build.sh
                }
            }
            stage('Test') {
                steps {
                    /scripts/create_log_test.sh
                }
            }
            stage('Deploy') {
                steps {
                    /scripts/create_log_deploy.sh
                }
            }
        }
}