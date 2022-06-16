# Approve and Manage Contributors

After a company signs a CCLA, the company's CLA Managers can approve their company's employees to contribute by adding them to their Approved List for that project. **Approved Lists** are lists of domain names, email addresses of individuals, GitHub usernames, GitHub organization names, that allow contributors to be authorized to contribute under the signed CCLA.

{% hint style="info" %}
**Note:** CLA Managers may receive an email after a contributor sends a request to be added to the Approved list. To approve them, the CLA Manager must add their email address or GitHub username to the approved list.
{% endhint %}

As a CLA manager for a project, you can:

* ​[Add Contributors to the project's Approved List](approve-and-manage-contributors.md#add-contributor-s)​
* ​[Edit the details for an Approved List criteria](approve-and-manage-contributors.md#edit-a-contributors-details)​
* ​[Delete a Contributor from the project's Approved List](approve-and-manage-contributors.md#delete-a-contributors-details)​

{% hint style="info" %}
**Note**: Before doing any of the following actions, you must first be a CLA Manager under a signed CCLA. If your company has not yet signed a CCLA, you will need to first [coordinate the CCLA signing process](coordinate-signing-cla-and-become-initial-cla-manager.md).
{% endhint %}

## **Add Contributor(s)** <a href="#add-contributor-s" id="add-contributor-s"></a>

1. ​Sign in to the[ EasyCLA Corporate Console](https://organization.lfx.linuxfoundation.org/company/dashboard).
2. Click a project of interest.
3. Click **+ Add Approval Criteria** under **Approved List Of Contributions From My Organization**.

![Add Approval Criteria](<../../../.gitbook/assets/add approval criteria.png>)

4\. On the **Add Approval Criteria** window, select an option from the drop-down list, and provide details in the field next to it.

![Add Approval Criteria](<../../../.gitbook/assets/add approval criteria (1) (1) (1).png>)

{% hint style="info" %}
**Note:**

* _Email Address Domain_ allows contribution from anyone with an email address with that domain name.
* _Contributor's Gerrit/GitHub Email address_ allows contribution from the person with that email address.
* _GitHub Organization_ allows contribution from anyone in that GitHub organization.
* _GitHub Username_ allows contribution from the contributor with that GitHub username.
* _GitLab Group URL_ allows contribution from anyone associated with the GitLab Group.
* _GitLab Username_ allows contribution from the contributor with that GitLab username.
{% endhint %}

5\. Click **+Add More** to add other details for more contributors.

6\. Click **Save** to save the approval criteria settings.

{% hint style="info" %}
**Note:** If you add a contributor to the approved list after you receive an email requesting authorization, inform them to [acknowledge company contribution](../contributors/corporate-contributor.md#acknowledge-company-contribution) before they contribute to the project.
{% endhint %}

## Edit a Contributor's Details <a href="#edit-a-contributors-details" id="edit-a-contributors-details"></a>

Click ![](../../../.gitbook/assets/Edit\_Icon.png) in the row for one of the Approval List criteria, make edits, and click **Save**.

## Delete a Contributor's Details <a href="#delete-a-contributors-details" id="delete-a-contributors-details"></a>

Click ![](../../../.gitbook/assets/delete\_icon.png) in the row for one of the Approval List criteria, to delete the contributor or the group criteria.

{% hint style="info" %}
**Note:** If you delete a contributor's details or an approval criteria, then the status of signature for the contributor, who signed a CLA under a CLA group with that criteria, will be displayed as "Disabled" under Signatory tab of the CLA group on project console. For details about the statuses see, [Signatures](../project-managers/view-and-manage-cla-group-details.md#signatures). Only Project Managers and Community Program managers can access project console (also called Project Control Center).
{% endhint %}

![Delete Contributors](<../../../.gitbook/assets/delete contributors.png>)
