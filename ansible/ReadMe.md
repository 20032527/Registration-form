Overview

This part automates the configuration of the server using Ansible. The goal is to install and set up Docker on an AWS EC2 instance so it is ready to deploy applications. Automation ensures consistent and error-free setup across all environments.

Files

install-docker.yml – Ansible playbook that installs Docker, configures it, and ensures it starts on boot.

inventory.ini – Contains the EC2 instance IP address and SSH key for remote connection.

Steps

Ansible connects to the EC2 instance using SSH.

The playbook updates the system, installs Docker, and enables it to start automatically.

After execution, Docker is ready to run containers on the server.