pipeline {
  agent any
  stages {
    stage('Build'){
      steps {
        echo "This should run on the BUILD stage"
        echo "Second step on BUILD"
      }
    }
    stage('Test') {
      steps {
        echo "This is a TEST stage step"
      }
    }
    stage('Deploy') {
      steps {
        echo "This is a DEPLOY stage step"
      }
    }
  }
}
