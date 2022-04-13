# EasyCLA Disabled

#### Problem: <a href="#problem" id="problem"></a>

EasyCLA was previously enabled for a GitHub repository, but someone other than the project manager has subsequently disabled it.

#### Solution: <a href="#solution" id="solution"></a>

### Enable Branch Protection <a href="#enable-branch-protection" id="enable-branch-protection"></a>

GitHub is set up to permit administrators and organization owners to have maximum flexibility, which includes disabling installed applications, such as EasyCLA. To avoid this, you must enable branch protection by [selecting the Enable Branch Protection check box](https://app.gitbook.com/s/-M2DCN9UgoRgMEkgnLyP-3789850253/easycla/getting-started/easycla-troubleshooting/easycla-is-disabled) after the GitHub organization is added to a project.

You can also add the branch protection rule manually, as described below:

1\. As the GitHub organization owner or administrator, go to the GitHub repository that you want EasyCLA to monitor.

2\. Click Settings from the top menu.

![CLA GitHub Repository Settings](../../../../.gitbook/assets/cla-github-repository-settings.png)

3\. Settings appear with Options in the left pane.

4\. Click Branches under Options.

![](../../../../.gitbook/assets/cla-github-options.png)

5\. Select master for the Default branch. Click Edit or Add rule for Branch protection rules of your organization.

![CLA GitHub branch Add Rule](../../../../.gitbook/assets/cla-github-branch-add-rule.png)

6\. Select the following check boxes under **Rule settings**, and click **Create**:

* Require status checks to pass before merging
* Require branches to be up to date before merging
* Include administrators

![CLA GitHub Branch Protection Rule](https://files.gitbook.com/v0/b/gitbook-legacy-files/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-M6c\_lpbFL3c2MHPwbCU%2F-M6cg5mNvgw-UP7bSFBI%2Fcla-github-branch-protection-rule.png?alt=media\&token=e317954c-42af-4bad-8be5-6db07e256e6e)
