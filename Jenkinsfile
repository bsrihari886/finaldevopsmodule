pipeline
{
  agent any
  stages{
    stage("Deploy"){
      steps
      {
        echo"deploy succesful"
        bat"mvn compile"
      }
    }
     stage("Build"){
      steps
      {
        echo"build succesful"
        bat"mvn clean"
      }
    }
    stage("Test"){
      steps
      {
        echo"test succesful"
        bat"mvn test"
      }
    }
  }
}
