---

---

# Ansible Automation Platform Configuration as Code Collections

## Introduction

Several collections have been created by the Red Hat Communities of Practice to assist with configuring aspects of the Ansible Automation Platform (AAP) using configuration as code practices. This site will guide you through these collections, the use cases, how to use and strategies for scaling appropriately.

### Where to get and maintain this document

This document is published to [https://redhat-cop.github.io/aap_config_as_code_docs/](https://redhat-cop.github.io/aap_config_as_code_docs/), it is open source and its source code is maintained at [https://github.com/redhat-cop/aap_config_as_code_docs/](https://github.com/redhat-cop/aap_config_as_code_docs/).

## Getting Help

We are on the Ansible Forums and Matrix, if you want to discuss something, ask for help, or participate in the community, please use the #infra-config-as-code tag on the forum, or post to the chat in Matrix.

[Ansible Forums](https://forum.ansible.com/tag/infra-config-as-code)

[Matrix Chat Room](https://matrix.to/#/#aap_config_as_code:ansible.com)

## AAP Config as Code Collections
NOTE: Further documentation for these collections will be stored here.

Links to Ansible Automation Platform Collections

|Collection Name|Purpose|
|---------|---------|
|[awx.awx/Ansible.controller repo](https://github.com/ansible/awx/tree/devel/awx_collection)|Automation controller modules|
|[Ansible Hub Configuration](https://github.com/ansible/automation_hub_collection)|Automation hub configuration|

Links to other Validated Configuration Collections for Ansible Automation Platform

|Collection Name|Purpose|
|---------|---------|
|[Controller Configuration](https://github.com/redhat-cop/controller_configuration)|Automation controller configuration|
|[EE Utilities](https://github.com/redhat-cop/ee_utilities)|Execution Environment creation utilities|
|[AAP installation Utilities](https://github.com/redhat-cop/aap_utilities)|Ansible Automation Platform Utilities|
|[AAP Configuration Template](https://github.com/redhat-cop/aap_configuration_template)|Configuration Template for this suite|

### Controller Configuration:
* [ad_hoc_command.md](collections/controller_configuration/ad_hoc_command.html)
* [ad_hoc_command_cancel.md](collections/controller_configuration/ad_hoc_command_cancel.html)
* [applications.md](collections/controller_configuration/applications.html)
* [bulk_host_create.md](collections/controller_configuration/bulk_host_create.html)
* [bulk_job_launch.md](collections/controller_configuration/bulk_job_launch.html)
* [credential_input_sources.md](collections/controller_configuration/credential_input_sources.html)
* [credential_types.md](collections/controller_configuration/credential_types.html)
* [credentials.md](collections/controller_configuration/credentials.html)
* [dispatch.md](collections/controller_configuration/dispatch.html)
* [execution_environments.md](collections/controller_configuration/execution_environments.html)
* [filetree_create.md](collections/controller_configuration/filetree_create.html)
* [filetree_read.md](collections/controller_configuration/filetree_read.html)
* [global_vars.md](collections/controller_configuration/global_vars.html)
* [groups.md](collections/controller_configuration/groups.html)
* [hosts.md](collections/controller_configuration/hosts.html)
* [instance_groups.md](collections/controller_configuration/instance_groups.html)
* [instances.md](collections/controller_configuration/instances.html)
* [inventories.md](collections/controller_configuration/inventories.html)
* [inventory_source_update.md](collections/controller_configuration/inventory_source_update.html)
* [inventory_sources.md](collections/controller_configuration/inventory_sources.html)
* [job_launch.md](collections/controller_configuration/job_launch.html)
* [job_templates.md](collections/controller_configuration/job_templates.html)
* [jobs_cancel.md](collections/controller_configuration/jobs_cancel.html)
* [labels.md](collections/controller_configuration/labels.html)
* [license.md](collections/controller_configuration/license.html)
* [notification_templates.md](collections/controller_configuration/notification_templates.html)
* [object_diff.md](collections/controller_configuration/object_diff.html)
* [organizations.md](collections/controller_configuration/organizations.html)
* [project_update.md](collections/controller_configuration/project_update.html)
* [projects.md](collections/controller_configuration/projects.html)
* [roles.md](collections/controller_configuration/roles.html)
* [schedules.md](collections/controller_configuration/schedules.html)
* [settings.md](collections/controller_configuration/settings.html)
* [teams.md](collections/controller_configuration/teams.html)
* [users.md](collections/controller_configuration/users.html)
* [workflow_job_templates.md](collections/controller_configuration/workflow_job_templates.html)
* [workflow_launch.md](collections/controller_configuration/workflow_launch.html)

### Ansible Hub Configuration:
* [ansible_config.md](collections/galaxy_collection/ansible_config.html)
* [collection.md](collections/galaxy_collection/collection.html)
* [collection_remote.md](collections/galaxy_collection/collection_remote.html)
* [collection_repository.md](collections/galaxy_collection/collection_repository.html)
* [collection_repository_sync.md](collections/galaxy_collection/collection_repository_sync.html)
* [dispatch.md](collections/galaxy_collection/dispatch.html)
* [ee_image.md](collections/galaxy_collection/ee_image.html)
* [ee_namespace.md](collections/galaxy_collection/ee_namespace.html)
* [ee_registry.md](collections/galaxy_collection/ee_registry.html)
* [ee_registry_index.md](collections/galaxy_collection/ee_registry_index.html)
* [ee_registry_sync.md](collections/galaxy_collection/ee_registry_sync.html)
* [ee_repository.md](collections/galaxy_collection/ee_repository.html)
* [ee_repository_sync.md](collections/galaxy_collection/ee_repository_sync.html)
* [group.md](collections/galaxy_collection/group.html)
* [group_roles.md](collections/galaxy_collection/group_roles.html)
* [namespace.md](collections/galaxy_collection/namespace.html)
* [publish.md](collections/galaxy_collection/publish.html)
* [repository.md](collections/galaxy_collection/repository.html)
* [repository_sync.md](collections/galaxy_collection/repository_sync.html)
* [role.md](collections/galaxy_collection/role.html)
* [user.md](collections/galaxy_collection/user.html)

### Event Driven Ansible Configuration:
* [credential.md](collections/eda_config/credential.html)
* [project.md](collections/eda_config/project.html)
* [project_sync.md](collections/eda_config/project_sync.html)

### AAP Installation Utilities:
* [aap_backup.md](collections/aap_utilities/aap_backup.html)
* [aap_certs.md](collections/aap_utilities/aap_certs.html)
* [aap_ocp_install.md](collections/aap_utilities/aap_ocp_install.html)
* [aap_remove.md](collections/aap_utilities/aap_remove.html)
* [aap_restore.md](collections/aap_utilities/aap_restore.html)
* [aap_setup_download.md](collections/aap_utilities/aap_setup_download.html)
* [aap_setup_install.md](collections/aap_utilities/aap_setup_install.html)
* [aap_setup_prepare.md](collections/aap_utilities/aap_setup_prepare.html)
* [git_ssh_setup.md](collections/aap_utilities/git_ssh_setup.html)
* [kerberos.md](collections/aap_utilities/kerberos.html)

### Execution Environment Utilities:
* [ee_builder.md](collections/ee_utilities/ee_builder.html)
* [virtualenv_migrate.md](collections/ee_utilities/virtualenv_migrate.html)

## Contributing to this Documentation
We welcome community contributions to this documentation, or any of the mentioned collections. If you find problems, please open an issue and consider creating a PR against this, or any relevant, repository. More information about contributing can be found in our [Contribution Guidelines](CONTRIBUTE.html).

We have a community meeting every 4 weeks. Find the agenda in the issues and the calendar invitation below:

[Calendar](https://raw.githubusercontent.com/redhat-cop/controller_configuration/devel/docs/aap_config_as_code_public_meeting.ics)

## Code of Conduct

This repository follows the Ansible project's
[Code of Conduct](https://docs.ansible.com/ansible/latest/community/code_of_conduct.html).
Please read and familiarize yourself with this document.

## Licensing

GNU General Public License v3.0 or later.

See [LICENSE](https://www.gnu.org/licenses/gpl-3.0.txt) to see the full text.