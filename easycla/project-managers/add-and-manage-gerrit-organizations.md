# Add and Manage Gerrit Organizations

Before you can add or manage Gerrit organizations and repositories, you must connect or add Gerrit organizations while setting up IT services. However, you can also add Gerrit organization in the Gerrit pane of **Tools** tab.

* [Add Gerrit Organization](add-and-manage-gerrit-organizations.md#add-gerrit-organization)
* [Disassociate Gerrit Organization](add-and-manage-gerrit-organizations.md#disassociate-gerrit-organization)

After you successfully add Git organizations, you can:

* [View Connection Status of Git Organization and Repositories](view-connection-status-of-git-organizations-and-repositories.md)
* [Enforce or Remove CLA Mechanism for Gerrit Repositories](enforce-or-remove-cla-mechanism.md#enforce-cla-mechanism-for-gerrit-repositories)

## Add Gerrit Organization

{% hint style="info" %}
**Note:**

* If you have already added a Gerrit instance during the EasyCLA on-boarding process, skip this procedure unless you want to add more Gerrit instances.
* After you add a Gerrit organization, all of its repositories are EasyCLA-enabled by default.
{% endhint %}

1. Click the **+** sign at the top right of Add Gerrit Organization.

![Add Gerrit Organization](../../.gitbook/assets/add-gerrit-organization.png)

2. Complete the form fields, and click **Connect**.  
**Gerrit Instance Name** - Name of the Gerrit Instance  
**Gerrit Instance URL** - URL of the Gerrit Instance  
**ICLA Group ID** - An existing LDAP Group ID for Individual CLAs  
**CCLA Group ID** - An existing LDAP Group ID for Corporate CLAs

{% hint style="info" %}
**Notes:**

* Contact the Linux Foundation IT team to get Gerrit Instance Name and URL.
* Contact the Linux Foundation IT team if you do not know the LDAP Group IDs.
* One or both LDAP groups must exist for you to be able to create a Gerrit instance. If a group does not exist, an error message appears and you are prevented from creating a Gerrit instance.
{% endhint %}

The EasyCLA project console lists the CLA-enabled instances, as shown below.​​  
**Note:** You cannot disable the CLA check for individual Gerrit repositories.

![Gerrit Instances](../../.gitbook/assets/gerrit-instances.png)

## Disassociate Gerrit Organization

1. Click **Disassociate Gerrit** next to a Gerrit Instance, and click **Yes, Disconnect** on the confirmation page.

![Disassociate Gerrit](../../.gitbook/assets/disassociate-gerrit-organization.png)

