# Project Managers

Project Managers are the project administrators or maintainers of the project. They set up a project on EasyCLA, and manage configuration details, such as the GitHub organization or Gerrit instance or GitLab groups, and associated repositories. The Project Manager uses the Project Control Center for these actions.

As a Project Manager, you can perform the following activities:

1. [Sign in to Project Control Center](../../v1-deprecated/project-managers/sign-in-to-the-easycla-management-console.md)
2. [Create New CLA Group](../../v1-deprecated/project-managers/install-the-easycla-application.md)
3. Add and manage [GitHub organization](broken-reference) or [Gerrit organization](broken-reference) or [GitLab Groups](broken-reference)
4. [Enforce CLA mechanism for GitHub/Gerrit/GitLab repositories](broken-reference)

Additionally, you can view and manage CLA details, GitHub, Gerrit, and GitLab organizations and repositories:

1. [View and Manage CLA Group Details](broken-reference)
2. [Add or Remove Project from CLA Group](broken-reference)
3. [View connection status of Git organizations and repositories](broken-reference)
4. [Disassociate GitHub organization](broken-reference)
5. [Disassociate Gerrit organization](broken-reference)
6. [Disassociate GitLab group](broken-reference)
7. [Enforce or Remove CLA Mechanism from GitHub/Gerrit/GitLab repositories](broken-reference)
8. [Uninstall the EasyCLA Application from git organization](../../v1-deprecated/project-managers/uninstall-the-easycla-application.md)

For EasyCLA integrated GitHub organizations and repositories, EasyCLA sends email notification to project managers regarding any changes to the repositories. EasyCLA takes the following actions for different events:

* **Repository Renamed: **EasyCLA updates GitHub repository table entry to match the new GitHub repository name, and notifies the project manager.
* **Repository Archived: **EasyCLA takes no action, however notifies the project manager that the repository is archived.
* **Repository Deleted: **EasyCLA** **disables the repository, and notifies the project manager.
* **Repository Moved to a Different Organization: **
  * If** **an EasyCLA enabled repository is moved from one organization to another within the same CLA Group, EasyCLA simply notifies the project manager about the action.
  * If** **a repository is moved from one organization to another where EasyCLA is not configured or the CLA Group is different, EasyCLA disables the repository, and notifies the project manager.
