pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Executing gradle"
                withGradle() {
                    sh './gradlew -v'
                }
                
            }
        }
    }
}
