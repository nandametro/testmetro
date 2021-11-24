pipeline {
  agent {
    node {
      label 'main'
    }

  }
  stages {
    stage('maven verify') {
      steps {
        sh '''cd /home/nandakumar/PoC_TrainSim/serenityscreenplayrestassured;

/usr/share/maven/bin/mvn verify'''
      }
    }

  }
}