# Add and Manage Git Organizations and Repositories

Before you can add or manage git repositories, you must connect/add Git organizations while setting up IT services, as described in **PROVIDE LINK TO ADMIN DASHBOARD**. However, you can also add GitHub organization in the GitHub pane and add Gerrit instance in the Gerrit pane of **Product Services** tab.

* [Add GitHub Organization](./#to-add-github-organization)
* [Disassociate GitHub Organization](./#to-disassociate-github-organization)
* [Add Gerrit Organization](./#to-add-gerrit-organization)
* [Disassociate Gerrit Organization](./#to-disassociate-gerrit-organization)

After you successfully add/connect Git organizations, you can:

* [View Connection Status of Git Organization and Repositories](view-connection-status-of-git-organizations-and-repositories.md)
* [Add or Remove GitHub repositories](add-or-remove-git-repositories-for-cla-monitoring.md)
* [Add or Remove Gerrit Instances](add-or-remove-gerrit-instances-from-cla-monitoring.md)

### Add GitHub Organization:

1. [Sign in](../sign-in-to-project-console.md).

2.Click a **project** of interest.  
The project page appears.

3. Navigate to **Product Services** tab, and click **CLA**.  
You can also connect the GitHub organization during IT set up in the **IT Services** tab, and then install EasyCLA application in **Product Services** tab to add it for CLA monitoring.

![](../../../../.gitbook/assets/cla-product-services.png)

3. Under a CLA group, click **Add/Manage Repos for a project.**  
Source Control configuration page appears.

![Add and Manage Repositories](../../../../.gitbook/assets/add-manage-repositories.png)

4. Under GitHub tab, click the **+** sign at the top right of Add GitHub Organization.

![](../../../../.gitbook/assets/add-github-organization.png)

5. Type GitHub organization name in the **Enter GitHub Organization** field, and click **Connect**.

![](../../../../.gitbook/assets/connect-github-organization.png)

6. Click **Install GitHub EasyCLA App**.

![Install GitHub EasyCLA App](../../../../.gitbook/assets/install-github-easycla-app.png)

7. Sign in to GitHub if sign in window appears, and click **Configure**.

![](../../../../.gitbook/assets/configure-cla-for-github-organization.png)

8. Select the organization that you want to enroll for CLA monitoring.

![Select GitHub Organization](../../../../.gitbook/assets/select-github-organization.png)

9. A confirmation window appears informing you that the GitHub organization is connected for CLA monitoring.

### Disassociate GitHub Organization:

1. Click the settings icon ![](../../../../.gitbook/assets/settings%20%281%29.png) next to **Additional Settings** for a GitHub organization.

2. Click **Disassociate GitHub Org**, and click **Yes, Disconnect** on the confirmation page.

![Disassociate GitHub Organization](../../../../.gitbook/assets/disassociate-github-organization.png)

### Add Gerrit Organization:

 1. Click the **+** sign at the top right of Add Gerrit Organization.

2. Provide details, such as Gerrit instance name, URL, ICLA and CCLA group ids in the respective fields.

3. Click **Connect**.

![](../../../../.gitbook/assets/add-gerrit-organization.png)

### Disassociate Gerrit Organization:

1. Click the settings icon ![](../../../../.gitbook/assets/settings%20%281%29.png) next to **Additional Settings** for a Gerrit Instance.

2. Click **Disassociate Gerrit**, and click **Yes, Disconnect** on the confirmation page.

![](../../../../.gitbook/assets/disassociate-gerrit-organization.png)



