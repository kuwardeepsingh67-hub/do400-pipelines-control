pipeline {

    agent any

    stages {
        stage('Backend Tests') {
            steps {
                sh 'oc apply -f deployment.yaml'
            }
        }

    }
}
