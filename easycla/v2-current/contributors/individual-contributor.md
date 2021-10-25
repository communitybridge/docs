# Individual Contributor

An individual contributor is one who contributes code on their own behalf (and not on behalf of an employer). If you are contributing code on behalf of your employer, see the [Corporate Contributor](broken-reference) workflow.

Upon creating a pull request in GitHub or GitLab or submitting changed code in Gerrit, EasyCLA will check whether the contributor is authorized under a signed CLA for that project. If they are not, and if they are contributing on their own behalf, then they must sign an ICLA.

* [GitHub](broken-reference)
* [Gerrit](broken-reference)
* [GitLab](broken-reference)

## GitHub

1. In GitHub, clone the repository want to contribute to Or click the **pencil icon** next to a file of the repository to edit; it will clone the repository under your username.
2. Make a change and create a pull request.

{% hint style="info" %}
1. EasyCLA checks the CLA status of all committers involved in that pull request. EasyCLA displays a cross or a check mark beside the name of each contributor who is involved in that pull request based on their CLA status.
2. A cross next to a contributor's name means the EasyCLA check has failed, because the contributor is not authorized under a signed CLA.
{% endhint %}

![CLA Check Failed](../../../.gitbook/assets/cla-github-individual-check-fail.png)

3\. Click![](../../../.gitbook/assets/lfx-easycla.png) or **Please click here to be authorized**.

4\. Click **Authorize LF-Engineering**. (Subsequent contributions will not require this authorization.)

​ ![](../../../.gitbook/assets/authorize-linux-foundation-easycla.png) ​

The CLA Contributor Console appears and shows the CLA group for your project.

{% hint style="info" %}
**Note:** If the project is not configured to use ICLAs, then **Proceed as an Individual Contributor** is inactive. In this case, individuals would not be able to contribute on their own behalf.
{% endhint %}

![CLA ICLA Flow](../../../.gitbook/assets/cla-icla-flow.png)

5\. Click **Proceed as an Individual Contributor**.\
![](../../../.gitbook/assets/preparing-cla.png)

6\. After the **CLA Ready For Signature** window appears, click **SIGN CLA**.

![CLA Ready for Signature](../../../.gitbook/assets/cla-ready-for-signature.png)

DocuSign presents the ICLA document for your signature.

![DocuSign](../../../.gitbook/assets/docusign-icla-flow.png)

7\. Select the check box and click **CONTINUE**. Follow the instructions in the DocuSign document, fill in the indicated fields, sign it, and click **FINISH**.

{% hint style="info" %}
**Result:**

* You will receive an email from The Linux Foundation, informing you that you have signed the ICLA.&#x20;
* You can download the PDF document by clicking the link from the email. You will be re-directed to the Linux Foundation's website. If the download doesn't start automatically, click **Proceed to Download**. ![](../../../.gitbook/assets/proceed-to-download-icla.png)&#x20;
{% endhint %}

You are redirected to GitHub. Wait a few seconds or refresh the page for the EasyCLA status to be updated. A check mark appears next to your branch.

![GitHub Individual Contributor Pass](../../../.gitbook/assets/cla-github-individual-contributor-pass.png)

8\. Click **Merge pull request** and confirm the merge.

## Gerrit

1. In Gerrit, clone a repository under the Gerrit instance into your local machine.
2. Make a change and push the code to your Gerrit repository.
3. A warning link that you need to sign a CLA appears:

![CLA Gerrit Sign a CLA](../../../.gitbook/assets/cla-gerrit-sign-a-cla.png)

