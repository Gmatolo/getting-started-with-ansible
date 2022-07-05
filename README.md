# getting-started-with-ansible

Getting started with Ansible

Installation is easy as long as you already have Python installed.
`pip install --user ansible`

## Whats a Playbook

YAML files that contain a series of commands to run on the target machines. These commands can be used to:

1. Update the webserver
2. Migrate the database
3. Install Dependencies
4. Copy production files

A Playbook includes the following primary sections:

- name - Name of the playbook(yml file).
- hosts - These are the target machines / hosts that are configured by the playbook.
- tasks - the ordered list of commands to run on the target host. Individual commands can be bundled into a module to essentially a library functions.
- roles - Is defined directory structure used within a playbook to bring modularity, and keep the playbook clean and readable in complex orchestrations.
