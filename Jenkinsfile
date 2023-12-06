pipeline {
  agent any
  stages {
    stage('Jenkinsfile') {
      steps {
        sh '''pipeline {
    agent any

    stages {
        stage(\'Code Quality\') {
            steps {
                script {
                    echo \'Checking code quality\'
                }
            }
        }

        stage(\'Unit Tests\') {
            steps {
                script {
                    echo \'Testing the application\'
                }
            }
        }

        stage(\'Build\') {
            steps {
                script {
                    echo \'Creating application package\'
                }
            }
        }

        stage(\'Delivery\') {
            steps {
                script {
                    echo \'Uploading the artifact to a repository\'
                }
            }
        }

        stage(\'Deploy\') {
            steps {
                script {
                    echo \'Deploying the application\'
                }
            }
        }
    }
}
'''
        }
      }

    }
  }