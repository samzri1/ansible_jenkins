node{
 stage('Clone') {
  git branch: 'main', url: 'https://github.com/samzri1/ansible_jenkins'
  }
 stage('Ansible') {
  sh 'ansible-playbook -i mon_inventaire.ini Main_Playbook.yaml'
  }
}
