pipeline {
  agent { 
    docker { image "maven" }
    }

  stages {
    stage('maven') {
      steps {
        sh "mvn -version"
        sh "java -version"
      }
    }
  }
}
