pipeline {
  agent any
  stages {
    stage('Code Checkout') {
      agent any
      steps {
        git(url: 'https://github.com/Milan-Johnson/curriculum-app', branch: 'master')
      }
    }

  }
}