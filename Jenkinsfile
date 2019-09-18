pipeline {
  agent {
    node {
      label 'slave'
    }

  }
  stages {
    stage('preparation') {
      steps {
        git 'https://github.com/suryachinu/Maven-Java-Project.git'
      }
    }
  }
}