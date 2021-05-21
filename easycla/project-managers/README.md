# Project Managers

A Project Manager sets up a project on EasyCLA, and manages configuration details, such as the GitHub organization or Gerrit instance and associated repositories. The Project Manager uses the Project Control Center for these actions.

As a Project Manager, you can perform the following activities:

1. [Sign in to Project Control Center](sign-in-to-project-control-center.md)
2. [Create New CLA Group](create-new-cla-group.md)
3. [Add GitHub organization](add-and-manage-git-organizations-and-repositories/#add-github-organization) or [Gerrit organization](add-and-manage-git-organizations-and-repositories/#add-gerrit-organization)
4. [Enforce CLA monitoring for GitHub repositories](add-and-manage-git-organizations-and-repositories/enforce-or-remove-cla-monitoring.md#enforce-or-remove-cla-monitoring-from-github-repositories) or [Gerrit repositories](add-and-manage-git-organizations-and-repositories/enforce-or-remove-cla-monitoring.md#enforce-cla-monitoring-for-gerrit-repositories)

Additionally, you can view and manage CLA details, GitHub and Gerrit organizations and repositories:

1. [View and Manage CLA Group Details](view-and-manage-cla-group-details.md)
2. [Add or Remove Project from CLA Group](add-or-remove-a-project-from-cla-group.md)
3. [View connection status of Git organizations and repositories](add-and-manage-git-organizations-and-repositories/view-connection-status-of-git-organizations-and-repositories.md)
4. [Disassociate GitHub organization](add-and-manage-git-organizations-and-repositories/#disassociate-github-organization)
5. [Disassociate Gerrit organization](add-and-manage-git-organizations-and-repositories/#disassociate-gerrit-organization)
6. [Remove CLA Monitoring from GitHub repositories](add-and-manage-git-organizations-and-repositories/enforce-or-remove-cla-monitoring.md#enforce-or-remove-cla-monitoring-from-github-repositories)
7. [Uninstall the EasyCLA Application from git organization](uninstall-the-easycla-application.md)

For EasyCLA integrated GitHub organizations, and repositories, EasyCLA sends email notification to project managers regarding any changes to the repositories. EasyCLA takes the following actions for different events:

* **Repository Renamed:** EasyCLA updates GitHub repository table entry to match the new GitHub repository name, and notifies the project manager.
* **Repository Archived:** EasyCLA takes no action, however notifies the project manager that the repository is archived.
* **Repository Deleted:** EasyCLA ****disables the repository, and notifies the project manager.
* **Repository Moved to a Different Organization:** 
  * If ****an EasyCLA enabled repository is moved from one organization to another within the same CLA Group, EasyCLA simply notifies the project manager about the action.
  * If ****a repository is moved from one organization to another where EasyCLA is not configured or the CLA Group is different, EasyCLA disables the repository, and notifies the project manager.

