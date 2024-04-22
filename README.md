This repository contains Ansible playbooks and Bash scripts to automate the setup of a LAMP stack for a Laravel application on Ubuntu servers.

Prerequisites
Before running the playbooks, make sure you have:

Ansible installed on your local machine.
Two Ubuntu servers (one for the master and one for the slave) accessible over SSH.
Usage:
1. Clone this repository to your local machine
2. Navigate to the repository directory
3. Update the inventory file (hosts.yml) with the IP addresses of your master and slave servers
4. Run the Ansible playbook to set up the LAMP stack
5. Once the playbook execution is complete, SSH into your master server and run the deploy script
6. Follow the prompts to set up your Laravel application. Make sure to replace placeholders with your actual database details
7. Access your Laravel application in a web browser by navigating to the IP address of your server
