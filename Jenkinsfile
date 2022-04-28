pipeline { 
    agent any  
    stages { 
        stage('Testing') {
          steps {
            echo 'running Tests'
            bat 'python finalLab.py'
          }
        }
        stage('Build') { 
            steps { 
               echo 'Building jar files...' 
               bat 'mvn package'
            }
        }
    }
}
