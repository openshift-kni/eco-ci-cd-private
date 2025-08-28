prepare_dci_pipeline_files
===============================
Prepares the DCI pipeline files for execution.

Requirements
------------
python3

Role Variables
--------------
| Variable                    | Required | Default | Choices    | Comments                           |
|-----------------------------|----------|---------|------------|------------------------------------|
| temp_dir_path               | yes      | none    |            | Path to the temporary directory    |
| stamp_target_host           | yes      | none    |            | Target host to configure           |
| remote_user_name            | yes      | none    |            | Remote user for SSH connections    |
| dci_pipeline_files          | yes      | none    |            | DCI pipeline files to use          |
| prow_pipeline_id            | yes      | none    |            | Pipeline ID                        |
| latency_duration            | no       | "1800"  |            | Latency test duration in seconds   |
| ocp_version                 | yes      | none    |            | OpenShift version                  |
| stamp_value                 | yes      | none    |            | STAMP environment value            |
| dci_remote_ci               | yes      | none    |            | DCI remote CI information          |
| site_name_value             | yes      | none    |            | Site name                          |
| eco_validation_container    | yes      | none    |            | Container image for validation     |
| ansible_skip_tags_value     | yes      | none    |            | Ansible tags to be skipped         |
| edu_ptp_value               | yes      | none    | true/false | Run PTP tests                      |
| copy_to_prow                | yes      | none    | true/false | Copy files to Prow server          |
| prow_junit_temp_directory   | yes      | none    |            | Temporary directory for Prow JUnit |
