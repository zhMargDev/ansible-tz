## Prerequisites

- Docker
- Docker Compose
- Ansible

## Setup

1. Clone the repository

2. Run docker container:
    docker-compose up -d

3. Run the Ansible playbook:
    ansible-playbook -i inventory playbook.yml

4. Access the static server at http://localhost/images and /images/filename.

5. Connect via ssh:
    use "ssh user1@localhost" command and password = 1234