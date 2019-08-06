pipeline {
    agent any
    stages {
      stage('Linti HTML') {
        steps {
          sh 'tidy -q -e *.html'
        }
      }
    }
}