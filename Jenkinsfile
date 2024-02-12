pipeline {
 agent any
  stages { 
    stage('checkout stage') {
      steps {
        sh 'git clone https://github.com/Sudhamshetty7/Ansible_project.git'
      }
    }
    stage('running playbook') {
     steps {
       sh 'ansible-playbook -i hosts sample.yml'
     }
    } 
  }
}
