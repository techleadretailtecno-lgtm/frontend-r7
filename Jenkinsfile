pipeline {
 agent any
 stages {
  stage('Build') {
   steps {
    sh 'docker build -t retailfactory/frontend-r7:latest .'
   }
  }
  stage('Push') {
   steps {
    sh 'docker push retailfactory/frontend-r7:latest'
   }
  }
 }
}
