pipeline {
  agent any
  stages {
    stage('Setup') {
      steps {
        echo 'Deploy'
      }
    }
    stage('Minified Scripts') {
      steps {
        echo 'Minified Script'
      }
    }
    stage('Unit Test') {
      steps {
        echo 'Unit Test'
      }
    }
    stage('Build env, Manifest') {
      steps {
        echo 'Publish Manifest'
      }
    }
    stage('Build Release') {
      steps {
        echo 'Database and Aplication'
      }
    }
    stage('Distribute Release') {
      steps {
        echo 'Distribute to Octopus Deploy'
      }
    }
  }
}