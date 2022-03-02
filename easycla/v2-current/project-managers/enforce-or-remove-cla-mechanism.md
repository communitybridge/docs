# Enforce or Remove CLA Mechanism

Before you enable Git repositories for CLA check or remove them from CLA mechanism, you must add the [GitHub](add-and-manage-github-organizations.md#add-github-organization) or [Gerrit](add-and-manage-gerrit-organizations.md#add-gerrit-organization) or [GitLab](add-and-manage-gitlab-groups.md#add-gitlab-groups) organizations. You can perform the following activities with EasyCLA:

1\. Sign in to the [Project Control Center](https://projectadmin.lfx.linuxfoundation.org).

2\. Click a **project** of interest.

3\. From **Tools Status** drop-down menu, click **EasyCLA**.

![Tools Status Tab](<../../../.gitbook/assets/tools status tab (1).png>)

4\. Select the CLA group to which you have added the project.5. Click **Manage** next to the project for which you want to manage repositories.

* ​[Enforce CLA for GitHub Repositories](enforce-or-remove-cla-mechanism.md#enforce-or-remove-cla-mechanism-from-github-repositories)​
* ​[Enforce CLA for Gerrit Repositories​](enforce-or-remove-cla-mechanism.md#enforce-cla-mechanism-for-gerrit-repositories)
* [​Enforce CLA for GitLab Projects​](enforce-or-remove-cla-mechanism.md#enforce-or-remove-cla-mechanism-from-gitlab-projects)

## Enforce or Remove CLA Mechanism from GitHub Repositories <a href="#enforce-or-remove-cla-mechanism-from-github-repositories" id="enforce-or-remove-cla-mechanism-from-github-repositories"></a>

1. Under GitHub, select the added organization for which you want to manage repositories.
2. Turn on or turn off the **Enforce CLA** toggle key to enforce or remove all the repositories from CLA mechanism at a time.
3. To enforce CLA for individual repositories, select the check box next to a repository, and click **Save**.

![Add or Remove Git Repositories](<../../../.gitbook/assets/add or remove git repositories.png>)

## Enforce CLA Mechanism for Gerrit Repositories <a href="#enforce-cla-mechanism-for-gerrit-repositories" id="enforce-cla-mechanism-for-gerrit-repositories"></a>

After you add a [Gerrit organization](add-and-manage-gerrit-organizations.md#add-gerrit-organization), by default all of its repositories are CLA enabled. You cannot disable CLA for an individual Gerrit repository. However, you can [disassociate the Gerrit organization](add-and-manage-gerrit-organizations.md#disassociate-gerrit-organization) to disable CLA for the organization and all of its repositories.

![Gerrit Instance showing all its repositories CLA enabled](<../../../.gitbook/assets/gerrit instances.png>)

## Enforce or Remove CLA Mechanism from GitLab Projects <a href="#enforce-or-remove-cla-mechanism-from-gitlab-projects" id="enforce-or-remove-cla-mechanism-from-gitlab-projects"></a>

1. Under GitLab, select the added group for which you want to manage projects.
2. Turn on or turn off the **Enforce CLA** toggle key to enforce or remove all the projects from CLA mechanism at a time.
3. To enforce or remove CLA from individual projects, turn on the toggle key next to a project, and click **Yes**.

![Enforce or Remove CLA from GitLab](<../../../.gitbook/assets/enforce or remove CLA for GitLab.png>)
