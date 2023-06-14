node{
 stage('Clone') {
  git branch: 'main', url: 'https://github.com/samzri1/ansible_jenkins'
  }
 stage('Ansible') {
  sh 'ansible-playbook roles/* -i mon_inventaire.ini'
  }
}
