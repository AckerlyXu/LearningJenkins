pipeline {
  agent {
    node {
      label 'worker_node2'
    }

  }
  stages {
    stage('source') {
      steps {
        git 'https://github.com/AckerlyXu/LearningJenkins.git'
      }
    }

  }
  environment {
    testkey = 'testvalue'
  }
}