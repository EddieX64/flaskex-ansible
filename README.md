### Ansible playbook for test project

Usage: `ansible-playbook -i inventory jenkins.yml`
You can specify a group of hosts from inventory with `-l` flag, e.g. `ansible-playbook -i inventory -l jenkins_master jenkins.yml` 
