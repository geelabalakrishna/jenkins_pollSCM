pipeline {
    agent any
    triggers {
        pollSCM('*/5 * * * *')
    }
    stages {
        stage('Build') {
            steps {
                echo "Building due to SCM changes"
            }
        }
    }
}
