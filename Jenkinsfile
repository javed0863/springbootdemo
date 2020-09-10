pipeline {
  agent any
  
  stages {
    stage("build") {
      steps {
        echo 'Building App...'
        mvn clean install
      }
    }
    
    stage("test") {
      steps {
        echo 'Skipping test...'
      }
    }
    
    stage("deploy") {
      steps {
        echo 'Deploying WAR...'
      }
    }
  }
}
