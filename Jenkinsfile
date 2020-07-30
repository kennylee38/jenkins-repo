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
        echo "Just one more dummy step"
        echo "One more, just in case"
      }
    }
    stage('Deploy') {
      steps {
        echo "Drinking a coffee while the deploy runs"
        echo "This is a DEPLOY stage step"
      }
    }
  }
}
