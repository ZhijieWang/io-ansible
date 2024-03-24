Install Ansible

https://docs.ansible.com/ansible/latest/getting_started/get_started_ansible.html#get-started-ansible

This is not an official repo from IO.NET Team. Use with your own risk, fork and PR welcome.

Read the files and Ansible docs, not difficult

Run adhoc command 

`ansible io_workers -m ansible.builtin.shell -a "hostname" -i ./targets.yml`

Run playbook

`ansible-playbook playbook.yml -i ./targets.yml --extra-vars "ansible_sudo_pass=<<your password >>"`
