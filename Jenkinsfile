pipeline {
  agent any
  
  tools {nodejs "node 15"}
  stages {
    stage('Build') {
      steps {
        git 'https://github.com/shashankreddya/crud_app.git'
        sh 'npm install'
      }}}}
