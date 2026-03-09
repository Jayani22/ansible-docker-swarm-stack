# Ansible Automation: Docker Swarm with MySQL 8 and Redis

This project automates the installation and setup of **Docker Swarm**, **MySQL 8** and **Redis** using **Ansible**.

The playbook is designed with a **modular role-based structure** and supports both **Debian-based** and **RedHat-based** systems, allowing the automation to run interchangeably across different Linux distributions.

---

## Features

- Modular **Ansible role-based architecture**
- Supports **Debian and RedHat systems**
- Automated **Docker installation**
- Automatic **Docker Swarm initialization**
- Deploys **MySQL 8 container**
- Deploys **Redis container**

## Requirements

- Ansible installed on the control machine
- SSH access to the target server
- Python installed on the target machine

---

## How to Run the Playbook
Execute the following command from the project directory:
`ansible-playbook -i inventory playbook.yml`

## Verification

Check running containers:
`docker ps`

Check Docker Swarm:
`docker node ls`