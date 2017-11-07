pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building..'
      }
    }
    stage('Test') {
      steps {
        echo 'Testing..'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploying....'
      }
    }
    stage('FixedToDelimiter') {
      steps {
        python '"C:\\Users\\c24088745\\Documents\\MyFiles\\myowntestings\\FixedWidthToDelimiter\\FixedWidthToDelimiter.py" -i Tap80.txt -c tap80Config.txt'
      }
    }
  }
}
