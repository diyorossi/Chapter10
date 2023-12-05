pipeline {
  agent any
  stages {
    stage('Jenkinsfile') {
      steps {
        sh '''pipeline {
    agent {
        docker {
            // Ganti \'nama_image_docker\' dengan nama atau ID image Docker yang sesuai
            image \'jenkins/jenkins:lts\'
        }
    }
    
    stages {
        stage(\'Build\') {
            steps {
                // Tambahkan langkah-langkah build di sini
                sh \'echo "Building..."\'
            }
        }
        
        stage(\'Test\') {
            steps {
                // Tambahkan langkah-langkah pengujian di sini
                sh \'echo "Testing..."\'
            }
        }
        
        stage(\'Deploy\') {
            steps {
                // Tambahkan langkah-langkah deployment di sini
                sh \'echo "Deploying..."\'
            }
        }
    }
}'''
        }
      }

    }
  }