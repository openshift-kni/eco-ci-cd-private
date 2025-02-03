exec_ran_o2ims_compliance_tests
===============================

Runs the o2ims compliance tests playbook in `eco_validation_repo` then syncs the results.

Requirements
------------

Modules

- ansible.posix

Packages

- rsync

Role Variables
--------------

| Variable                     | Required | Default                                           | Choices | Comments |
|------------------------------|----------|---------------------------------------------------|---------|----------|
| eco_validation_repo          | no       | `git@github.com:openshift-kni/eco-validation.git` |         |          |
| eco_validation_repo_version  | no       | `dev`                                             |         |          |

