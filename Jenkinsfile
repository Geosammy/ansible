pipeline {
  agent any
  stages {
  stage('maven install') {
    steps {
      withMaven(globalMavenSettingsConfig: '', jdk: '', maven: '') {
    sh 'mvn clean install'
}
    }
  }

}

}
