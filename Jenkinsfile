pipeline {
  agent any
  stages {
    stage('Hello') {
      parallel {
        stage('Hello') {
          steps {
            echo 'Hello World'
          }
        }

        stage('Build') {
          steps {
            sh '\'./gradlew clean build\''
          }
        }

      }
    }

  }
}