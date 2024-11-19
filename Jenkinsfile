pipeline {
  agent any 
  tools {
        gradle 'gradle' 
  }
  stages {
    stage('Build with Gradle') {
            steps {
                script {
                    echo "Using Gradle to build the project..."
                    sh 'gradle --version'
                    sh 'gradle build'
                }
            }
        }
  }
}
