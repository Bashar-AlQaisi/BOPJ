pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'build completed'
      }
    }

    stage('test stages') {
      parallel {
        stage('test stages') {
          steps {
            echo 'run test'
          }
        }

        stage('test 1') {
          steps {
            echo 'run test1'
          }
        }

      }
    }

    stage('deploy') {
      steps {
        echo 'a'
      }
    }

  }
}