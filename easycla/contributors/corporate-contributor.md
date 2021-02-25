# Corporate Contributor

As a corporate \(employee\) contributor, you are contributing code on company's behalf. When Corporate CLA is signed for the project, you confirm your association with the company during your first pull request or change submit. Your subsequent contributions will neither require association confirmations nor will they be gated by CLA check.

* [GitHub](corporate-contributor.md#github)
* [Gerrit](corporate-contributor.md#gerrit)

## GitHub

1. In GitHub, go to the repository that is linked to your project.

2. Make a change and create a pull request.

3. EasyCLA checks the CLA status of all committers involved in that pull request.

{% hint style="info" %}
1. EasyCLA marks a cross or a tick beside contributor names involved in that pull request based on their CLA status.
2. A cross next to your contributor name means the CLA check has failed.
{% endhint %}

![CLA Check Fail](../../.gitbook/assets/cla-github-individual-check-fail.png)

4. Click ![](../../.gitbook/assets/lfx-easycla.png) or **Please click here to be authorized**.

5. Click **Authorize LF-Engineering**. \(Subsequent contributions will not require authorization.\)

**Result:** The CLA Contributor Console appears in a new tab.

​ ![](../../.gitbook/assets/authorize-linux-foundation-easycla.png) ​

![CLA CCLA Flow](../../.gitbook/assets/cla-ccla-flow.png)

6. Click **Proceed as a Corporate Contributor**.

7. On **Select Organization** window, type organization name in the field, select the organization from the drop-down list, and click **Proceed**.

{% hint style="info" %}
**Note:**

* If your company is not in the list, you can add the company as described in [If Company is not in the list](corporate-contributor.md#if-the-select-company-dialog-appears-1).
{% endhint %}

![Select Organization](../../.gitbook/assets/select-organization.png)

8. You will need to complete one of the following workflows:

* [If you are not added to the approved list](corporate-contributor.md#if-you-are-not-added-to-the-approved-list)
* [If you are asked to sign ICLA](corporate-contributor.md#if-you-are-asked-to-sign-icla)
* [If Company has not signed CLA](corporate-contributor.md#if-the-select-company-dialog-appears)
* [If Company is not in the List](corporate-contributor.md#if-the-select-company-dialog-appears-1)

## Gerrit

1. In Gerrit, clone a repository under the Gerrit instance into your local machine.

2. Make a change and push the code to your Gerrit repository.

3. A warning link that you need to sign a CLA appears:

![CLA Gerrit Sign a CLA](../../.gitbook/assets/cla-gerrit-sign-a-cla.png)

4. Navigate to the Gerrit instance of your project. For example, if you are contributing to OPNFV project, navigate to [https://gerrit.opnfv.org](https://gerrit.opnfv.org/)​

5. Sign in using your LF [Single Sign-On \(SSO\)](https://docs.linuxfoundation.org/lfx/sso/create-an-account) account.

6. Navigate to **Settings**— the gear icon on the upper right corner, and click **Agreements** from the menu on the left:

​![Settings Icon](../../.gitbook/assets/settings-icon.png)​    ​![Gerrit Agreements](../../.gitbook/assets/agreements.png)​

7. Click **New Contributor Agreement**.

![Agreement Link](../../.gitbook/assets/agreement-link.png)

8. Click **Corporate CLA** , and then click **Please review the agreement** link.

![](../../.gitbook/assets/ccla-flow.png)

9. Click **Proceed To Corporate Authorization**.

![](../../.gitbook/assets/proceed-to-corporate-authorization.png)

10. You are redirected to Corporate CLA Console. Sign in with LF login name if prompted.

11. You will need to complete one of the following workflows:

* [If you are not added to the approved list](corporate-contributor.md#if-you-are-not-added-to-the-approved-list)
* [If you are asked to sign ICLA](corporate-contributor.md#if-you-are-asked-to-sign-icla)
* [If Company has not signed CLA](corporate-contributor.md#if-the-select-company-dialog-appears)
* [If Company is not in the List](corporate-contributor.md#if-the-select-company-dialog-appears-1)

## If you are not added to the approved list

If your company has signed CLA, but you are not added to the approved list, **Request Authorization to Contribute** window appears that shows the CLA manager\(s\) for your company.

1. Select CLA manager\(s\) from the drop-down list whom you want to request to authorizing you.  
**Note:** Clicking **Exit EasyCLA** cancels the CLA signing process.

![Request Authorization](../../.gitbook/assets/request-authorization.png)

2. Click **Request Authorization**.  
 ![](../../.gitbook/assets/request-submitted.png) 

3. Click **Exit EasyCLA**.

{% hint style="info" %}
* **GitHub Contributors:** After the CLA manager adds you to the approved list, you must [acknowledge company contribution](corporate-contributor.md#acknowledge-company-contribution) or[ sign ICLA](corporate-contributor.md#if-you-are-asked-to-sign-icla) if your CLA requires you to sign individual CLA before you can contribute code under the signed CLA.
* **Gerrit Contributors:** After the CLA manager adds you to the approved list, or you sign corporate CLA and become CLA manager but you still see **No Contributor Agreement** error, then sign out from Gerrit, sign in again, and then [follow the procedure](corporate-contributor.md#gerrit) again to submit the change.
{% endhint %}

## If you are asked to sign ICLA

1. If you are added to the approved list, but your CLA requires you to sign Individual CLA \(ICLA\),  then the following screen appears:  
 ![](../../.gitbook/assets/sign-icla-required.png) 

2. Click **Proceed**.

3. On **CLA Ready For Signature** window, click **SIGN CLA**.  
 ![](../../.gitbook/assets/cla-ready-for-signature.png) 

4. Follow the instructions in the DocuSign document, sign it, and click **FINISH**.  
**Note:** Ensure that the organization name is correct in the document before you sign.

{% hint style="info" %}
* **GitHub Contributors:** Navigate to the GitHub page. Wait a few seconds for the CLA status to be updated or refresh the page.
* **Gerrit Contributors:** If ****you still see **No Contributor Agreement** error, then sign out from Gerrit, sign in again, and then [follow the procedure](corporate-contributor.md#gerrit) again to submit the change.
{% endhint %}

## If Company has not signed CLA <a id="if-the-select-company-dialog-appears"></a>

If your company has not signed a CLA, **No Signed CLA Found** window appears.

![company has not signed cla](../../.gitbook/assets/company-has-not-signed-cla%20%281%29.png)

1. Click an answer: **Are you authorized to be a CLA Manager for your organization?**

* [Yes](corporate-contributor.md#yes-if-you-are-authorized) — You become the initial CLA manager after you sign CLA.
* [No](corporate-contributor.md#no-if-you-are-not-authorized) — Send request to the authorized person to sign CLA.

### **Yes \(If you  are authorized\)**

1. Click **Proceed** on the window that appears.

![Proceed to Sign with SSO Account](../../.gitbook/assets/proceed-to-sign-with-sso-account.png)

{% hint style="info" %}
**Note:** If you don't have a username \(LF SSO Account\) associated with Linux Foundation, you will be redirected to The Linux Foundation page to create a username.
{% endhint %}

2.  Click **Proceed** again.

![Redirecting to CLA Manager COnsole](../../.gitbook/assets/redirecting-to-cla-manager-console.png)

3. You will be redirected to corporate console to [sign a CLA](../corporate-cla-manager-designee-or-initial-cla-manager/sign-corporate-cla-for-a-company.md).

{% hint style="warning" %}
**Important:** After you sign the CLA, and want to contribute to the project, you must [add yourself to the approved list](../corporate-cla-managers/approve-and-manage-contributors.md#add-contributor-s), and [complete company acknowledgement](corporate-contributor.md#acknowledge-company-contribution) before you can contribute.
{% endhint %}

### **No \(If you are not authorized\)**

1. An **Identify CLA Manager** window appears.  
 ![](../../.gitbook/assets/identify-cla-manager%20%281%29.png) 

2. Complete the form, and click **Submit Request**, ****Or if you don't know email address of the CLA Manager of your company, click **Contact Company Admin**.

3. Click **Exit EasyCLA**.  
You can contribute after the authorized representative signs a corporate CLA, and adds you to the approved list.

{% hint style="info" %}
* **GitHub Contributors:** You will receive an email after you are added to the approved list. After you are added, you must [acknowledge the company contribution](corporate-contributor.md#acknowledge-company-contribution) and/or [sign ICLA](corporate-contributor.md#if-you-are-asked-to-sign-icla) if the CLA is configured for you to sign ICLA before you can contribute to the project.
* **Gerrit Contributors**: After the CLA manager adds you the approved list, if you still see **No Contributor Agreement** error, then sign out from Gerrit, sign in again, and then [follow the procedure](corporate-contributor.md#gerrit) again to submit the change.
{% endhint %}

## If Company is not in the List <a id="if-the-select-company-dialog-appears"></a>

1. Click **+Click Here** next to **Organization not listed?**

![company not listed](../../.gitbook/assets/company-not-listed.png)

2. ****Provide organization website URL, and organization name in the respective fields.  
**Note:** If the website URL is already associated with an organization, the organization name appears in the **Organization Name** field, and you cannot edit the name.

3. Click **Next**.

![Create New Organization](../../.gitbook/assets/create-new-organization.png)

4. Click an answer: **Are you authorized to be a CLA Manager for your organization?**

* **Yes:** Follow the procedure, and click **Proceed** to [sign corporate CLA](../corporate-cla-manager-designee-or-initial-cla-manager/sign-corporate-cla-for-a-company.md).
* **No:** Provide name and email address of the person whom you want to authorize as a CLA manager for your company, and click **Submit Request**.

## Acknowledge Company Contribution

After the CLA manager adds you to the approved list, you must acknowledge company contribution before you can contribute code under the signed CLA.

1. Navigate to the GitHub PR page.

2. Click **Not Covered**, and follow the procedure.

3. On **Select Organization** window, select the company, and click **Proceed**.

A window appears confirming your association with the company. Click Exit EasyCLA, and you will be redirected to GitHub page for the CLA status to be updated.  
 ![](../../.gitbook/assets/company-acknowledgement.png)

