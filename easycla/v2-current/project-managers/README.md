# Project Managers

Project Managers are the project administrators or maintainers of the project. They set up a project on EasyCLA, and manage configuration details, such as the GitHub organization or Gerrit instance or GitLab groups, and associated repositories. The Project Manager uses the Project Control Center for these actions.

As a Project Manager, you can perform the following activities:

1. [Sign in to Project Control Center](sign-in-to-project-control-center.md)
2. [Create New CLA Group](create-new-cla-group.md)
3. [Add or Remove Project from CLA Group](add-or-remove-a-project-from-cla-group.md)
4. Add and manage [GitHub organization](add-and-manage-github-organizations.md) or [Gerrit organization](add-and-manage-gerrit-organizations.md) or [GitLab Groups](add-and-manage-gitlab-groups.md)
5. [Enforce CLA mechanism for GitHub/Gerrit/GitLab repositories](enforce-or-remove-cla-mechanism.md)
6. [Uninstall the EasyCLA Application from git organization](uninstall-the-easycla-application.md)

Additionally, you can view and manage CLA details, GitHub, Gerrit, and GitLab organizations and repositories:

1. [View and Manage CLA Group Details](view-and-manage-cla-group-details.md)
2. [View connection status of Git organizations and repositories](view-connection-status-of-git-organizations-and-repositories.md)

For EasyCLA integrated GitHub organizations and repositories, EasyCLA sends email notification to project managers regarding any changes to the repositories. EasyCLA takes the following actions for different events:

* **Repository Renamed:** EasyCLA updates GitHub repository table entry to match the new GitHub repository name, and notifies the project manager.
* **Repository Archived:** EasyCLA takes no action, however notifies the project manager that the repository is archived.
* **Repository Deleted:** EasyCLA disables the repository, and notifies the project manager.
* **Repository Moved to a Different Organization:**
  * If an EasyCLA enabled repository is moved from one organization to another within the same CLA Group, EasyCLA simply notifies the project manager about the action.
  * If a repository is moved from one organization to another where EasyCLA is not configured or the CLA Group is different, EasyCLA disables the repository, and notifies the project manager.
