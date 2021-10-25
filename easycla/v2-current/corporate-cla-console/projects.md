# Projects

Click a project from the dashboard, or expand **Projects**, search for a project, and click **EasyCLA** under the project to view the related EasyCLA information.

![](<../../../.gitbook/assets/search a project.png>)

## Project Hierarchy

In the user interface, some projects are nested under parent projects or foundations that they are contained in. The data shown for a parent project or foundation is an aggregate of all the projects under it. The following sections show CLA information for a project based on:

* [If company has signed CLA](broken-reference)
* [If company has not signed CLA](broken-reference)

## If Company has signed CLA

{% hint style="warning" %}
**Important:** The CLA Managers for a project can edit their company's EasyCLA settings (such as authorized contributors approval lists) for only the project(s) where they are the CLA Managers. Others (such as CLA Managers for other projects, or other roles) will have read-only access but cannot change the company's EasyCLA settings for the project.
{% endhint %}

### ACTIVE CLAs FOR MY ORGANIZATION <a href="cla-for-my-organization" id="cla-for-my-organization"></a>

This shows a table that lists the CCLA signed by your company for this project:

* **Project** shows the name and logo of the project for which the CCLA was signed.
* **CLA Group** shows the CLA group name which the project belongs to. A CLA group can cover multiple projects.
* **Status** shows CCLA status (e.g., Signed or Not signed).
* **Signed on** shows the date when the CCLA was signed.
* **Signed By** shows the name of the person who signed the CCLA.
* **Download** (shown if CCLA is signed) lets you download the PDF file of the signed CLA.

### CLA MANAGERS FROM MY ORGANIZATION <a href="cla-managers-from-my-organization" id="cla-managers-from-my-organization"></a>

This shows a table that lists CLA Managers of your company including their details.

* **Name** shows the name of the CLA Manager
* **Email Address** shows the email address of the CLA Manager.
* **Manage** (Only for CLA Managers) lets CLA Managers [delete](broken-reference) CLA Managers.
* **+ Add CLA Manager** (Only for CLA Managers) lets CLA Managers [add](broken-reference) other CLA Managers.

**RECENT ACTIVITY LOG FOR MY ORGANIZATION**

This shows recent EasyCLA-related activities of your company for the project. The activity log displays activity details, the project name and logo for which the activity happened, and the date and time.

**APPROVED LIST OF CONTRIBUTORS FROM MY ORGANIZATION**

{% hint style="info" %}
**Note:** This section is displayed only for individual projects, not for project groups.
{% endhint %}

This shows a table that lists details of approved contributors from your organization for the project.

* **Approved List** shows the email address domain name, GitHub/Gerrit email address, GitHub Organization, GitHub Username, GitLab Group URL or GitLab Username.
* **Approval Criteria** shows the type of approval criteria.
* **Added on** shows the date when the criteria was added to the approved list.
* **Manage** (Only for CLA Managers) lets CLA Managers [edit](../../v1-deprecated/cla-manager/approve-contributors.md#edit-a-contributors-details) or [delete](../../v1-deprecated/cla-manager/approve-contributors.md#delete-a-contributors-details) the criteria on the approved list.
* **+Add Approval Criteria** (Only for CLA Managers) lets CLA managers [add contributor approval criteria](../../v1-deprecated/cla-manager/approve-contributors.md#add-contributor-s) to the approved list.

**CONTRIBUTOR ACKNOWLEDGEMENT FROM MY ORGANIZATION**

{% hint style="info" %}
**Note:** This section is displayed only for individual projects, not for project groups.
{% endhint %}

This shows a table that lists contributors from your company authorized to contribute to this project who have completed contributor acknowledgments.

* **Name** shows the name of the contributor.
* **LF Login/GitHub ID** shows the Linux Foundation login name or GitHub username of the contributor.
* **Agreement** shows the version of the CCLA under which the contributor was authorized.
* **Acknowledged On** shows the date and time when the user acknowledged their association with the company under the CCLA.

**Search** lets you search for a contributor by name and LFID/GitHub ID.

**PROJECTS WITH EASYCLA ENABLED**

{% hint style="info" %}
**Note:** This section is displayed only for parent projects that have child projects.
{% endhint %}

Shows the child projects that have EasyCLA enabled. Click **View Details** to navigate to the project page.

## If Company has not signed CLA

If your company has not yet signed a CCLA for a project, the following screen will appear.

![CLA not signed](<../../../.gitbook/assets/company has not signed cla.png>)

For details about signing a CCLA, see [Getting Started](../../v1-deprecated/getting-started/) and [coordinating signing a CCLA](broken-reference).
