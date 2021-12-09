
pipeline{
  agent any
  stages{
    stage('cloning repo'){
      steps{
        git url: "https://github.com/sunduru/sample-repo1.git", branch: "main"
        cat README.md
        echo "hi"
      }
    }
  }
}
