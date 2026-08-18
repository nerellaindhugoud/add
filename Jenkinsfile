pipeline{
  agent any
  stages{
  stage('compile'){
    steps{
      sh 'javac SimpleAddition.java'
    }
  }
stage('Run'){
  steps{
    sh 'java SimpleAddition'
  }
}
}
}
