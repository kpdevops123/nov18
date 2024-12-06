pipeline {
  agent any
  stages {
    stage("hello-world"){
      steps {
        println "hello world "
      }
    }
    stage ("creat a file"){
      steps{
        sh "sleep 20"
        sh "touch file.txt"
        println "hello stage 2"
      }
    }
  }
}
