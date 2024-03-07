pipeline {
    agent any
    stages {
        stage('Display Env') {
            steps {
                script {
                    echo "Jenkins URL: ${env.JENKINS_URL}"
                    echo "Build ID: ${env.BUILD_ID}"
                }
            }
        }
    }
}
