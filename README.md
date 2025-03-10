Ansible Apache Deployment

This project demonstrates the automated deployment of the Apache HTTP Server using Ansible. The playbook handles installing, configuring, and starting Apache on multiple virtual machines (VMs) through Ansible automation.

Prerequisites

Ansible installed on the control node.

A virtualization tool like Multipass to manage VMs.

Properly configured inventory file.

SSH key-based authentication set up between the control node and managed nodes.

Project Structure : 

├── ansible.cfg
├── inventory
├── playbook_DeployApache.yml
├── apache.conf.j2
└── README.md

Verfiy & Test Screenshots :

![image](https://github.com/user-attachments/assets/b3e72e34-4101-43f9-9a01-00d09e498363)


![image](https://github.com/user-attachments/assets/54d785d1-b0df-44d5-8eed-fa19df56887a)



