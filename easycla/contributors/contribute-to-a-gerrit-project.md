# Contribute to a Gerrit Project

As an individual contributor or a corporate \(employee\) contributor or to an open source project, you submit changed code in Gerrit to inform reviewers about the changes:

* If any of your contributions to the project are created as part of your employment, the work may not belong to you—it may be owned by your employer. In that case, the CCLA signatory represents the employer \(company\) for legal reasons, and signs the Corporate Contributor Licensing Agreement in order for your contribution to be accepted into the company. During the code submission process, your CLA status is verified.

  When all CLA management set-up tasks are complete and your CCLA signatory has signed a Corporate CLA, you simply confirm your association to the company during your first code submission. Then, you can continue. Your subsequent contributions will not require association confirmations.

**To Contribute to Gerrit Project:**

1. In Gerrit, clone a repository under the Gerrit instance into your local machine.

2. Make a change and push the code to your Gerrit repository.

3. A warning link that you need to sign a CLA appears:

![CLA Gerrit Sign a CLA](../../.gitbook/assets/cla-gerrit-sign-a-cla.png)

4. Navigate to the Gerrit instance of your project. For example, if you are contributing to OPNFV project, navigate to [https://gerrit.opnfv.org](https://gerrit.opnfv.org/)​

5. Sign in using your [Single Sign-On \(SSO\)](../../sso/sign-in/) account.

6. Navigate to **Settings**— the gear icon on the upper right corner, and click **Agreements** from the menu on the left:

​![Settings Icon](../../.gitbook/assets/settings-icon.png)​    ​![Gerrit Agreements](../../.gitbook/assets/agreements.png)​

7. Click **New Contributor Agreement**.

![Agreement Link](../../.gitbook/assets/agreement-link.png)

8. New Contributor Agreement types appear:

![New Contributor Agreement](../../.gitbook/assets/new-contributor-agreement.png)

9. Continue to contribute as an individual or employee \(corporate contributor\):

* [Individual Contributor](contribute-to-a-gerrit-project.md#individual-contributor)
* [Corporate Contributor](contribute-to-a-gerrit-project.md#corporate-contributor)

## Individual Contributor <a id="individual-contributor"></a>

EasyCLA presents a review agreement link to individual contributors to open a CLA and sign it.

1. Select an individual CLA type.

![CLA Gerrit ICLA Type](../../.gitbook/assets/cla-gerrit-icla-type.png)

2. Click the **Please review the agreement link** and then click the message link that appears:

![CLA Gerrit ICLA Proceed to Sign CLA](../../.gitbook/assets/cla-gerrit-icla-proceed-to-sign-cla.png)

3. Sign in to EasyCLA if you are prompted.

4. Click **OPEN CLA** on the dialog that appears:  
DocuSign presents the agreement that you must sign. The Individual CLA is not tied to any employer you may have, so enter your @personal address in the E-Mail field.

![CLA Gerrit Individual CLA](../../.gitbook/assets/cla-gerrit-individual-cla-open-cla.png)

5. Follow the instructions in the DocuSign document, sign it, and click **FINISH**.

You are redirected to Gerrit. Wait a few seconds for the CLA status to update.

## Corporate Contributor <a id="corporate-contributor"></a>

EasyCLA presents a review agreement link where you confirm your association with the company.

1. Select **Corporate CLA**.

![Corporate CLA](../../.gitbook/assets/corporate-cla.png)

2. Click the **Please review the agreement link** and then click the message link that appears:

![](../../.gitbook/assets/cla-gerrit-icla-proceed-to-sign-cla.png)

3. Sign in to EasyCLA if you are prompted.

4. Select **Company**.  
**Note:** To contribute to this project, you must be authorized under a signed Contributor License Agreement. You are contributing on behalf of your work for a company.

5. Continue:

* [If a **Confirmation of Association with** statement appears](contribute-to-a-gerrit-project.md#if-a-confirmation-of-association-with-statement-appears)
* [If your company has not signed CCLA](contribute-to-a-gerrit-project.md#if-your-company-has-not-signed-ccla)
* [If you are not added to the approved list](contribute-to-a-gerrit-project.md#if-you-are-not-added-to-the-approved-list)
* [If Company is not in the list](contribute-to-a-gerrit-project.md#if-company-is-not-in-the-list)

## If a **Confirmation of Association with** statement appears <a id="if-a-confirmation-of-association-with-statement-appears"></a>

This message appears if you are added to the approved list, and your CLA doesn't require you to sign Individual CLA \(ICLA\). If the CLA is configured for you to sign ICLA, you will be re-directed to sign an Individual CLA, as shown in [step 4 of Individual Contributor](contribute-to-a-gerrit-project.md#individual-contributor).

1. Read the Confirmation of Association statement and select the checkbox.

![](../../.gitbook/assets/cla-github-confirmation-of-association%20%281%29.png)

2. Click **CONTINUE**.

A dialog appears and informs you: You are done!

![](../../.gitbook/assets/cla-github-you-are-done%20%281%29.png)

3. Click **RETURN TO REPO**.

You are redirected to Gerrit. Wait a few seconds for the CLA status to update or refresh the page.

## If your company has not signed CCLA

1. The **Verify Your Permission of Access** dialog appears.
2. Click an answer: Are You a CLA Manager?

   **YES**— You will be redirected to [corporate.lfcla.com](https://corporate.lfcla.com/#/companies) to [sign a CLA](../ccla-managers-and-ccla-signatories/sign-a-corporate-cla-on-behalf-of-the-company.md).

   **NO**— A **Request Access** form appears. Continue to next step.  
    ![](../../.gitbook/assets/request-access.png) 

3. Complete the form and click **SEND**.

   The CCLA manager signs a Corporate CLA and adds you to the approved list.

## If you are not added to the approved list

 You must be added to the approved list under a signed CCLA before you can contribute to the project.

**To contact your CLA manager to add you to the approved list:**

1. Click **CONTACT** under Contact the CLA Manager to be approved under their signed Corporate CLA.

![Contact CLA Manager](../../.gitbook/assets/contact-cla-manager.png)

2. Select an option, and complete the form.

3. Click **SEND**.  
A message appears informing you that the e-mail is sent successfully.

![](../../.gitbook/assets/contact-cla-manager-form.png)

{% hint style="info" %}
You will receive an email notification if the CLA manager approves or rejects your request to be approved as a corporate contributor for the company.
{% endhint %}

## If Company is not in the list <a id="if-company-is-not-in-the-list"></a>

If you don't find your company's name in the list:

1. Click **COMPANY NOT IN LIST? CLICK HERE**.

   The **Verify Your Permission of Access** dialog appears.

2. Click an answer: Are You a CLA Manager?

   **YES**— You will be redirected to [corporate.lfcla.com](https://corporate.lfcla.com/#/companies) to [add your company](../ccla-managers-and-ccla-signatories/add-a-company-to-a-project.md) to a project.

   **NO**— A **Request Access** form appears. Continue to next step.  
    ![](../../.gitbook/assets/request-access.png) 

3. Complete the form and click **SEND**.

   The CCLA manager signs a Corporate CLA and adds you to the approved list.

You have finished signing your CLA for this Gerrit instance. You are able to submit your changes to any repository under this Gerrit instance.

