run_edu_tests
===============================
Runs the eDU (edge Device Unit) tests.

Requirements
------------

python3
dci-pipeline (when not skipping DCI)

Role Variables
--------------
| Variable                    | Required | Default | Choices       | Comments                             |
|-----------------------------|----------|---------|---------------|--------------------------------------|
| temp_dir_path               | yes      | none    |               | Path to the temporary directory      |
| stamp_target_host           | yes      | none    |               | Target host to configure             |
| remote_user_name            | yes      | none    |               | Remote user for SSH connections      |
| dci_pipeline_files          | yes      | none    |               | DCI pipeline files to use            |
| skip_dci                    | no       | false   | true, false   | Boolean to skip DCI tests            |
| site_name_value             | yes      | none    |               | Site name                            |
| prow_pipeline_id            | yes      | none    |               | Pipeline ID                          |
| playbook_directory          | yes      | none    |               | Directory containing the playbook    |