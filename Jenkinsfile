node {
    stage('build') {
    git 'https://github.com/priximmo/jenkins-helloworld/'
    sh '''
        javac Main.java
        '''
    }
    stage('run') {
    sh '''
        java Main
        '''
    }
}
