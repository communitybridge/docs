# Add and Manage GitHub Organizations

Before you can add or manage GitHub organizations and repositories, you must connect or add GitHub organizations while setting up IT services. However, you can also add GitHub organization in the GitHub pane of **Tools** tab.

* [Add GitHub Organization](add-and-manage-github-organizations.md#add-github-organization)
* [Enable Branch Protection and Auto Enable New Repositories](add-and-manage-github-organizations.md#enable-branch-protection-and-auto-enable-new-repositories)
* [Disassociate GitHub Organization](add-and-manage-github-organizations.md#disassociate-github-organization)

After you successfully add GitHub organization, you can:

* [View Connection Status of Git Organization and Repositories](view-connection-status-of-git-organizations-and-repositories.md)
* [Enforce or Remove CLA Mechanism from GitHub Repositories](enforce-or-remove-cla-mechanism.md#enforce-or-remove-cla-mechanism-from-github-repositories)

## Add GitHub Organization

{% hint style="info" %}
**Note:** You must be the owner of the GitHub organization which you want to connect for CLA mechanism.
{% endhint %}

1. Sign in to the [Project Control Center](https://projectadmin.lfx.linuxfoundation.org/).

2. Click a **project** of interest.

3. Scroll down to the **Tools** **Status** section, and click **EasyCLA**.  
**Note:** You can also connect the GitHub organization during IT set up in the **IT Services Status** section, and then install EasyCLA application in **Tools Status** section to add it for CLA process.

4. Under CLA Groups, select a CLA group to which you have added the project.

5. Click **Manage** next to the project for which you want to manage repositories.

![Add and manage repositories](../../.gitbook/assets/add-and-manage-repositories.png)

6. Under the GitHub tab, click the **+** sign at the top right of Add GitHub Organization.

![](../../.gitbook/assets/add-github-organization.png)

7. Type the GitHub organization name in the **Enter GitHub Organization** field, and click **Connect**.

![](../../.gitbook/assets/connect-github-organization.png)

![Install GitHub EasyCLA App](../../.gitbook/assets/install-github-easycla-app.png)

8. Click **Install GitHub EasyCLA App**.

9. Sign in to GitHub if the sign-in window appears, and click **Configure**.

![](../../.gitbook/assets/configure-cla-for-github-organization.png)

10. Select the organization that you want to enroll for CLA mechanism.  
![](../../.gitbook/assets/select-github-organization.png)

11. Select repositories, and click **Install**.

{% hint style="info" %}
#### Note:

If you select **Only select repositories**, then a newly added repository to the GitHub organization will not be reflected automatically under the project's GitHub organization page in Project Console.

![](../../.gitbook/assets/selecting-individual-repositories.png)
{% endhint %}

12. Navigate to the Project Control Center, and click **I'm Done Installing**.

![Installation Completed](../../.gitbook/assets/installation-completed.png)

{% hint style="warning" %}
**Important:** To enable a CLA mechanism on a repository, you must [enforce CLA mechanism](enforce-or-remove-cla-mechanism.md) for GitHub repositories. Simply adding a GitHub organization to the project does not enable the EasyCLA mechanism for any CLA groups.
{% endhint %}

## Enable Branch Protection and Auto Enable New Repositories

After adding the GitHub organization, you should enable branch protection and auto enable new repositories. 

* **Enable Branch Protection** automatically enables the EasyCLA check for all the branches of the GitHub organization. If you select this check box, you do not need to [enable branch protection manually](../getting-started/easycla-troubleshooting/easycla-is-disabled.md#enable-branch-protection).
* **Auto Enable New Repositories** automatically adds a repository under the GitHub organization on the project console when you add the repository to the GitHub organization.

1. Click the settings icon ![](../../.gitbook/assets/settings%20%281%29.png) next to **Additional Settings** for a GitHub organization.

2. Click both the check boxes, and click **Save Changes**.

![Additional Settings](../../.gitbook/assets/additional-setttings.png)

## Disassociate GitHub Organization

1. Click the settings icon ![](../../.gitbook/assets/settings%20%281%29.png) next to **Additional Settings** for a GitHub organization.
2. Click **Disassociate GitHub Org**, and click the link to create a support ticket to disassociate the GitHub org.

![Additional Settings - Disassociate GitHub Organization](../../.gitbook/assets/additional-setttings.png)
