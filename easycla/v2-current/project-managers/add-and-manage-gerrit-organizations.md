# Add and Manage Gerrit Organizations

Before you can add or manage Gerrit organizations and repositories, you must connect or add Gerrit organizations while setting up IT services. However, you can also add Gerrit organization in the Gerrit pane of **Tools** tab.

* ​[Add Gerrit Organization​](add-and-manage-gerrit-organizations.md#add-gerrit-organization)
* ​[Disassociate Gerrit Organization​](add-and-manage-gerrit-organizations.md#disassociate-gerrit-organization)

After you successfully add Git organizations, you can:

* ​[View Connection Status of Git Organization and Repositories​](view-connection-status-of-git-organizations-and-repositories.md)
* ​[Enforce or Remove CLA Mechanism for Gerrit Repositories​](enforce-or-remove-cla-mechanism.md#enforce-cla-mechanism-for-gerrit-repositories)

## Add Gerrit Organization <a href="#add-gerrit-organization" id="add-gerrit-organization"></a>

{% hint style="info" %}
**Note:**

* If you have already added a Gerrit instance during the EasyCLA on-boarding process, skip this procedure unless you want to add more Gerrit instances.
* After you add a Gerrit organization, all of its repositories are EasyCLA-enabled by default.
{% endhint %}

1\. Click the **+** sign at the top right of Add Gerrit Organization.

![Add Gerrit Organization](https://docs.linuxfoundation.org/\~/files/v0/b/gitbook-28427.appspot.com/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-MUCVklTQZW8sJpK2HLG%2F-MUDZj7HiVsJRLs2mGs3%2Fadd%20gerrit%20organization.png?alt=media\&token=ace2a9b7-cdf9-49a7-a0ea-dd44783827f6)

2\. Complete the form fields, and click **Connect**.&#x20;

> **Gerrit Instance Name** - Name of the Gerrit Instance
>
> **Gerrit Instance URL** - URL of the Gerrit Instance
>
> **ICLA Group ID** - An existing LDAP Group ID for Individual CLAs
>
> **CCLA Group ID** - An existing LDAP Group ID for Corporate CLAs

{% hint style="info" %}
**Notes:**

* Contact the Linux Foundation IT team to get Gerrit Instance Name and URL.
* Contact the Linux Foundation IT team if you do not know the LDAP Group IDs.
* One or both LDAP groups must exist for you to be able to create a Gerrit instance. If a group does not exist, an error message appears and you are prevented from creating a Gerrit instance.
{% endhint %}

The EasyCLA project console lists the CLA-enabled instances, as shown below.​​&#x20;

**Note:** You cannot disable the CLA check for individual Gerrit repositories.

![Gerrit Instances](https://docs.linuxfoundation.org/\~/files/v0/b/gitbook-28427.appspot.com/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-MHLgxt0yyY5C8JVm7Sh%2F-MHLi3TkO\_YVgD5b4YJ9%2Fgerrit%20instances.png?alt=media\&token=94d94daa-c824-407f-b604-3ca336b28aa2)

## Disassociate Gerrit Organization <a href="#disassociate-gerrit-organization" id="disassociate-gerrit-organization"></a>

1\. Click **Disassociate Gerrit** next to a Gerrit Instance, and click **Yes, Disconnect** on the confirmation page.

![Disassociate Gerrit](https://docs.linuxfoundation.org/\~/files/v0/b/gitbook-28427.appspot.com/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-MGgGDh5YsW-7vaCluVV%2F-MGgzMKnb6nZs2XU0zOh%2Fdisassociate%20gerrit%20organization.png?alt=media\&token=d7abd234-c704-4809-bc98-7a3c40cca775)
