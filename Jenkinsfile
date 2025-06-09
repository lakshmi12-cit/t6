pipeline{
  agent any
  tools{
    maven "MAVEN_HOME"
  }
  stages{
    stage("Build"){
      steps{
        dir('p6') {
        bat "mvn clean install"
        }
      }
    }
  }
}
