pipeline {
  agent any
  stages {
    stage('Checkout Code') {
      steps {
        git(url: 'https://github.com/usamazaheerr/curriculum-app', branch: 'dev')
      }
    }

    stage('Front-End Unit Test / Shell Script') {
      steps {
        sh 'cd curriculum-front && npm i && npm run test:unit'
      }
    }

  }
}