stage('Build Image') {
    steps {
        sh 'docker build -t sabarirko/prt-image .'
    }
}

stage('Push Image') {
    steps {
        sh 'docker push sabarirko/prt-image'
    }
}
