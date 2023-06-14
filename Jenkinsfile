node{
 stage('Clone') {
  git branch: 'main', credentialsId: '10fedfbb-8a4e-4700-b3cd-3ad56c87c166', url: 'https://github.com/obabaldbiyat/Ansible_2VMs_Sibles_ApachePHP_MYSQL'
  }
 stage('Ansible') {
  sh 'ansible-playbook -i mon_inventaire.ini Main_Playbook.yaml'
  }
}
