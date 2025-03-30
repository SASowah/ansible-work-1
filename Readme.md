## Ansible-Work-1 Project
# Overview
A Demo project to automate server configuration using Ansible. It includes playbooks for:
Installing packages
Setting up users
Configuring services
Managing files and directories

# Prerequisites
Ansible Installed (ansible --version)
SSH access to target machines
Proper inventory file setup (inventory.ini)

# Project Structure
ansible-work-1/
│── angular/  
│── apache/           
│── html/  
│── inventories/      # Inventory file with managed nodes
      │── inventory.ini
│── php/          
│── playbooks/        # Main Ansible playbook
      │── deploy_angular.yml
      │── deploy_ecommerce.yml
      │── deploy_html.yml
      │── deploy_php.yml
      │── dynamic_playbook.yml
      │── example_playbook.yml
      │── food_service.yml
      │── httpd.yml
      │── httpd_config.yml
      │── install_java.yml
      │── maintenance.yml
      │── multi_role_playbook.yml
      │── multi_os_playbook.yml
      │── multi_os_playbook_p2.yml
      │── server_setup.yml
      │── static_page_playbook.yml
      │── ubuntu_setup.yml
│── Maintenance.html/  
│── Readme.md        
│── dynamic.j2  
│── variables.yml



## Playbooks Overview
* deploy_php.yml`: Deploys a PHP application.
* multi_os_playbook.yml`: Runs tasks on multiple OS platforms.
* install_java.yml`: Installs Java on target nodes.
