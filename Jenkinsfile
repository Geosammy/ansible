pipeline {
  agent any
  stages {
  stage('maven install') {
    steps {
      git url: 'https://github.com/Geosammy/ansible.git'
      withMaven(globalMavenSettingsConfig: '', jdk: '', maven: 'maven3', mavenSettingsConfig: '', traceability: true) {
    sh 'mvn clean install'
}
    }
  }

}

}
