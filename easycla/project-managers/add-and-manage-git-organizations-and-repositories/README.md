# Add and Manage Git Organizations and Repositories

Before you can add or manage git repositories, you must connect/add Git organizations while setting up IT services. However, you can also add GitHub organization in the GitHub pane and add Gerrit instance in the Gerrit pane of **Tools** tab.

* [Add GitHub Organization](./#add-github-organization)
* [Disassociate GitHub Organization](./#disassociate-github-organization)
* [Add Gerrit Organization](./#add-gerrit-organization)
* [Disassociate Gerrit Organization](./#disassociate-gerrit-organization)

After you successfully add Git organizations, you can:

* [View Connection Status of Git Organization and Repositories](view-connection-status-of-git-organizations-and-repositories.md)
* [Enforce or Remove CLA Monitoring for Repositories](enforce-or-remove-cla-monitoring.md)

### Add GitHub Organization:

1. [Sign in](../sign-in-to-project-control-center.md).

2.Click a **project** of interest.

3. Navigate to **Tools** tab, and click **CLA**.  
**Note:** You can also connect the GitHub organization during IT set up in the **IT Services** tab, and then install EasyCLA application in **Tools** tab to add it for CLA monitoring.

![](../../../.gitbook/assets/tools-tab.png)

4. Under CLA Groups, select a CLA group to which you have added the project.

5. Click **Manage** next to the project for which you want to manage repositories.

![Add and Manage Repositories](../../../.gitbook/assets/add-and-manage-repositories.png)

6. Under GitHub tab, click the **+** sign at the top right of Add GitHub Organization.

![](../../../.gitbook/assets/add-github-organization.png)

7. Type GitHub organization name in the **Enter GitHub Organization** field, and click **Connect**.

![](../../../.gitbook/assets/connect-github-organization.png)

![Install GitHub EasyCLA App](../../../.gitbook/assets/install-github-easycla-app.png)

8. Click **Install GitHub EasyCLA App**.

9. Sign in to GitHub if sign in window appears, and click **Install**.

![](../../../.gitbook/assets/configure-cla-for-github-organization.png)

10. Select the organization that you want to enroll for CLA monitoring.  
 ![](../../../.gitbook/assets/select-github-organization.png)

11. Select repositories, and click **Install**.

{% hint style="info" %}
**Note**: If you select **Only select repositories**, then a newly added repository to the github organization will not be reflected automatically under the project's github organization page in Project Console.

![](../../../.gitbook/assets/selecting-individual-repositories.png)
{% endhint %}

12. A confirmation window appears informing you that the GitHub organization is connected for CLA monitoring.

{% hint style="warning" %}
**Important:** To enable a CLA check on a repository, you must [enforce CLA monitoring](enforce-or-remove-cla-monitoring.md#enforce-or-remove-cla-monitoring-from-github-repositories) for GitHub repositories or [add a Gerrit instance](./#add-gerrit-organization) for gerrit repositories. Simply adding an GitHub organization to the project does not enable the CLA check for any CLA groups.
{% endhint %}

### Disassociate GitHub Organization:

1. Click the settings icon ![](../../../.gitbook/assets/settings%20%281%29.png) next to **Additional Settings** for a GitHub organization.

2. Click **Disassociate GitHub Org**, and click the link to create a support ticket to disassociate the GitHub org.

![Disassociate GitHub Organization](../../../.gitbook/assets/disassociate-github-orgnanization.png)

### Add Gerrit Organization:

{% hint style="info" %}
**Note:** If you have already added a Gerrit instance during the CLA on-boarding process, skip this procedure unless you want to add more Gerrit instances.
{% endhint %}

 1. Click the **+** sign at the top right of Add Gerrit Organization.

![Add Gerrit Organization](../../../.gitbook/assets/add-gerrit-organization.png)

2. Complete the form fields, and click **Connect**.  
**Gerrit Instance Name** - Name of the Gerrit Instance  
**Gerrit Instance URL** - URL of the Gerrit Instance  
**ICLA Group ID** - An existing LDAP Group ID for Individual CLAs  
**CCLA Group ID** - An existing LDAP Group ID for Corporate CLAs

{% hint style="info" %}
**Notes:**

* Contact the IT team of Linux Foundation to get Gerrit Instance Name and URL.
* Contact the Linux Foundation IT team if you do not know the LDAP Group IDs.
* One or both LDAP groups must exist for you to be able to create a Gerrit instance. If a group does not exist, an error message appears and you are prevented from creating a Gerrit instance.
{% endhint %}

The CLA Project Console lists the CLA-enabled instances, as shown below.​​  
**Note:** You cannot disable CLA check for individual gerrit repositories.

![Gerrit Instances](../../../.gitbook/assets/gerrit-instances.png)

### Disassociate Gerrit Organization:

1. Click **Disassociate Gerrit** next to a Gerrit Instance, and click **Yes, Disconnect** on the confirmation page.

![Disassociate Gerrit](../../../.gitbook/assets/disassociate-gerrit-organization.png)



