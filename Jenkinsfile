pipeline
{
  agent any
  stages
  {
    stage("GIT")
    {
      steps
      {
        git "https://github.com/ramyachetty/maven"
      }
    }
    stage("Run")
    {
      steps
      {
        bat "clean install"
      }
    }
  }
}
