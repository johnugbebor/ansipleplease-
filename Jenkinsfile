pipeline{
  agent any  
  stages{  
      stage("Run ansible playbook"){
        steps{
       ansiblePlaybook credentialsId: 'admin', inventory: 'hosts', playbook: 'nginx_install.yaml'
        }
      }
  }
}
