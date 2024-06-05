node {
    stage('Build') {
    git 'https://github.com/pevn14/jenkins-helloworld/'
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
