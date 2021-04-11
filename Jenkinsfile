pipeline {
  agent {
    node {
      label 'worker_node1'
    }

  }
  stages {
    stage('source') {
      steps {
        git 'git@github.com.cnpmjs.org:AckerlyXu/LearningJenkins.git'
      }
    }

  }
  environment {
    testkey = 'testvalue'
  }
}