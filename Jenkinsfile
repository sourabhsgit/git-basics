pipeline {
  agent any
  stages {
    stage('download') {
      steps {
        readFile(file: 'abc.txt', encoding: 'md5')
      }
    }

  }
}