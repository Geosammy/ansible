pipeline {
  agent any
  stages {
  stage('build') {
    steps {
      git url: 'https://github.com/Geosammy/ansible.git'
      withMaven(globalMavenSettingsConfig: '', jdk: '', maven: '', mavenSettingsConfig: '', traceability: true) {
    // some block
}
      sh "mvn clean verify"
    }
  }

}
}
