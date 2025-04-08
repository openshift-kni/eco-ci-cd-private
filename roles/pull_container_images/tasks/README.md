pull_container_images
===============================
Pulls required container images for testing and validation.

Requirements
------------
podman

Role Variables
--------------

| Variable                    | Required | Default | Choices | Comments                                 |
|-----------------------------|----------|---------|---------|------------------------------------------|
| temp_dir_path               | yes      | none    |         | Path to the temporary directory          |
| stamp_target_host           | yes      | none    |         | Target host to configure                 |
| remote_user_name            | yes      | none    |         | Remote user for SSH connections          |
| eco_validation_container    | yes      | none    |         | Container image for validation           |
| eco_gotests_container       | yes      | none    |         | Container image for Go tests             |
| podman_auth_path            | yes      | none    |         | Path to Podman authentication file       |