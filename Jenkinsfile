pipeline {
  agent any
  stages {
    stage("hello-world") {
      steps {
        echo "hello world"
      }
    }
    stage("create a file") {
      steps {
        bat "echo. > file.txt"  // Create a file
        echo "hello stage 2"
        
      }
    }
  }
}
