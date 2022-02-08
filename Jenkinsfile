pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        tool(name: 'node-v18', type: 'nodejs')
        sh 'npm install'
      }
    }

  }
}