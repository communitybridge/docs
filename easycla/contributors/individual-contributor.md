# Individual Contributor

An individual contributor is one who contributes code on their own behalf \(and not on behalf of an employer\). If you are contributing code on behalf of your employer, please see the [Corporate Contributor](corporate-contributor.md) workflow.

Upon creating a pull request in GitHub or submitting changed code in Gerrit, EasyCLA will check whether the contributor is authorized under a signed CLA for that project. If they are not, and if they are contributing on their own behalf, then they must sign an ICLA.

* [GitHub](individual-contributor.md#github)
* [Gerrit](individual-contributor.md#gerrit)

## GitHub

1. In GitHub, go to the repository where you are contributing code.
2. Make a change and create a pull request.

{% hint style="info" %}
1. EasyCLA checks the CLA status of all committers involved in that pull request. EasyCLA displays a cross or a check mark beside the name of each contributor who is involved in that pull request based on their CLA status.
2. A cross next to a contributor's name means the EasyCLA check has failed, because the contributor is not authorized under a signed CLA.
{% endhint %}

![CLA Check Failed](../../.gitbook/assets/cla-github-individual-check-fail.png)

3. Click![](../../.gitbook/assets/lfx-easycla.png) or **Please click here to be authorized**.

4. Click **Authorize LF-Engineering**. \(Subsequent contributions will not require this authorization.\)

​ ![](../../.gitbook/assets/authorize-linux-foundation-easycla.png) ​

The CLA Contributor Console appears and shows the CLA group for your project.

{% hint style="info" %}
**Note:** If the project is not configured to use ICLAs, then **Proceed as an Individual Contributor** is inactive. In this case, individuals would not be able to contribute on their own behalf.
{% endhint %}

![CLA ICLA Flow](../../.gitbook/assets/cla-icla-flow.png)

5. Click **Proceed as an Individual Contributor**.  
![](../../.gitbook/assets/preparing-cla.png)

6. After the **CLA Ready For Signature** window appears, click **SIGN CLA**.

![CLA Ready for Signature](../../.gitbook/assets/cla-ready-for-signature.png)

DocuSign presents the ICLA document for your signature.

![DocuSign](../../.gitbook/assets/docusign-icla-flow.png)

7. Select the check box and click **CONTINUE**. Follow the instructions in the DocuSign document, fill in the indicated fields, sign it, and click **FINISH**.

{% hint style="info" %}
**Result:**

* You will receive an email from The Linux Foundation, informing you that you have signed the ICLA. 
* You can download the PDF document by clicking the link from the email. You will be re-directed to the Linux Foundation's website. If the download doesn't start automatically, click **Proceed to Download**. ![](../../.gitbook/assets/proceed-to-download-icla.png) 
{% endhint %}

You are redirected to GitHub. Wait a few seconds or refresh the page for the EasyCLA status to be updated. A check mark appears next to your branch.

![GitHub Individual Contributor Pass](../../.gitbook/assets/cla-github-individual-contributor-pass.png)

8. Click **Merge pull request** and confirm the merge.

## Gerrit

1. In Gerrit, clone a repository under the Gerrit instance into your local machine.
2. Make a change and push the code to your Gerrit repository.
3. A warning link that you need to sign a CLA appears:

![CLA Gerrit Sign a CLA](../../.gitbook/assets/cla-gerrit-sign-a-cla.png)

4. Navigate to the Gerrit instance of your project. For example, if you are contributing to the OPNFV project, navigate to [https://gerrit.opnfv.org](https://gerrit.opnfv.org/)​

5. Sign in using your LF [Single Sign-On \(SSO\)](https://docs.linuxfoundation.org/lfx/sso/create-an-account) account.

6. Navigate to **Settings**— the gear icon on the upper right corner— and click **Agreements** from the menu on the left:

​![Settings Icon](../../.gitbook/assets/settings-icon.png)​ ​![Gerrit Agreements](../../.gitbook/assets/agreements.png)​

7. Click **New Contributor Agreement**.

![Agreement Link](../../.gitbook/assets/agreement-link.png)

8. Select **Individual CLA \(ICLA\)**, and click **Please review the agreement**.

![ICLA User Flow](../../.gitbook/assets/icla-flow.png)

9. Click **Proceed To Individual Authorization**.

![Proceed to Individual Authorization](../../.gitbook/assets/proceed-to-individual-authorization.png)

10. Sign in if you are prompted, and you will be redirected to the Contributor Console.

11. After CLA preparation is completed, click **Sign CLA**.

![CLA Ready for Signature](../../.gitbook/assets/cla-ready-for-signature.png)

DocuSign presents the ICLA document for your signature.

![DocuSign](../../.gitbook/assets/docusign-icla-flow.png)

12. Select the check box and click **CONTINUE**. Follow the instructions in the DocuSign document, fill in the indicated fields, sign it, and click **FINISH**.

{% hint style="info" %}
**Result:**

* A message appears informing you that you have signed the ICLA.
* You will also receive an email from The Linux Foundation, informing you that you have signed the ICLA. 
* You can download the PDF document by clicking the link from the email. You will be redirected to the Linux Foundation's website. If the download doesn't start automatically, click **Proceed to Download**. ![](../../.gitbook/assets/proceed-to-download-icla.png) 
{% endhint %}

13. Navigate to the Gerrit project, and start contributing.

{% hint style="info" %}
**Note:** If you still see the EasyCLA status not updated, sign out from Gerrit and sign in again, and then follow the procedure again to submit the change.
{% endhint %}

