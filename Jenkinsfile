pipeline{
  agent any
  stages{
    stage('Checkout'){
      steps{
        git 'https://github.com/nandini23naik1/repo-publish.git'
      }
    }
    stage('Publish'){
      steps{
          publishHTML([
            allowmissing:true,
            alwaysLinktoLastBuild:false,
            KeepAll:false,
            reportDir:'.'
            reportFiles:'sample.html',
            reportName:'MY HTML PAGE'
            ])
      }
  }
}
          }
