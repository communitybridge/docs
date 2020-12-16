# View and Manage CLA Group Details

You can view CLA group details, edit or delete an added CLA group. Based on CLA configuration for the project, available data are shown under CLA Groups.

1. [Sign in](sign-in-to-project-control-center.md).

2. Click a **project name** of interest.

3. Navigate to the **Tools** tab, and click **CLA**.

![Tools](../../.gitbook/assets/tools-tab.png)

**CLA Groups** shows the CLA groups that you have added to the project. A CLA group defines one or more CLA types that contributors must sign. A CLA group shows the following details:

* **Name** of the CLA group.
* **Projects Covered** shows the number of projects that are covered under the CLA group.
* **Repositories** shows the total number of repositories of the added projects that are enrolled for CLA monitoring. You must[ enforce EasyCLA](add-and-manage-git-organizations-and-repositories/add-or-remove-git-repositories-for-cla-monitoring.md) for one or more Git repositories for them to be counted.
* **Signatures** shows the total number of individuals who have signed CLA within the CLA group. This includes both ICLA and/or CCLA based on the CLA group configuration.
* Click![](../../.gitbook/assets/edit-cta.png)to edit the title and description of the CLA group.
* Click![](../../.gitbook/assets/delete-icon.png)to create a support ticket requesting to delete the CLA group.
* Under **PROJECTS** tab, expand the project group to view projects that are enrolled for the CLA group. Inactive Selected checkbox indicates that the project is added under another CLA group. Click **Manage** to [add and manage git organizations and repositories](add-and-manage-git-organizations-and-repositories/).
* Navigate to **TEMPLATES** tab to view ICLA and/or CCLA documents based on CLA configuration.
* Navigate to **SIGNATURES** tab to view signed ICLAs and CCLAs. Click 
  * **Signed ICLAs** lists the details of individuals who have signed ICLA.
  * **Signed CCLAs** lists the details of corporate members who have signed CCLA. It lists the CLA managers, approved contributors, approval criteria for the approved contributor, and the signed CLA document.

![View CLA Group Details](../../.gitbook/assets/view-cla-details.png)

**ACTIVITY LOG** shows the recent CLA activities for the project, such as activity description, name of the person who did the activity, date and time of activity, association company's name, and the project for which the activity happened.  

![](../../.gitbook/assets/activity-log.png)

 

