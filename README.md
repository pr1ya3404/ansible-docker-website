# Ansible Docker Nginx Deployment

## Project Overview
This project demonstrates how to automate Docker installation and deploy an Nginx container using Ansible.

## Tools Used
- Ansible
- Docker
- Nginx

## Project Structure

ansible-docker-website
│
├── inventory
│   └── hosts
│
├── playbooks
│   └── deploy-nginx.yml
│
└── website
    └── index.html


## How to Run the Project

1. Clone the repository

git clone https://github.com/pr1ya3404/ansible-docker-website.git

2. Navigate to project folder

cd ansible-docker-website

3. Run the Ansible playbook

ansible-playbook -i inventory/hosts playbooks/deploy-nginx.yml -K

## Output

The playbook installs Docker and deploys an Nginx container.

Open in browser:

http://localhost:8080

