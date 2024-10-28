pipeline {
  agent any
  stages {
  stage('maven install') {
    steps {
      git url: 'https://github.com/Geosammy/ansible.git'
      withMaven(globalMavenSettingsConfig: '', jdk: '', maven: '3.9.9', mavenSettingsConfig: '', traceability: true) {
    sh ('mvn install')
}
    }
  }

}

}
