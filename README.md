# examples for ansible-playbooks
```shell
#for dynamicall using jinja2 templated
ansible-playbook -v preconfig/json_read.yml
#static
ansible-playbook -i inventory/all_host.ini -b -u root -e "ansible_ssh_pass=nnnn ansible_become_pass=" -v preconfig/preconfig.yaml
```