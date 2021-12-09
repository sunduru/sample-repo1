
pipeline{
  agent any
  stages{
    stage('cloning repo'){
      steps{
        script{
          git url: "https://github.com/sunduru/sample-repo1.git", branch: "main"
        }
        sh "cat README.md"
      }
    }
  }
}
