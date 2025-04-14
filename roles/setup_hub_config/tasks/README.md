setup_hub_config
===============================
Sets up the hub Kubernetes configuration on the target host.

Requirements
------------
None

Role Variables
--------------


| Variable                | Required | Default | Choices | Comments                                 |
|-----------------------------|----------|---------|---------|------------------------------------------|
| temp_dir_path               | yes      | none    |         | Path to the temporary directory          |
| stamp_target_host           | yes      | none    |         | Target host to configure                 |
| remote_user_name            | yes      | none    |         | Remote user for SSH connections          |
| cluster_configs_directory   | yes      | none    |         | Directory containing cluster configs     |