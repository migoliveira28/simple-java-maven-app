pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                sh 'mvn -DskipTests clean install package' 
            }
        }
    }
}
