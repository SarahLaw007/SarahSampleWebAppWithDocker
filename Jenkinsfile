pipeline {
  agent any
  stages {
    stage('Build .NET Core') {
      steps {
        sh '''dotnet clean



'''
        sh 'dotnet build --configuration Release'
      }
    }
  }
}