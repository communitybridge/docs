# Projects

Click a project from the dashboard, or expand **Projects**, search a project group or project, and click **EasyCLA** under the project to view the related EasyCLA information.

![](../../.gitbook/assets/search-a-project.png)

## Project Group / Project

If your company has multiple signing entities, select the signing entity, from the drop-down, under which you want to sign CLA.

![](../../.gitbook/assets/signing-entity-name.png)

If signing entity name is not in the list, create a new signing entity as described below:

1. From the drop-down list, click **+Add New Signing Entity**.
2. In the **Signing Entity Name** field, provide signing entity name.
3. Click **Add Signing Entity**.

Data under a project group is an aggregate data of all the projects that come under the project group. Following sections display CLA information for a project based on:

* [If company has signed CLA](./#if-company-has-signed-cla)
* [If company has not signed CLA](./#if-company-has-not-signed-cla)

## If Company has signed CLA

{% hint style="warning" %}
**Important:** CLA Managers of a project can add another user as a CLA manager and/or contributor or delete such added users for the same project, however can view CLA managers, Approved List, and Contributor Acknowledgements for other projects of the company. All other roles can view CLA details for the project.
{% endhint %}

#### ACTIVE CLAs FOR MY ORGANIZATION <a id="cla-for-my-organization"></a>

It shows a table that lists the CLAs signed by your company with the project:

* **Project** shows name and logo of the project with which CLA is signed.
* **CLA Group** shows CLA group name which the project belongs to. A CLA group can have multiple projects.
* **Status** shows CLA status—Signed/Not signed.
* **Signed on** shows the date when CLA was signed.
* **Signed By** shows name of the person who signed the CLA.
* **Download** \(shows if CLA is signed\) lets you download PDF file of the signed CLA.

#### CLA MANAGERS FROM MY ORGANIZATION <a id="cla-managers-from-my-organization"></a>

It shows a table that lists CLA managers of your company including their details.

* **Name** shows name and image of the CLA Manager
* **Email Address** shows email address of the CLA Manager.
* **Project** shows the project name for which the individual is assigned as a CLA Manager.
* **Manage** \(Only for CLA Managers\) lets CLA managers [delete](../../easycla/corporate-cla-managers/add-or-delete-cla-managers.md#delete-a-cla-manager) the added CLA managers. Each project has at least one CLA manager. If there is only one CLA manager for a project, that person's details cannot be deleted.
* **+ Add CLA Manager** \(Only for CLA Managers\) lets you [add](../../easycla/corporate-cla-managers/add-or-delete-cla-managers.md#add-a-cla-manager) an individual as a CLA manager.

**RECENT ACTIVITY LOG FOR MY ORGANIZATION**

It shows recent activities of your company for the project. The activity-log displays activity details, project name and logo for which the activity happened along with date and time.

**APPROVED LIST OF CONTRIBUTORS FROM MY ORGANIZATION**

{% hint style="info" %}
**Note:** This section is displayed only for individual projects, not for project groups.
{% endhint %}

It shows a table that lists details of approved contributors from your organization for the project.

* **Approved List** shows the user name/email lD/GitHub user ID /GitHub Organization or Domain name that is in the approved list.
* **Approval Criteria** shows the type with which the contributor is listed in the approved list.
* **Added on** shows the date when the user was added to the approved list.
* **Manage** \(Only for CLA Managers\) lets CLA managers [edit](../../easycla/corporate-cla-managers/approve-and-manage-contributors.md#edit-a-contributors-details) or [delete](../../easycla/corporate-cla-managers/approve-and-manage-contributors.md#delete-a-contributors-details) the approved list.
* **+Add Approval Criteria** is displayed only for CLA Managers, and lets CLA managers [add contributors](../../easycla/corporate-cla-managers/approve-and-manage-contributors.md#add-contributor-s) to an approved list.

**CONTRIBUTOR ACKNOWLEDGEMENT FROM MY ORGANIZATION**

{% hint style="info" %}
**Note:** This section is displayed only for individual projects, not for project groups.
{% endhint %}

It shows a table that lists contributors from your company associated with this project who have completed contributor acknowledgments.

* **Name** shows the name and image of the contributor. Data is retrieved from the individual profile page.
* **LF Login/GitHubID** shows The Linux Foundation login name or GitHub ID of the contributor.
* **Agreement** shows the version of CLA agreement that was signed by the contributor.
* **Acknowledged On** shows date and time when the user acknowledged the agreement.

**Search** lets you to search a contributor by name and LFID/GHID.

**CLA STATISTICS FOR MY ORGANIZATION**

{% hint style="info" %}
**Note:** This section is displayed ****only for project groups, not for individual projects.
{% endhint %}

This is displayed only for project groups, and shows a table that lists the following information:

* **Projects** shows the names of the EasyCLA enabled projects that come under the project group.
* **My CLA Managers** shows total number of CLA managers assigned to projects.
* **Approved Contributor Count** shows total number of approved contributors of projects.

**PROJECTS WITH EASYCLA ENABLED**

{% hint style="info" %}
**Note:** This section is displayed ****only for project groups, not for individual projects.
{% endhint %}

Shows the individual projects that are EasyCLA enabled. Click **View Details** to navigate to the project page.

## If Company has not signed CLA

Following is an example that appears if your company has not signed CLA for a project or a project group. Sign CLA for a project or designate someone to sign CLA for the project. For details, see [Sign Corporate CLA for a Company](../../easycla/corporate-cla-manager-designee-or-initial-cla-manager/sign-corporate-cla-for-a-company.md).

**Note:** You can sign CLA at project-group level or project level based on how the CLA Group is configured.

![CLA not signed](https://gblobscdn.gitbook.com/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-M9roIeDUquwapsG6oPJ%2F-M9rpJlKSE1tcHGVUxfZ%2Fcompany%20has%20not%20signed%20cla.png?alt=media&token=7c8318e4-79e9-4692-9c73-a19d3bc2d831)

