---
description: Troubleshooting helps you to resolve problems in your EasyCLA implementation.
---

# EasyCLA Troubleshooting

> If you are having issues with EasyCLA, go to [The Linux Foundation Support Center](https://jira.linuxfoundation.org/plugins/servlet/theme/portal/4/create/143), and file a ticket.

Following sections help you troubleshoot common problems that you might encounter when using EasyCLA tool.

* [GitHub pull request is not passing](./#github-pull-request-is-not-passing)
* * [Contributor's EasyCLA status is not updated](./#contributors-easycla-status-is-not-updated)
* ​[EasyCLA is Disabled for a GitHub repository](easycla-is-disabled.md)​

### GitHub pull request is not passing

#### Problem:

I have an agreement on file, but my GitHub pull request is still not passing.

#### Solution:

Ensure that your commits are [linked to your GitHub account](https://docs.github.com/en/github/committing-changes-to-your-project/why-are-my-commits-linked-to-the-wrong-user#commits-are-not-linked-to-any-user). If your commits are not linked to any user, GitHub will display the grey Octocat logo beside them.

### Contributor's EasyCLA status is not updated

#### Problem \#1:

After a Contributor has signed an ICLA, it may take a few moments for the status of the EasyCLA checks to update.

#### Solution \#1:

Please wait a few moments and then try refreshing the page.

#### Problem \#2:

For a CCLA, after a Contributor has been added to the approved list for the first time, the CLA status still displays **Not Covered** for GitHub and **No Contributor Agreement** for Gerrit.

#### Solution \#2:

After being added to the approved list under their company's signed CCLA, the Contributor must [acknowledge their association with the company](../../contributors/corporate-contributor.md#acknowledge-company-contribution). This is a one-time action and, after completion, it will not be required for future contributions to that project.

Although it is uncommon, some projects may require a Contributor under a CCLA to additionally [sign an ICLA](../../contributors/corporate-contributor.md#if-you-are-asked-to-sign-icla). If this is required, then after completing the company acknowledgement, the Contributor will be guided to sign the project's ICLA.

{% hint style="warning" %}
**Important \(Only for Gerrit Contributors\) :** If the status on Git command line still shows "No contributor agreement" when you push the code change, you need to navigate to the Gerrit window, **sign out**, **sign in** again, and then push the code.

![](../../../.gitbook/assets/signout-gerrit.png)
{% endhint %}

### Unable to contribute to EasyCLA-enforced repositories on GitHub

Problem:

Solution:

Still having trouble contributing to EasyCLA-enforced repositories on GitHub?

1. Make sure your company email is verified in your [GitHub account settings](https://github.com/settings/emails).
2. **Make sure your** [**commits are linked to the correct user**](https://help.github.com/en/github/committing-changes-to-your-project/why-are-my-commits-linked-to-the-wrong-user)**.**
3. [Ask your CLA Manager](https://docs.linuxfoundation.org/lfx/easycla/ccla-managers-and-ccla-signatories/approve-contributors) to add your GitHub Username to the Approved List, rather than your email.
4. If you believe you are a member of an Approved GitHub Organization, [make sure you have made that membership public](https://help.github.com/en/github/setting-up-and-managing-your-github-user-account/publicizing-or-hiding-organization-membership).
5. Try making your [GitHub email address](https://github.com/settings/emails) public.

