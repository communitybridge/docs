---
description: >-
  This page describes CLA information for projects with which your company has
  signed CLA.
---

# EasyCLA

Companies sign CLA at project level under a foundation. However, for CNCF and CloudFoundry foundations, companies sign CLA at foundation level. So, the following dashboards are not displayed for the aforementioned foundations. 

The data for individual dashboards of this page varies based on the user's role.

Following are various dashboards of EasyCLA page:

### CLA STATISTICS

This provides CLA highlights for the project.

* **CLA SIGNED** shows total number of Contributor License Agreements—ICLA \(Individual CLA\) and CCLA \(Corporate CLA\)—signed by your company for one or more project within the foundation. This includes both the number of CLAs signed for one or more projects, and the individual contributors per signed CLA.
* **TOTAL CONTRIBUTORS** shows the total number of Individual and Corporate contributors including approved contributors.
* **REPOSITORIES USING EASYCLA** shows total number git repositories of projects that use EasyCLA.

Data for other dashboards are displayed based on:

* [If your Company has signed CLA](./#if-your-company-has-signed-cla)
* [If your Company has not signed CLA](./#if-your-company-has-not-signed-cla)

## If your Company has signed CLA

{% hint style="warning" %}
**Important:** Users of a Company with ****CLA Managers permission for a project can add another user as a CLA manager and/or contributor or delete such added users for the same project, however can view CLA managers, Approved List, and Contributor Acknowledgements for other projects of the company. All other roles can view CLA details for the project.
{% endhint %}

### CLA FOR MY ORGANIZATION

It shows a table that lists the CLAs signed by your company with the project:

* **Project** shows name and logo of the project with which CLA is signed.
* **CLA Group** shows CLA group name which the project belong to. A project can have multiple CLA groups.
* **Status** shows CLA status—Signed/Not signed.
* **Signed on** shows the date when CLA was signed.
* **Signatory** shows name of the person who signed the CLA.
* **Action** lets you download PDF file of the signed CLA

### CLA MANAGERS FROM MY ORGANIZATION

It shows a table that lists CLA managers of your company including their details.

* **Name** shows name and image of the CLA Manager
* **Email Address** shows email address of the CLA Manager.
* **Added on** shows the date when the individual was added as CLA Manager. 
* **Action** \(Appears only for CLA Managers\) ****lets CLA managers delete the added CLA managers. Each project has at least one CLA manager. If there is only one CLA manager for a project, that person's details cannot be deleted. **Note:** As a CLA manager, you can add a user as a CLA manager or delete CLA managers. For details, see [How to Add or Delete a CLA Manager](how-to-add-or-delete-a-cla-manager.md).

### APPROVED LIST OF CONTRIBUTORS FROM MY ORGANIZATION

It shows a table that lists details of approved contributors from your organization for the project.

* **Approved List** shows the user name/email lD/GitHub user ID /GitHub Organization or Domain name that is in the approved list.
* **Coverage Type** shows the type with which the contributor is listed in the approved list.
* **Added on** **shows** the date when the user was added to the approved list.
* **Manage** \(Appears only for CLA Managers\) lets CLA managers edit the approved list or delete it. As a CLA manager, you can add, edit or delete a contributor. For details, see [How to Add, Edit or Delete a Contributor](how-to-add-edit-or-delete-a-contributor.md).

### CONTRIBUTOR ACKNOWLEDGEMENT FROM MY ORGANIZATION

It shows a table that lists contributors from your company associated with this project who have completed contributor acknowledgments.

* **Name** shows the name and image of the contributor. Data is retrieved from the individual profile page.
* **LFID/GHID** shows the LinuxFoundation ID or GitHub ID of the contributor.
* **Agreement** shows the version of CLA agreement that was signed by the contributor.
* **Timestamp** shows date and time when the user acknowledged the agreement.

**Search** lets you to search a contributor by name and LFID/GHID.

### RECENT ACTIVITY LOG FOR MY ORGANIZATION

It shows recent activities of your company for the project. The activity-log displays activity details, project name and logo for which the activity happened along with date and time.

## If your Company has not signed CLA

The following window appears if your company has not signed CLA with a project or foundation.

![CLA not signed](../../../../.gitbook/assets/company-has-not-signed-cla.png)



