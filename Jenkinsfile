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
        bat "timeout /t 20 >nul" // Equivalent to sleep on Windows
        bat "echo. > file.txt"  // Create a file
        echo "hello stage 2"
      }
    }
  }
}
