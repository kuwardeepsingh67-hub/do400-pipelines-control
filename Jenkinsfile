node('nodejs') {

    stage('Checkout') {

        git branch: 'main',

            url: 'https://github.com/kuwardeepsingh67-hub/do400-pipelines-control'

    }

    stage('Backend Tests') {

        sh 'node ./backend/test.js'

    }

    stage('Frontend Testssss') {

        sh 'node ./frontend/test.js'

    }

}
