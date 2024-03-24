Run adhoc command 
ansible io_workers -m ansible.builtin.shell -a "hostname" -i ./targets.yml

run developed playbook
ansible-playbook playbook.yml -i ./targets.yml --extra-vars "ansible_sudo_pass=<<your password >>"
