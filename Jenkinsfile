pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'build completed'
      }
    }

    stage('test1') {
      parallel {
        stage('test1') {
          steps {
            echo 'test1 done'
          }
        }

        stage('test2') {
          steps {
            echo 'test2 done'
          }
        }

      }
    }

    stage('deploy') {
      steps {
        echo 'deployment completed'
      }
    }

  }
}