# Instrument CentOS with AppDynamics using Ansible

The purpose of this repo is to provide a template for rapidly configuring a Cent machine with AppDynamics using Ansible.

You are free to copy the initial configurations, add your variables to the project, and extend the playbook as you see fit to accomplish your objectives.

## Minimal Configuration

1. Have a target host provisioned & running Cent VM, accessible over port 22, with SSH keys configured.
2. Copy `ansible/inventory.ini.dist` to `ansible/inventory.ini`.
3. Update your `inventory.ini` according to your host details & SSH key configuration.
4. Copy `ansible/variables.json.dist` to `ansible/variables.json`. 
5. Add or remove any specific data you'd like to in `ansible/variables.json`.
6. Ensure `bin/ap` is executable, and run it!
