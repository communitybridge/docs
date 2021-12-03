# Add and Manage GitLab Groups

Before you can add or manage GitLab groups and projects, you must connect or add GitLab groups while setting up IT services. However, you can also add GitLab groups in the GitLab pane of **Tools** tab.

{% hint style="info" %}
**Note**:

* In GitLab, _organizations_ are mentioned as _groups_, and _repositories_ are mentioned as _projects_.
* You must be the owner of the GitLab group which you want to connect for CLA mechanism.
{% endhint %}

* ​[Add GitLab Groups](add-and-manage-gitlab-groups.md#add-gitlab-groups)​
* ​[Enable Branch Protection and Auto Enable New Repositories](add-and-manage-gitlab-groups.md#enable-branch-protection-and-auto-enable-new-repositories)​
* ​D[isassociate GitLab Groups](add-and-manage-gitlab-groups.md#disassociate-gitlab-groups)​

After you successfully add Git organizations, you can:

* [​View Connection Status of Git Organization and Repositories](view-connection-status-of-git-organizations-and-repositories.md)​
* ​[Enforce or Remove CLA Mechanism from GitLab Projects​](enforce-or-remove-cla-mechanism.md#enforce-or-remove-cla-mechanism-from-gitlab-projects)

## Add GitLab Groups <a href="#add-gitlab-groups" id="add-gitlab-groups"></a>

1\. Sign in to the [Project Control Center](https://projectadmin.lfx.linuxfoundation.org).

2\. Click a **project** of interest.

3\. Scroll down to the **Tools** **Status** section, and click **EasyCLA**.

**Note:** You can also connect the GitLab groups during IT setup in the IT Services Status section, and then install the EasyCLA application in the Tools Status section to add it for the CLA process.

4\. Under CLA Groups, select a CLA group to which you have added the project.

5\. Click **Manage** next to the project for which you want to manage repositories.

![Add and manage repositories](https://docs.linuxfoundation.org/\~/files/v0/b/gitbook-28427.appspot.com/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-MYL76gRXl7OC0uMczgL%2F-MYLD72mIvpAdv9fFlZ4%2Fadd%20and%20manage%20repositories.png?alt=media\&token=b160c7c6-058f-4ebf-bd9a-da5e9eb063e8)

6\. Under the GITLAB tab, click the **+** sign at the top right of ADD GITLAB GROUP.

![Add GitLab Group](https://docs.linuxfoundation.org/\~/files/v0/b/gitbook-28427.appspot.com/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-MiPaFEZaMNq3VIuBRMe%2F-MiPcqDDRfIYvatzDsaY%2Fadd%20gitlab%20group.png?alt=media\&token=34afeee7-1a2d-4e8d-96c9-a9573c56c857)

7\. Provide the complete URL of the GitLab group, as shown in the image, in the **Enter GitLab Group URL** field, and click **Connect**.

![Connect GitLab Group](https://docs.linuxfoundation.org/\~/files/v0/b/gitbook-28427.appspot.com/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-MiPaFEZaMNq3VIuBRMe%2F-MiPdsW4DbRxTg7b1Rb5%2Fconnect%20gitlab%20group.png?alt=media\&token=e73ee2e2-1b4b-40e7-bc79-83c5e6710e89)

8\. Click **Install GitLab EasyCLA App**.

![Install GitLab EasyCLA Application](https://docs.linuxfoundation.org/\~/files/v0/b/gitbook-28427.appspot.com/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-MiPaFEZaMNq3VIuBRMe%2F-MiPg2EpWrcICW6p6vSm%2Finstall%20gitlab%20easycla%20app.png?alt=media\&token=50adf813-c24a-4c2f-9cc4-bc539712f1b6)

&#x20;9\. Click **Authorize**.

10\. Installation Successful window appears. Close the window, navigate to the Project Control Center, and click **I'm Done Installing**.

**Note:** If you do not click **I'm Done Installing**, you will have to reinstall EasyCLA application.

![GitLab I am Done Installing](https://docs.linuxfoundation.org/\~/files/v0/b/gitbook-28427.appspot.com/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-MiPaFEZaMNq3VIuBRMe%2F-MiPi8H7IPV1A4ngjBSv%2Fgitlab%20i%20am%20done%20installing.png?alt=media\&token=0e55a66f-2716-40ca-ad4a-f70e323023ef)

![](https://docs.linuxfoundation.org/\~/files/v0/b/gitbook-28427.appspot.com/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-MiPaFEZaMNq3VIuBRMe%2F-MiPh7h0GBui2s6oC59b%2Fgitlab%20installation%20successful.png?alt=media\&token=20545bbb-668f-4751-8d46-5a7a858158da)

{% hint style="info" %}
**Note:**

1.LFX EasyCLA adds all the projects, including projects under subgroups, of the GitLab group to the Project Control Center.

2.To enable a CLA mechanism on a project, you must [enforce CLA mechanism](enforce-or-remove-cla-mechanism.md#enforce-or-remove-cla-mechanism-from-gitlab-projects) for GitLab projects. Simply adding a GitLab group to the project does not enable the EasyCLA mechanism for any GitLab project.

3.To review the configuration or revoke the application, navigate to the _GitLab Applications under your User Settings_.
{% endhint %}

## Enable Branch Protection and Auto Enable New Repositories <a href="#enable-branch-protection-and-auto-enable-new-repositories" id="enable-branch-protection-and-auto-enable-new-repositories"></a>

After adding the GitLab group, you should enable branch protection and auto enable new repositories.

* **Enable Branch Protection** automatically enables the EasyCLA check for all the branches of the GitLab group. If you select this check box, you do not need to [enable branch protection manually](../getting-started/easycla-troubleshooting/easycla-disabled.md#enable-branch-protection).
* **Auto Enable New Repositories** automatically adds a repository under the GitLab group on the project console when you add a project to the GitLab group.

**To enable branch protection and auto enable new repositories:**

1\. Click the settings icon![](https://docs.linuxfoundation.org/\~/files/v0/b/gitbook-28427.appspot.com/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-MCM1hprE1R74hXHjdUe%2F-MCM2JfE9dPjlsLUyjJG%2Fsettings.png?alt=media\&token=63615e57-2bea-4fb8-b371-627314ea5611)next to **Additional Settings** for a GitLab group.

2\. Click both the check boxes, and click **Save Changes**.

![Additional Settings GitLab](https://docs.linuxfoundation.org/\~/files/v0/b/gitbook-28427.appspot.com/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-MitRJvK43ovpq45P2Tx%2F-MitZdX8TRK\_724q9gMF%2Fadditional%20setttings%20GitLab.png?alt=media\&token=56a0169f-4d46-43cf-bc01-c5d6fe07f5b2)

## Disassociate GitLab Groups <a href="#disassociate-gitlab-groups" id="disassociate-gitlab-groups"></a>

**Note**: To disassociate a GitLab group, you must disable CLA from all projects of the GitLab group.

![Disassociate GitLab Group disabled for CLA enforced Projects](https://docs.linuxfoundation.org/\~/files/v0/b/gitbook-28427.appspot.com/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-MlEWgNXplb\_p5b-Msjx%2F-MlEm0yjikCAqyhShrV3%2Fdisassociate%20gitlab%20group%20disabled.png?alt=media\&token=c5a359a4-73f3-40cf-bb15-55169ba89da0)



1. Click the settings icon![](https://docs.linuxfoundation.org/\~/files/v0/b/gitbook-28427.appspot.com/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-MCM1hprE1R74hXHjdUe%2F-MCM2JfE9dPjlsLUyjJG%2Fsettings.png?alt=media\&token=63615e57-2bea-4fb8-b371-627314ea5611)next to **Additional Settings** for a GitLab group.
2. Click **Disassociate GitLab Group**, and click **Disassociate** on the confirmation window.

![Disassociate GitLab Group](https://docs.linuxfoundation.org/\~/files/v0/b/gitbook-28427.appspot.com/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-MlEWgNXplb\_p5b-Msjx%2F-MlEmJKzhdUeO\_X4yUpz%2Fdisassociate%20gitlab%20group.png?alt=media\&token=c7f328d1-42a0-4cd0-bb6e-0433f45c67fc)
