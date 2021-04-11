pipeline {
  agent {
    node {
      label 'worker_node1'
    }

  }
  stages {
    stage('source') {
      steps {
        git 'https://github.com.cnpmjs.org/AckerlyXu/LearningJenkins.git'
      }
    }

  }
  environment {
    testkey = 'testvalue'
  }
}