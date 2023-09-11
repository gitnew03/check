pipeline {
  agent any 
    stages {
      stage('one') {
        steps {
          echo 'Hi, this is Ayesha.'
        }
      }
      stage('two') {
        steps {
          input('Do you want to proceed')
        }
      }
      stage('three') {
        steps {
          mail bcc: '', body: 'Success', cc: '', from: '', replyTo: '', subject: 'Email', to: 'gitpractice03@gmail.com'
        }
      }
    }
}
