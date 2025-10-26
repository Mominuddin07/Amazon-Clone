pipeline {
  agent any
  triggers { githubPush() }   // build on GitHub push
  stages {
    stage('Checkout') { steps { checkout scm } }
    stage('Build')    { steps { echo 'Build step' } }
    stage('Test')     { steps { echo 'Run tests here' } }
  }
}
