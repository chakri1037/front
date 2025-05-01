pipeline {
  agent any
  parameters {
    string(name: 'ENV', defaultValue: 'dev', description: 'Environment')
  }
  environment {
    GREETING = "Hello from Jenkins"
  }
  stages {
    stage('Print') {
      steps {
        echo "${GREETING}, running in ${params.ENV} environment"
      }
    }
  }
}
