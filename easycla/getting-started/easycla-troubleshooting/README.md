---
description: Troubleshooting helps you to resolve problems in your EasyCLA implementation.
---

# EasyCLA Troubleshooting

> If you are having issues with EasyCLA, go to [The Linux Foundation Support Center](https://jira.linuxfoundation.org/plugins/servlet/theme/portal/4/create/143), and file a ticket.

Following sections help you troubleshoot common problems that you might encounter when using EasyCLA tool.

* [GitHub pull request is not passing](./#github-pull-request-is-not-passing)
* [Unable to contribute to EasyCLA-enforced repositories](./#unable-to-contribute-to-easycla-enforced-repositories)
* [Contributor's EasyCLA status is not updated](./#contributors-easycla-status-is-not-updated)
* [Corporate contributor's EasyCLA status is not updated even after added to the approved list](./#problem-corporate-contributors)
* ​[EasyCLA is Disabled for a GitHub repository](easycla-is-disabled.md)​

## GitHub pull request is not passing

#### Problem:

I have an agreement on file, but my GitHub pull request is still not passing.

#### Solution:

Ensure that your commits are [linked to your GitHub account](https://docs.github.com/en/github/committing-changes-to-your-project/why-are-my-commits-linked-to-the-wrong-user#commits-are-not-linked-to-any-user). If your commits are not linked to any user, GitHub will display the grey Octocat logo beside them.

## Unable to contribute to EasyCLA-enforced repositories

#### Problem:

Contributor's commits are linked to GitHub or Gerrit account, however, they are still having trouble contributing to EasyCLA-enforced repositories?

#### Solution for GitHub:

1. Ensure that your company email is [verified in your GitHub account settings](https://docs.github.com/en/github/getting-started-with-github/verifying-your-email-address).
2. Ensure that your [commits are linked to the correct user](https://help.github.com/en/github/committing-changes-to-your-project/why-are-my-commits-linked-to-the-wrong-user).
3. Ask your CLA Manager to add your GitHub Username to the Approved List, instead of your GitHub email address.
4. If you are a member of an Approved GitHub Organization, [ensure that you have made that membership public](https://docs.github.com/en/github/setting-up-and-managing-your-github-user-account/publicizing-or-hiding-organization-membership).
5. Make your GitHub email address public.

#### Solution for Gerrit:

Ensure that your Gerrit email address is added to the approved list, and you must log in to Gerrit instance of your project using the same email address that is added to the approved list.

## Contributor's EasyCLA status is not updated

* [Individual Contributors](./#problem-individual-contributors)
* [Corporate Contributors](./#problem-corporate-contributors)

### Problem \(Individual Contributors\):

After a Contributor has signed an ICLA, EasyCLA status is not updated on contributor console.

#### Solution for GitHub:

It may take a few moments for the status of the EasyCLA checks to update. Please wait a few moments and then refresh the page.

#### Solution for Gerrit:

If the status on Git command line still shows "No contributor agreement" when you push the code change, then you need to navigate to the Gerrit window, **sign out**, **sign in** again, and then push the code.  
![](../../../.gitbook/assets/signout-gerrit.png) 

### Problem \(Corporate Contributors\):

For a CCLA, after a Contributor has been added to the approved list for the first time, the CLA status still displays **Not Covered** for GitHub and **No Contributor Agreement** for Gerrit.

#### Solution:

After being added to the approved list under their company's signed CCLA, the Contributor must [acknowledge their association with the company](../../contributors/corporate-contributor.md#acknowledge-company-contribution). This is a one-time action and, after completion, it will not be required for future contributions to that project.

Although it is uncommon, some projects may require a Contributor under a CCLA to additionally [sign an ICLA](../../contributors/corporate-contributor.md#if-you-are-asked-to-sign-icla). If this is required, then after completing the company acknowledgement, the Contributor will be guided to sign the project's ICLA.

{% hint style="warning" %}
**Important \(Only for Gerrit Contributors\) :** If the status on Git command line still shows "No contributor agreement" when you push the code change, you need to navigate to the Gerrit window, **sign out**, **sign in** again, and then push the code.

![](../../../.gitbook/assets/signout-gerrit.png)
{% endhint %}

