pipeline {
  agent any
  stages {
  stage('maven install') {
    steps {
      withMaven(globalMavenSettingsConfig: '', jdk: '', maven: '', mavenSettingsConfig: '', traceability: true) {
    http 'maven clean install'
}
    }
  }

}

}