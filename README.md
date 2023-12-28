# Manjaro Sway Desktop Ansible

1. Install ansible
```
yay -S ansible
```
2. Clone the repo
3. Install requirements 
```
ansible-galaxy install -r requirements.yml
```
4. Run the playbook 
```
ansible-playbook playbook.yml -i inventory -K
```