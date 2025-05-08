# Ansible Playbook Demo

This project contains a simple Ansible playbook to install and start Nginx on an Ubuntu server.

## Files

- `nginx-install.yml`: Ansible playbook to install and start Nginx.
- `hosts`: Sample inventory file listing the target server(s).

## How to Run

1. **Install Ansible:**
sudo apt update
sudo apt install ansible -y

2. **Update your `hosts` file:**
- Replace `your_server_ip_or_hostname` with your actual server IP or hostname.

3. **Run the playbook:**
ansible-playbook -i hosts nginx-install.yml


## Skills Practiced

- Ansible basics
- Automating software installation
- Service management on Ubuntu
