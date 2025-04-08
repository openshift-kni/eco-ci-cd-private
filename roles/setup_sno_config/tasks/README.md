setup_sno_config
===============================
Sets up Single Node OpenShift (SNO) configuration for the edge device.


Requirements
------------

oc
jq
base64

Role Variables
------------

| Variable                    | Required | Default | Choices | Comments                                 |
|-----------------------------|----------|---------|---------|------------------------------------------|
| temp_dir_path               | yes      | none    |         | Path to the temporary directory          |
| stamp_target_host           | yes      | none    |         | Target host to configure                 |
| remote_user_name            | yes      | none    |         | Remote user for SSH connections          |
| site_name_value             | yes      | none    |         | Site name                                |