## Ansible-Work-1 Project
# Overview
This is a test project to automate server configuration using Ansible. It includes playbooks for:
✅ Installing packages
✅ Setting up users
✅ Configuring services
✅ Managing files and directories

# Prerequisites
Ansible Installed (ansible --version)
SSH access to target machines
Proper inventory file setup (inventory.ini)

# Project Structure
ansible-work-1/
│── hostinventory.ini   # Inventory file with managed nodes
│── Readme.md           # Project documentation
│── sample.yml          # Main Ansible playbook
│── setup.yml           # System setup playbook
│── delete_devops.yml   # Cleanup playbook
│── single-play_1.yml   

## Playbooks Overview
- `deploy_php.yml`: Deploys a PHP application.
- `multi_os_playbook.yml`: Runs tasks on multiple OS platforms.
- `install_java.yml`: Installs Java on target nodes.
