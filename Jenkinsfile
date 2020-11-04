pipeline {
  agent any
  triggers {
    githubPush()
  }
  stages {
    stage('Build') {
      steps {
        echo "Hello, this is Cami!"
      }
    }
  }
}
