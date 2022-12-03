pipeline {
    agent any
  
    options {
        skipDefaultCheckout true
    }
    
    stages {       
        stage('Build apk') {
            steps {
                build job: 'build apk'
            }
        }
        stage('Tes Android') {
            steps {
                build job: 'test android'
            }
        }
    }
}
