pipeline {
    agent any 
    stages {
  stage('checkout') { 
      
            steps {
                git branch:"main",url:"https://github.com/zerroukiimane/NewRepoPipeline.git"
            }
        }
      stages {
  stage('Build') { 
      
            steps {
               bat "php index.php"
            }
        }
            stages {
  stage('Test') { 
      
            steps {
                echo 'Testing...'
            }
  }
            }
        }
    }
}
