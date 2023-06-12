# Ansible Collection - alex.k3s collection
Documentation for the collection.

# Install
ansible-galaxy collection install git+https://github.com/AlexanderWitteveen/ALEX.Ansible.K3S.git

# Use playbook
vars="{\"args_host\":\"hostname\"}"  
export ANSIBLE_CONFIG=/etc/ansible/ansible.cfg  
ansible-playbook alex.k3s.install -vv --extra-vars "$vars"  

