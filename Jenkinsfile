pipeline{
  agent any  
  stages{  
      stage("Run ansible playbook"){
        steps{
        ansiblePlaybook credentialsId: 'ssh-id', inventory: 'hosts', playbook: 'nginx_install.yaml'
        }
      }
  }
}
