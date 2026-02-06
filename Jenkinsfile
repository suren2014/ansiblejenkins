pipeline {
  agent {label "${LABEL_NAME}" }

  stages {
    stage('ANSIBLE PLAYBOOK') {
      steps {
              ansiblePlaybook(
                playbook: 'ansible/deploy.yml',
                inventory: 'ansible/hosts.ini'
                )
      }
