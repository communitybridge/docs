# View and Manage CLA Group Details

A Project Manager can view CLA group details and can edit or delete a CLA group.

1. [Sign in](sign-in-to-project-control-center.md).
2. Click a **project name** of interest.
3. Navigate to the **Tools** tab, and click **CLA**.

![Tools](../../.gitbook/assets/tools-tab.png)

**CLA Groups** shows the CLA groups that have been added to the project. A CLA group defines a CCLA and/or ICLA that contributors must sign. A CLA group shows the following details:

![CLA Groups](../../.gitbook/assets/cla-group-names.png)

* **Name** of the CLA group, and whether the CLA Group includes a CCLA and/or an ICLA.
  * **Projects Covered** shows the number of projects that are covered under the CLA group.
  * **Repositories** shows the total number of repositories of the added projects that are enrolled for CLA monitoring. You must [enforce EasyCLA](add-and-manage-git-organizations-and-repositories/enforce-or-remove-cla-monitoring.md) for one or more Git repositories for them to be counted.
  * **Signatures** shows the total number of individuals who have signed CLA within that CLA group. This includes both ICLA and/or CCLA based on the CLA group configuration.
  * Click![](../../.gitbook/assets/edit-cta.png)to edit the title and description of the CLA group.
  * Click![](../../.gitbook/assets/delete-icon.png)to create a support ticket requesting to delete the CLA group. 
* Under the **PROJECTS** tab, expand the project group to view projects that are enrolled for the CLA group. Inactive selected check boxes indicate that the project has already been added to another CLA group. Click **Manage** to [add and manage Git organizations and repositories](add-and-manage-git-organizations-and-repositories/).
* Navigate to **TEMPLATES** tab to view and download the ICLA and/or CCLA templates.
* Navigate to **SIGNATURES** tab to view signed ICLAs and CCLAs.
  * **Signed ICLAs** lists details of individuals who have signed an ICLA, such as name, LF Login name, GitHub ID, and email address.
  * **Signed CCLAs** lists the details of companies that have signed a CCLA. It lists the company name, CLA Managers, approved contributors, approval criteria for the approved contributors, and the signed CCLA document along with the date.

![Signed CCLAs](../../.gitbook/assets/signed-cclas.png)

**ACTIVITY LOG** shows the recent CLA activities for the projects within the CLA group, such as activity description, name of the person who did the activity, date and time of the activity, the corresponding company name where applicable, and the applicable project.

![](../../.gitbook/assets/activity-log.png)

