pipeline {
  agent {
    node {
      label 'main'
    }

  }
  stages {
    stage('maven verify') {
      steps {
        sh '''cd /var/tmp/RSG_1.5_SystemTesting/serenityscreenplayrestassured;

/usr/share/maven/bin/mvn verify'''
      }
    }

  }
}