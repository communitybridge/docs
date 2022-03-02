# Add and Manage GitHub Organizations

Before you can add or manage GitHub organizations and repositories, you must connect or add GitHub organizations while setting up IT services. However, you can also add GitHub organization in the GitHub pane of **Tools** tab.

* ​[Add GitHub Organization](add-and-manage-github-organizations.md#add-github-organization)​
* ​[Enable Branch Protection and Auto Enable New Repositories](add-and-manage-github-organizations.md#enable-branch-protection-and-auto-enable-new-repositories)​
* ​[Disassociate GitHub Organization​](add-and-manage-github-organizations.md#disassociate-github-organization)

After you successfully add GitHub organization, you can:

* ​[View Connection Status of Git Organization and Repositories](view-connection-status-of-git-organizations-and-repositories.md)​
* ​[Enforce or Remove CLA Mechanism from GitHub Repositories](enforce-or-remove-cla-mechanism.md#enforce-or-remove-cla-mechanism-from-github-repositories)​

## Add GitHub Organization <a href="#add-github-organization" id="add-github-organization"></a>

{% hint style="info" %}
**Prerequisite:** You must be the owner of the GitHub organization which you want to connect for CLA mechanism.
{% endhint %}

1\. Sign in to the [Project Control Center](https://projectadmin.lfx.linuxfoundation.org).

2\. Click a **project** of interest.

3\. Scroll down to the **Tools** **Status** section, and click **EasyCLA**.

**Note:** You can also connect the GitHub organization during IT set up in the **IT Services Status** section, and then install EasyCLA application in **Tools Status** section to add it for CLA process.

4\. Under CLA Groups, select a CLA group to which you have added the project.

5\. Click **Manage** next to the project for which you want to manage repositories.

![Add and Manage Repositories](<../../../.gitbook/assets/add and manage repositories.png>)

6\. Under the GitHub tab, click the **+** sign at the top right of Add GitHub Organization.

![Add GitHub Organization](<../../../.gitbook/assets/add github organization.png>)

7\. Type the GitHub organization name in the **Enter GitHub Organization** field, and click **Connect**.

![Connect GitHub Organization](<../../../.gitbook/assets/connect github organization.png>)

8\. Click **Install GitHub EasyCLA App**.

![Install GitHub EasyCLA App](<../../../.gitbook/assets/install github easycla app.png>)

9\. Sign in to GitHub if the sign-in window appears, and click **Configure**.

10\. Select the organization that you want to enroll for CLA mechanism.

​11. Select repositories, and click **Install**.

{% hint style="info" %}
**Note:**

If you select **Only select repositorie**s, then a newly added repository to the GitHub organization will not be reflected automatically under the project's GitHub organization page in Project Console.​​
{% endhint %}

12\. Navigate to the Project Control Center, and click **I'm Done Installing**.

{% hint style="warning" %}
**Important:** To enable a CLA mechanism on a repository, you must [enforce CLA mechanism for GitHub repositories](enforce-or-remove-cla-mechanism.md#enforce-or-remove-cla-mechanism-from-github-repositories). Simply adding a GitHub organization to the project does not enable the EasyCLA mechanism for any CLA groups.
{% endhint %}

![GitHub Installation Completed](<../../../.gitbook/assets/github installation completed.png>)

## Enable Branch Protection and Auto Enable New Repositories <a href="#enable-branch-protection-and-auto-enable-new-repositories" id="enable-branch-protection-and-auto-enable-new-repositories"></a>

After adding the GitHub organization, you should enable branch protection and auto enable new repositories.

* **Enable Branch Protection** automatically enables the EasyCLA check for all the branches of the GitHub organization. If you select this check box, you do not need to [enable branch protection manually](../getting-started/easycla-troubleshooting/easycla-disabled.md#enable-branch-protection).
* **Auto Enable New Repositories** automatically adds a repository under the GitHub organization on the project console when you add the repository to the GitHub organization.

1\. Click the settings icon next to **Additional Settings** for a GitHub organization.

2\. Click both the check boxes, and click **Save Changes**.

![Additional Settings](<../../../.gitbook/assets/additional setttings.png>)

## Disassociate GitHub Organization <a href="#disassociate-github-organization" id="disassociate-github-organization"></a>

1\. Click the settings icon next to **Additional Settings** for a GitHub organization.

2\. Click **Disassociate GitHub Org**, and click the link to create a support ticket to disassociate the GitHub org.

![Additional Settings - Disassociate GitHub Organization](https://docs.linuxfoundation.org/\~/files/v0/b/gitbook-28427.appspot.com/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-MYL76gRXl7OC0uMczgL%2F-MYLEadh9tUu-8W00\_mk%2Fadditional%20setttings.png?alt=media\&token=9d67e276-b5cb-464e-9c43-54af26b36944)
