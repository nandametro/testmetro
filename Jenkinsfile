pipeline {
  agent {
    node {
      label 'main'
    }

  }
  stages {
    stage('maven install') {
      steps {
        tool 'maven3.8.4'
      }
    }

    stage('maven verify') {
      steps {
        sh '''cd /home/nandakumar/PoC_TrainSim/serenityscreenplayrestassured;

mvn verify'''
      }
    }

  }
}