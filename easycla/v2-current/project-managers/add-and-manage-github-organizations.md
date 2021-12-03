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

3\. Scroll down to the **Tools** **Status** section, and click **EasyCLA**.&#x20;

**Note:** You can also connect the GitHub organization during IT set up in the **IT Services Status** section, and then install EasyCLA application in **Tools Status** section to add it for CLA process.

4\. Under CLA Groups, select a CLA group to which you have added the project.

5\. Click **Manage** next to the project for which you want to manage repositories.

![Add and manage repositories](https://docs.linuxfoundation.org/\~/files/v0/b/gitbook-28427.appspot.com/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-MYL76gRXl7OC0uMczgL%2F-MYLD72mIvpAdv9fFlZ4%2Fadd%20and%20manage%20repositories.png?alt=media\&token=b160c7c6-058f-4ebf-bd9a-da5e9eb063e8)

6\. Under the GitHub tab, click the **+** sign at the top right of Add GitHub Organization.

![](https://docs.linuxfoundation.org/\~/files/v0/b/gitbook-28427.appspot.com/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-MFZGPu75-Bd7bqLBOnN%2F-MFZKZTNWbP2aVmjKu-V%2Fadd%20github%20organization.png?alt=media\&token=643551cd-1f7a-4034-9a5f-ab49da45970f)

7\. Type the GitHub organization name in the **Enter GitHub Organization** field, and click **Connect**.

![Install GitHub EasyCLA App](https://docs.linuxfoundation.org/\~/files/v0/b/gitbook-28427.appspot.com/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-MFZGPu75-Bd7bqLBOnN%2F-MFZPgq31tgztNKDBrbs%2Fconnect%20github%20organization.png?alt=media\&token=612e6ed4-236b-41ad-b46d-a5dce5ed9865)

8\. Click **Install GitHub EasyCLA App**.

![Install GitHub EasyCLA App](<../../../.gitbook/assets/install github easycla app.png>)

9\. Sign in to GitHub if the sign-in window appears, and click **Configure**.

![](https://docs.linuxfoundation.org/\~/files/v0/b/gitbook-28427.appspot.com/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-MFdLZv2xp3YKCFgNzQt%2F-MFdeKsL7EejOGnpsXFy%2Fconfigure%20cla%20for%20github%20organization.png?alt=media\&token=bfcb45f1-428f-4f21-abe0-7190fe5931bf)

10\. Select the organization that you want to enroll for CLA mechanism.![](https://docs.linuxfoundation.org/\~/files/v0/b/gitbook-28427.appspot.com/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-MFdLZv2xp3YKCFgNzQt%2F-MFdfNRIFgOtnmiH0fqV%2Fselect%20github%20organization.png?alt=media\&token=a18596c4-e8e2-4440-8fd0-e47e0e70a2ab)

​11. Select repositories, and click **Install**.

{% hint style="info" %}
#### Note: <a href="#note" id="note"></a>

If you select **Only select repositorie**s, then a newly added repository to the GitHub organization will not be reflected automatically under the project's GitHub organization page in Project Console.​​
{% endhint %}

![](https://docs.linuxfoundation.org/\~/files/v0/b/gitbook-28427.appspot.com/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-MUDfSFN0KdrdvVYTWRf%2F-MUDqSzSMRg7EyK1B1bO%2Fselecting%20individual%20repositories.png?alt=media\&token=310de0dd-f58f-4c2c-b8a2-237920b50286)

12\. Navigate to the Project Control Center, and click **I'm Done Installing**.

![Installation Completed](https://docs.linuxfoundation.org/\~/files/v0/b/gitbook-28427.appspot.com/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-MUN9fCoX3SgnGeAMrDC%2F-MUN9o8-V1nRC6N9kZT5%2Finstallation%20completed.png?alt=media\&token=4b860125-af3a-4527-87e1-d54ee22f3c28)

{% hint style="warning" %}
**Important:** To enable a CLA mechanism on a repository, you must [enforce CLA mechanism for GitHub repositories](enforce-or-remove-cla-mechanism.md#enforce-or-remove-cla-mechanism-from-github-repositories). Simply adding a GitHub organization to the project does not enable the EasyCLA mechanism for any CLA groups.
{% endhint %}

## Enable Branch Protection and Auto Enable New Repositories <a href="#enable-branch-protection-and-auto-enable-new-repositories" id="enable-branch-protection-and-auto-enable-new-repositories"></a>

After adding the GitHub organization, you should enable branch protection and auto enable new repositories.

* **Enable Branch Protection** automatically enables the EasyCLA check for all the branches of the GitHub organization. If you select this check box, you do not need to [enable branch protection manually](../getting-started/easycla-troubleshooting/easycla-disabled.md#enable-branch-protection).
* **Auto Enable New Repositories** automatically adds a repository under the GitHub organization on the project console when you add the repository to the GitHub organization.

1\. Click the settings icon![](https://docs.linuxfoundation.org/\~/files/v0/b/gitbook-28427.appspot.com/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-MCM1hprE1R74hXHjdUe%2F-MCM2JfE9dPjlsLUyjJG%2Fsettings.png?alt=media\&token=63615e57-2bea-4fb8-b371-627314ea5611)next to **Additional Settings** for a GitHub organization.

2\. Click both the check boxes, and click **Save Changes**.

![Additional Settings](https://docs.linuxfoundation.org/\~/files/v0/b/gitbook-28427.appspot.com/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-MYL76gRXl7OC0uMczgL%2F-MYLEadh9tUu-8W00\_mk%2Fadditional%20setttings.png?alt=media\&token=9d67e276-b5cb-464e-9c43-54af26b36944)

## Disassociate GitHub Organization <a href="#disassociate-github-organization" id="disassociate-github-organization"></a>

1\. Click the settings icon![](https://docs.linuxfoundation.org/\~/files/v0/b/gitbook-28427.appspot.com/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-MCM1hprE1R74hXHjdUe%2F-MCM2JfE9dPjlsLUyjJG%2Fsettings.png?alt=media\&token=63615e57-2bea-4fb8-b371-627314ea5611)next to **Additional Settings** for a GitHub organization.

2\. Click **Disassociate GitHub Org**, and click the link to create a support ticket to disassociate the GitHub org.

![Additional Settings - Disassociate GitHub Organization](https://docs.linuxfoundation.org/\~/files/v0/b/gitbook-28427.appspot.com/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-MYL76gRXl7OC0uMczgL%2F-MYLEadh9tUu-8W00\_mk%2Fadditional%20setttings.png?alt=media\&token=9d67e276-b5cb-464e-9c43-54af26b36944)
