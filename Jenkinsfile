pipeline {
  agent any
  stages {
  stage('build') {
    steps {
      git url: 'https://github.com/Geosammy/ansible.git'
      sh "mvn clean verify"
    }
  }

}
}
