# Ansible

## Folder structure

Ansible needs a predefined folder structure, like so:

    .
    ├── playbook.yml
    ├── roles
    │   ├── common
    │   │   ├── defaults
    │   │   │   └── main.yml
    │   │   ├── tasks
    │   │   │   ├── apt.yml
    │   │   │   ├── main.yml
    │   │   │   ├── task1.yml
    │   │   │   ├── task2.yml
    │   │   │   └── yum.yml
    │   │   ├── templates
    │   │   │   ├── template1
    │   │   │   └── template2
    │   │   └── vars
    │   │       ├── Debian.yml
    │   │       └── Fedora.yml
    │   ├── role2
    │   ├── role3
    │   └── role4
    └── variables
        └── var.yml

This structure has been replicated in this repo for learning purposes.