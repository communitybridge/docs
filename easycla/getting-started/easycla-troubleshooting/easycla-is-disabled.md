# EasyCLA is Disabled

EasyCLA was previously enabled for a GitHub repository, but someone other than the project manager has subsequently disabled it.

**Solution:**

## **Enable Branch Protection**

GitHub is set up to permit administrators and organization owners to have maximum flexibility, which includes disabling installed applications, such as EasyCLA. To avoid this, you must enable branch protection by [selecting the **Enable Branch Protection** check box](../../project-managers/add-and-manage-git-organizations-and-repositories/#enable-branch-protection-and-auto-enable-new-repositories) after the GitHub organization is added to a project.

You can also add the branch protection rule manually, as described below:

1. As the GitHub organization owner or administrator, go to the GitHub repository that you want EasyCLA to monitor.
2. Click **Settings** from the top menu.

![CLA GitHub Repository Settings](../../../.gitbook/assets/cla-github-repository-settings.png)

1. Settings appear with Options in the left pane.
2. Click **Branches** under Options.

![CLA GitHub Options](../../../.gitbook/assets/cla-github-options.png)

**Result:** Branch settings appears.

1. Select **master** for the Default branch. Click **Edit** or **Add rule** for Branch protection rules of your organization.

![CLA GitHub branch Add Rule](../../../.gitbook/assets/cla-github-branch-add-rule.png)

**Result:** Branch protection rule setting appears.

1. Select the following check boxes in Rule settings and click **Create**.
2. Require status checks to pass before merging
3. Require branches to be up to date before merging
4. Include administrators

![CLA GitHub Branch Protection Rule](../../../.gitbook/assets/cla-github-branch-protection-rule.png)

