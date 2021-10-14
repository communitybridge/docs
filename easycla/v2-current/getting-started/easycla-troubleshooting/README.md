# EasyCLA Troubleshooting



> If you are having issues with EasyCLA, go to [The Linux Foundation Support Center](https://jira.linuxfoundation.org/plugins/servlet/theme/portal/4/create/143), and file a ticket.

Following sections help you troubleshoot common problems that you might encounter when using EasyCLA tool.

* [GitHub pull request is not passing](broken-reference)
* [(GitHub) Unable to contribute to EasyCLA-enforced repositories](broken-reference)
* [(Gerrit) Unable to contribute to EasyCLA-enforced repositories](broken-reference)
* [(GitHub) Individual Contributor's EasyCLA status is not updated](broken-reference)
* [(Gerrit) Individual Contributor's EasyCLA status is not updated](broken-reference)
* [(GitHub) Corporate Contributor's EasyCLA status is not updated after being added to the approved list](broken-reference)
* [(Gerrit) Corporate Contributor's EasyCLA status is not updated after being added to the approved list](broken-reference)
* [EasyCLA status displays "Expected"​ in the "Checks" section of the Pull Request](broken-reference)
* [EasyCLA status does not change to "Authorized" for multiple open pull requests after signing ICLA and/or CCLA](broken-reference)
* [I cannot use EasyCLA for my Linux Foundation-hosted project](broken-reference)
* [My company is not displayed in the list when I am trying to contribute code under a corporate CLA (CCLA)](broken-reference)
* [I cannot view my individual CLA (ICLA) after I sign it](broken-reference)
* [EasyCLA is Disabled for a GitHub repository](broken-reference)

## GitHub pull request is not passing

#### Problem:

I have an agreement on file, but EasyCLA does not authorize me and displays "Missing ID on Commit".

#### Solution:

* Ensure that your commits are [linked to your GitHub account](https://docs.github.com/en/github/committing-changes-to-your-project/why-are-my-commits-linked-to-the-wrong-user#commits-are-not-linked-to-any-user). If your commits are not linked to any GitHub user, GitHub will display the _grey Octocat logo _![](<../../../../.gitbook/assets/grey colored octobat.png>)beside the commits. 
* If your commits are linked to your GitHub account, and yet the GitHub pull request is not passing the EasyCLA check, then open the pull request, type`/easycla` in the comment box, click **Comment **as shown below. This runs the EasyCLA bot again, and the GitHub pull request is passed.

![Pull Request Commenting](<../../../../.gitbook/assets/pull request commenting.png>)

## (GitHub) Unable to contribute to EasyCLA-enforced repositories

#### Problem:

Contributor's commits are linked to GitHub account, however, they are still having trouble contributing to EasyCLA-enforced repositories.

#### Solution:

* If your CLA Manager has approved your company email address or email domain, ensure that your company email is[ verified in your GitHub account settings](https://docs.github.com/en/github/getting-started-with-github/verifying-your-email-address) and make sure your GitHub email address is public.

Or

* If your CLA Manager has approved your GitHub Organization,[ ensure that you have made that membership public](https://docs.github.com/en/github/setting-up-and-managing-your-github-user-account/publicizing-or-hiding-organization-membership).

## (Gerrit) Unable to contribute to EasyCLA-enforced repositories

#### Problem:

Contributor's commits are linked to Gerrit account, however, they are still having trouble contributing to EasyCLA-enforced repositories.

#### Solution:

Ensure that your Gerrit email address is added to the approved list, and you must log in to Gerrit instance of your project using the same email address that is added to the approved list.

## (GitHub) Individual Contributor's EasyCLA status is not updated

#### Problem:

After a Contributor has signed an ICLA, EasyCLA status is not updated on contributor console.

#### Solution:

It may take a few moments for the status of the EasyCLA checks to update. Please wait a few moments and then refresh the page.** **If the EasyCLA status is still not updated, open the pull request, and comment `/easycla` in the comment section as shown below. This comment runs the bot again. If the status still does not change, open a support ticket.

![Comment /easycla in the Pull Request](<../../../../.gitbook/assets/pull request commenting.png>)

## (Gerrit) Individual Contributor's EasyCLA status is not updated

#### Problem:

After a Contributor has signed an ICLA, EasyCLA status on Git command line still displays "_No contributor agreement_" when the contributor pushes the code change.

#### Solution:

Navigate to the Gerrit window, **sign out**, **sign in** again, and then push the code.\
![](<../../../../.gitbook/assets/signout gerrit.png>) 

## (GitHub) Corporate Contributor's EasyCLA status is not updated

#### Problem:

For a CCLA, after a Contributor has been added to the approved list for the first time, the CLA status still displays **Not Covered**.

#### Solution:

After being added to the approved list under their company's signed CCLA, the Contributor must [acknowledge their association with the company](broken-reference). This is a one-time action and, after completion, it will not be required for future contributions to that project.

Although it is uncommon, some projects may require a Contributor under a CCLA to additionally [sign an ICLA](broken-reference). If this is required, then after completing the company acknowledgement, the Contributor will be guided to sign the project's ICLA.

## (Gerrit) Corporate Contributor's EasyCLA status is not updated

#### Problem:

For a CCLA, after a contributor has been added to the approved list for the first time, the CLA status on Git command line still displays **No contributor agreement** when you push the code change.

#### Solution:

Navigate to the Gerrit window, **sign out**, **sign in **again, and then push the code.

![](<../../../../.gitbook/assets/signout gerrit.png>)

## EasyCLA status displays "Expected"​ in the "Checks" section of the Pull Request 

#### **Problem:**

In the “Checks” section of the pull request, EasyCLA status is showing as “Expected”. 

#### **Solution:**

Open the pull request, and comment` /easycla` in the comment section as shown in the image below. This comment runs the bot again. If the status still does not change, open a support ticket.

![Comment /easycla in the Pull Request](<../../../../.gitbook/assets/pull request commenting.png>)

## EasyCLA status does not change to "Authorized" for multiple open pull requests after signing ICLA and/or CCLA

#### **Problem:**

After signing an ICLA or verifying under a CCLA, the status does not change to “Authorized” for multiple open pull requests.

#### **Solution:**

Open one pull request, and comment` /easycla` in the comment section as shown in the image below. This comment runs the bot again. If the status still does not change, open a support ticket.

![Comment /easycla in the Pull Request](<../../../../.gitbook/assets/pull request commenting.png>)

## **I cannot use EasyCLA for my Linux Foundation-hosted project**

#### **Problem:**

After hosting my project on The Linux Foundation, I can not use EasyCLA for my project.

#### **Solution:**

Open [https://jira.linuxfoundation.org/plugins/servlet/theme/portal/4/create/143](https://jira.linuxfoundation.org/plugins/servlet/theme/portal/4/create/143), submit the form describing your requirements, and import your existing CLAs.

## My company is not displayed in the list when I am trying to contribute code under a corporate CLA (CCLA)

#### Problem:

When I am trying to contribute code under a CCLA, my company is not displayed in the list.

#### Solution:

You must create a record for your company as described [here](broken-reference).

## I cannot view my individual CLA (ICLA) after I sign it

#### Problem:

I have signed an ICLA, however I cannot view the signed ICLA.

#### Solution:

Open your email, that you have provided while signing the ICLA, to check the signed ICLA that is sent from The Linux Foundation. If you have not received the email, you can open a support ticket to have it resent.



\
