pipeline
{
  agent {
    label 'slave'
  }
  stages
  {
    stage("GIT")
    {
      steps
      {
        git "git branch: 'main', url: 'https://github.com/amanbaghel101/maven.git'"
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
