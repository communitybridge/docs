# Approve and Manage Contributors

After a company signs a CCLA, the company's CLA Managers can approve their company's employees to contribute by adding them to their Approved List for that project. **Approved Lists** are lists of domain names, email addresses of individuals, GitHub usernames, or GitHub organization names that allow contributors to be authorized to contribute under the signed CCLA.

{% hint style="info" %}
CLA Managers may receive an email after a contributor sends a request to be added to the Approved list. To approve them, the CLA Manager must add their email address or GitHub username to the approved list.
{% endhint %}

As a CLA manager for a project, you can:

* [Add Contributors to the project's Approved List](approve-and-manage-contributors.md#add-contributor-s)
* [Edit the details for an Approved List criteria](approve-and-manage-contributors.md#edit-a-contributors-details)
* [Delete a Contributor from the project's Approved List](approve-and-manage-contributors.md#delete-a-contributors-details)

**Note**: Before doing any of the following actions, you must first be a CLA Manager under a signed CCLA. If your company has not yet signed a CCLA, you will need to first [coordinate the CCLA signing process](coordinate-signing-ccla.md).

## **Add Contributor\(s\)**

1. ​[Sign in](sign-in-to-the-easycla-corporate-console.md) to the[ EasyCLA Corporate Console](https://organization.lfx.linuxfoundation.org/company/dashboard).
2. Click a project of interest.
3. Click **+ Add Approval Criteria** under **Approved List Of Contributions From My Organization**.

![Add Approval Criteria](../../.gitbook/assets/add-approval-criteria.png)

4. On the **Add Approval Criteria** window, select an option from the drop-down list, and provide details in the field next to it.

![Add Approval Criteria](../../.gitbook/assets/add-approval-criteria%20%281%29.png)

{% hint style="info" %}
**Note:**

* _Email Address Domain_ allows contribution from anyone with an email address with that domain name.
* _Contributor's Gerrit/GitHub Email address_ allows contribution from the person with that email address.
* _GitHub Organization_ allows contribution from anyone in that GitHub organization.
* _GitHub Username_ allows contribution from the person with that GitHub username.

GitHub Organization and GitHub Username are not applicable while adding contributors to Gerrit projects.
{% endhint %}

5. Click **+Add More** to add other details for more contributors.

6. Click **Save** to save the approval criteria settings.

{% hint style="info" %}
If you add a contributor to the approved list after you receive an email requesting authorization, inform them to [acknowledge company contribution](../contributors/corporate-contributor.md#acknowledge-company-contribution) before they contribute to the project.
{% endhint %}

## Edit a Contributor's Details

Click ![](../../.gitbook/assets/edit-icon.png) in the row for one of the Approval List criteria, make edits, and click **Save**.

## Delete a Contributor's Details

Click ![](../../.gitbook/assets/delete-icon.png) in the row for one of the Approval List criteria, to delete the contributor or the group criteria.

![Delete Contributors](../../.gitbook/assets/delete-contributors.png)

