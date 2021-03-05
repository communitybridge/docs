# Enforce or Remove CLA Monitoring

Before you enable GitHub repositories for CLA monitoring or remove them from CLA monitoring, you must add the Git organizations— [add GitHub organization](./#add-github-organization) or [add Gerrit organization](./#add-gerrit-organization). You can perform the following activities with EasyCLA:

1. [Sign in](../sign-in-to-project-control-center.md).
2. Click a **project** of interest.
3. Navigate to **Tools** tab, and click **CLA**.

![Tools](../../../.gitbook/assets/tools-tab.png)

4. Select the CLA group to which you have added the project.

5. Click **Manage** next to the project for which you want to manage repositories.

* [Enforce CLA Monitoring for GitHub Repositories](enforce-or-remove-cla-monitoring.md#enforce-or-remove-cla-monitoring-from-github-repositories)
* [Enforce CLA Monitoring for Gerrit Repositories](enforce-or-remove-cla-monitoring.md#enforce-cla-monitoring-for-gerrit-repositories)

## Enforce or Remove CLA Monitoring from GitHub Repositories

1. Under GitHub, select the added organization for which you want to manage repositories.
2. Turn on or turn off the **Enforce CLA** toggle key to enforce or remove all the repositories from CLA monitoring at a time.
3. To enforce CLA for individual repositories, select the check box next to a repository, and click **Save**.

![Add or Remove Git Repositories](../../../.gitbook/assets/add-or-remove-git-repositories.png)

## Enforce CLA Monitoring for Gerrit Repositories

After you[ add a Gerrit organization](./#add-gerrit-organization), by default all of its repositories are CLA enabled. You cannot disable CLA for an individual Gerrit repository. However, you can [disassociate the Gerrit organization](./#disassociate-gerrit-organization) to disable CLA for the organization and all of its repositories.

![Gerrit Instance showing all its repositories CLA enabled](../../../.gitbook/assets/gerrit-instances.png)

