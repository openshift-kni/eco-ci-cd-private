handle_ansible_vault
===============================
Handles the Ansible vault configuration for secure variable management.

Requirements
------------
bash
base64

Role Variables
--------------
| Variable                    | Required | Default | Choices | Comments                                 |
|-----------------------------|----------|---------|---------|------------------------------------------|
| temp_dir_path               | yes      | none    |         | Path to the temporary directory          |
| stamp_target_host           | yes      | none    |         | Target host to configure                 |
| remote_user_name            | yes      | none    |         | Remote user for SSH connections          |
| vault_password              | yes      | none    |         | Password for Ansible vault               |
| playbook_directory          | yes      | none    |         | Directory containing the playbook        |