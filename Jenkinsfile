pipeline {
    agent any
    
    stages {       
        stage('Build APK') {
            steps {
                build job: 'Build APK'
            }
        }
        stage('Tes Android') {
            steps {
                build job: 'Test Android'
            }
        }
    }
}
