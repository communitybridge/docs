# View and Manage CLA Group Details

A Project Manager can view CLA group details and can update a CLA group details by updating or deleting a CLA group name, [updating a CLA template](update-template.md), and [invalidating a contributor's signature](invalidate-a-contributors-signature.md).

1. Sign in to the [Project Control Center](https://projectadmin.lfx.linuxfoundation.org).
2. Click a **project name** of interest.
3. Scroll down to **Tools Status** section, and click **EasyCLA**. The EasyCLA Overview page appears.

![Tools Status](https://files.gitbook.com/v0/b/gitbook-legacy-files/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-MYL76gRXl7OC0uMczgL%2F-MYL8B6xQwTBjV-bvxBl%2Ftools%20status%20tab.png?alt=media\&token=c1fee7b7-6cf2-4e79-8796-d311043d987e)

The Overview page displays CLA groups that have been added to the project, [details for each CLA group](view-and-manage-cla-group-details.md#cla-group-details), and [activity log](view-and-manage-cla-group-details.md#activity-log) table. A CLA group defines a CCLA and/or ICLA that contributors must sign.

![CLA Overview](https://files.gitbook.com/v0/b/gitbook-legacy-files/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-McSyoQ63waT5Zy3vINd%2F-MRdokxOKgWL83g31xcj%2Fcla%20overview.png?alt=media\&token=3047926e-e603-439b-991d-dcc2651a6e14)

### CLA Group Details: <a href="#cla-group-details" id="cla-group-details"></a>

1\. **Name** of the CLA group, and whether the CLA Group includes a CCLA and/or an ICLA with a tick mark beside each CLA type.

1. **Projects Covered** shows the number of projects that are covered under the CLA group.
2. **Repositories** shows the total number of repositories of the added projects that are enrolled for CLA monitoring. You must [enforce EasyCLA](enforce-or-remove-cla-mechanism.md) for one or more Git repositories for them to be counted.
3. **Signatures** shows the number of individuals who have signed CLA within that CLA group, and whose signature status is in active state. This includes both ICLA and/or CCLA based on the CLA group configuration.
4. Click![](https://files.gitbook.com/v0/gitbook-legacy-files/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-MMtuFseEUFUva2iGsvQ%2F-MMu0RrZNxmtvISo9j1B%2Fedit%20CTA.png?alt=media\&token=272b442e-ea97-42c8-be45-93d6c068fd99)to edit the title and description of the CLA group.
5. Click![](https://files.gitbook.com/v0/b/gitbook-legacy-files/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-M9WNn7lqBje4DX2Irn-%2F-M9Y5z1DnSglCZbaXzg0%2Fdelete%20icon.png?alt=media\&token=2333c400-d6bf-4c6e-93e9-52d4c00113d9)to create a support ticket requesting to delete the CLA group.

2\. Under the **PROJECTS** tab, expand the project group to view projects that are enrolled for the CLA group. Inactive selected check boxes indicate that the project has already been added to another CLA group. Click **Manage** to add and manage [GitHub](add-and-manage-github-organizations.md) or [Gerrit](add-and-manage-gerrit-organizations.md) or [GitLab](add-and-manage-gitlab-groups.md) groups and repositories.

3\. Navigate to **TEMPLATES** tab to view and download the ICLA and/or CCLA templates. You can [update the templates](update-template.md) incase the email address mentioned in the template is not correct or you want to change.

### Signatures: <a href="#signatures" id="signatures"></a>

Navigate to **SIGNATURES** tab to view signed ICLAs and CCLAs.

* **Signed ICLAs** lists details of individuals who have signed an ICLA, such as name, LF Login name (LF ID), GitHub ID, email address, status of their signature (Active, Disabled, Invalidated), and Invalidate CTA under Actions column (enabled only for Active statuses). Following are the different signature statuses:
  * **Active:** The contributor has completed the CLA signing process.
  * **Incomplete:** The contributor has not completed the CLA signing process.
  * **Disabled:** Either the project manager has invalidated the signature of the contributor or CLA manager has removed the contributor's approved criteria from the approved criteria list on corporate CLA console.
* **Signed CCLAs** lists the details of companies that have signed a CCLA. It lists the company name, CLA Managers, approved contributors, approval criteria for the approved contributors, and the signed CCLA document along with the date.

![](https://files.gitbook.com/v0/b/gitbook-legacy-files/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-McSyoQ63waT5Zy3vINd%2F-McU-MgoMo-9loGezlTW%2Fsigned%20iclas.png?alt=media\&token=9eba5fc7-4662-4a78-99b9-b3a4f20d752c)

![Signed CCLAs](https://files.gitbook.com/v0/b/gitbook-legacy-files/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-MRcPPKTyDc0YzE6XlMa%2F-MRdqUglRxH-LtYYrbJZ%2Fsigned%20cclas.png?alt=media\&token=210dfba6-bc3f-482c-bd88-5ec9787fd8c6)

### **Activity Log:** <a href="#activity-log" id="activity-log"></a>

It shows the recent CLA activities for the projects within the CLA group, such as activity description, name of the person who did the activity, date and time of the activity, the corresponding company name where applicable, and the applicable project.

![Activity Log](<../../../.gitbook/assets/activity log.png>)
