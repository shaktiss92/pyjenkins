pipeline {
    agent {
        label '!windows'
    }
    stages {
        stage('Build') {
            steps {
                echo "Database engine is "
                echo "DISABLE_AUTH is "
                sh 'printenv'
            }
        }
    }
}
