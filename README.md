Ansible Apache Deployment

This project demonstrates the automated deployment of the Apache HTTP Server using Ansible. The playbook handles installing, configuring, and starting Apache on multiple virtual machines (VMs) through Ansible automation.

Prerequisites

Ansible installed on the control node.

A virtualization tool like Multipass to manage VMs.

Properly configured inventory file.

SSH key-based authentication set up between the control node and managed nodes.

Project Structure:
project4/
├── ansible.cfg
├── inventory
├── playbook_DeployApache.yml
├── apache.conf.j2
└── README.md