4\. Navigate to the Gerrit instance of your project. For example, if you are contributing to the OPNFV project, navigate to [https://gerrit.opnfv.org](https://gerrit.opnfv.org)​

5\. Sign in using your LF [Single Sign-On (SSO)](https://docs.linuxfoundation.org/lfx/sso/create-an-account) account.

6\. Navigate to **Settings**— the gear icon on the upper right corner— and click **Agreements** from the menu on the left:

​![Settings Icon](../../../.gitbook/assets/settings-icon.png)​ ​![Gerrit Agreements](../../../.gitbook/assets/agreements.png)​

7\. Click **New Contributor Agreement**.

![Agreement Link](../../../.gitbook/assets/agreement-link.png)

8\. Select **Individual CLA (ICLA)**, and click **Please review the agreement**.

![ICLA User Flow](../../../.gitbook/assets/icla-flow.png)

9\. Click **Proceed To Individual Authorization**.

![Proceed to Individual Authorization](../../../.gitbook/assets/proceed-to-individual-authorization.png)

10\. Sign in if you are prompted, and you will be redirected to the Contributor Console.

11\. After CLA preparation is completed, click **Sign CLA**.

![CLA Ready for Signature](../../../.gitbook/assets/cla-ready-for-signature.png)

DocuSign presents the ICLA document for your signature.

![DocuSign](../../../.gitbook/assets/docusign-icla-flow.png)

12\. Select the check box and click **CONTINUE**. Follow the instructions in the DocuSign document, fill in the indicated fields, sign it, and click **FINISH**.

{% hint style="info" %}
**Result:**

* A message appears informing you that you have signed the ICLA.
* You will also receive an email from The Linux Foundation, informing you that you have signed the ICLA.&#x20;
* You can download the PDF document by clicking the link from the email. You will be redirected to the Linux Foundation's website. If the download doesn't start automatically, click **Proceed to Download**.\
  ![](../../../.gitbook/assets/proceed-to-download-icla.png)&#x20;
{% endhint %}

13\. Navigate to the Gerrit project, and start contributing.

{% hint style="warning" %}
**Important: **If the status on Git command line still shows "No contributor agreement" when you push the code change, you need to navigate to the Gerrit window, **sign out**, **sign in **again, and then push the code.

![](../../../.gitbook/assets/signout-gerrit.png)&#x20;
{% endhint %}

## GitLab

1. In GitLab, clone the repository you want to contribute to.
2. Make a changes, commit change and create a merge request.

{% hint style="info" %}
1. EasyCLA checks the CLA status of all committers involved in that commit. EasyCLA displays a cross or a check mark beside the name of each contributor who is involved in that commit based on their CLA status.
2. A cross next to a contributor's name means the EasyCLA check has failed, because the contributor is not authorized under a signed CLA.
{% endhint %}

![CLA Not Covered](<../../../.gitbook/assets/cla not covered.png>)

3\. Click![](../../../.gitbook/assets/lfx-easycla.png) or **Not Covered**.

4\. Click **Authorize LF-Engineering**. (Subsequent contributions will not require this authorization.)

​ ![](../../../.gitbook/assets/authorize-linux-foundation-easycla.png) ​

The CLA Contributor Console appears and shows the CLA group for your project.

{% hint style="info" %}
**Note:** If the project is not configured to use ICLAs, then **Proceed as an Individual Contributor** is inactive. In this case, individuals would not be able to contribute on their own behalf.
{% endhint %}

![CLA ICLA Flow](../../../.gitbook/assets/cla-icla-flow.png)

5\. Click **Proceed as an Individual Contributor**.\
![](../../../.gitbook/assets/preparing-cla.png)

6\. After the **CLA Ready For Signature** window appears, click **SIGN CLA**.

![CLA Ready for Signature](../../../.gitbook/assets/cla-ready-for-signature.png)

DocuSign presents the ICLA document for your signature.

![DocuSign](../../../.gitbook/assets/docusign-icla-flow.png)

7\. Select the checkbox and click **CONTINUE**. Follow the instructions in the DocuSign document, fill in the indicated fields, sign it, and click **FINISH**.

{% hint style="info" %}
**Result:**

* You will receive an email from The Linux Foundation, informing you that you have signed the ICLA.&#x20;
* You can download the PDF document by clicking the link from the email. You will be re-directed to the Linux Foundation's website. If the download doesn't start automatically, click **Proceed to Download**. ![](../../../.gitbook/assets/proceed-to-download-icla.png)&#x20;
{% endhint %}

You are redirected to GitLab. Wait a few seconds or refresh the page for the EasyCLA status to be updated. A check mark appears next to your branch.

![CLA Covered](<../../../.gitbook/assets/cla covered.png>)

8\. Ask someone with write access to the repository to merge your commit request.
