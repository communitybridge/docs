# Coordinate Signing CLA and become initial CLA Manager

Before a CCLA is signed, there is not yet an official "CLA Manager". Someone from the contributing company will be responsible for coordinating the CCLA signing process. That person will become the initial CLA Manager after it is signed.

This person (referred to internally in EasyCLA as the "CLA Manager Designee") can get designated as the initial CLA Manager either by starting the CCLA signing process themselves, or by being designated by another prospective contributor from their company who has started the EasyCLA CCLA process.

As the person who will become the initial CLA Manager, before starting the CCLA signing process, you will need to know the following before you proceed:

* Are you authorized to _sign_ the CCLA on behalf of your company?
* If you are not, what is the name and email address of someone who is authorized to sign?

You may need to consult with your management or legal department for guidance on the above questions.

## CCLA signing workflow

1\. [Sign in](../../v1-deprecated/cla-manager/sign-in-to-the-easycla-corporate-console.md) to the [EasyCLA corporate console](https://organization.lfx.linuxfoundation.org/company/dashboard).

2\. Select the project from the **Search** field, and click **EasyCLA** under the project name.\
**Note:** If a CCLA signature workflow is already in process for this project, you may be taken to the screen shown in step 5.

3\. Click **Start the CLA process**.

![Start the CLA Process](<../../../.gitbook/assets/start cla process.png>)

4\. Click an answer: **Are you authorized to be a CLA Manager for your organization?** &#x20;

![](<../../../.gitbook/assets/company has not signed cla (1).png>)&#x20;

* **Yes: **You _are_ going to be your company's initial CLA Manager. Continue to next step.
* **No: **[Designate someone else as the initial CLA Manager](broken-reference).** **

5\. Following screen appears. Under the **Action** column, click **Proceed with Signing**. &#x20;

![Proceed with Signing CLA](<../../../.gitbook/assets/proceed with signing.png>)

6\. Select an answer: **Are you authorized to sign CLAs on your company's behalf?** &#x20;

![](<../../../.gitbook/assets/identify cla signatory.png>)&#x20;

* **Yes: **Continue to next step.
* **No:** [Choose someone else to sign the CCLA](broken-reference).

7\. The **Review CCLA** window appears. Click **Review & Sign CCLA**.

![](<../../../.gitbook/assets/review ccla.png>)

8\. The **Preparing CCLA** window appears. After CCLA preparation is completed, click **Sign CCLA**.

![CCLA Ready for Signature](<../../../.gitbook/assets/ccla ready for signature.png>)

**Result:** You will be redirected to DocuSign to sign the CCLA.

9\. Select the check box to agree to use electronic signatures, and click **Continue**. Follow the instructions in the DocuSign document to fill in the required fields, sign the CCLA, and click **Finish**.

![](<../../../.gitbook/assets/docusign icla flow.png>)

**Result:** The CCLA is signed. You are now the CLA Manager from your company for this project. You will be redirected to the project page in the EasyCLA Corporate Console, and your name and email address will appear under **CLA Managers From My Organization**:

![CCLA signed successfully](<../../../.gitbook/assets/cla managers from my organization example.png>)

You will now be able to [approve contributors](../../v1-deprecated/cla-manager/approve-contributors.md) to contribute to the project, and to [add others as additional CLA Managers](broken-reference).

{% hint style="info" %}
* After signing the CCLA, you will receive an email from The Linux Foundation confirming that the CCLA is signed.
* You can download the signed PDF document by clicking the link from that email, where you will be redirected to The Linux Foundation's website. If the download doesn't start automatically, click **Proceed to Download**.  ![](<../../../.gitbook/assets/proceed to download ccla.png>)
* You can also download the signed CCLA at any time from within the EasyCLA Corporate Console.
{% endhint %}

## Designating someone else as initial CLA Manager <a href="designating-another-initial-cla-manager" id="designating-another-initial-cla-manager"></a>

If you clicked **No** in step 4 above, the **Identify CLA Manager** form appears:

![](<../../../.gitbook/assets/identify cla manager.png>)

Enter the name and email address of the person who should be the initial CLA Manager, and click **Submit Request**.

If you are not sure who is the initial CLA Manager, then click **Contact Company Admin**, which may let you reach out to your company's LFX administrative contact if your company has set someone up with this role, or reach out to your management or legal department for guidance.

{% hint style="info" %}
You should follow up with the specified person to confirm that they complete the CCLA signing process. They must have an [LF SSO](https://docs.linuxfoundation.org/lfx/sso) account to use the EasyCLA Corporate Console. If they don't have LF SSO account, they must [create one](https://docs.linuxfoundation.org/lfx/sso/create-an-account) before proceeding.
{% endhint %}

## Choosing someone else to sign the CCLA <a href="choosing-another-cla-signatory" id="choosing-another-cla-signatory"></a>

If you clicked **No** in step 6 above, the **Identify Authorized Signatory** form appears:

![](<../../../.gitbook/assets/identify authorized signatory.png>)

Enter the name and email address of the person who should sign the CCLA, and click **Send Signature Request Email**.

After the CCLA is signed, you will be designated as the CCLA manager, and you will be able to [approve contributors](../../v1-deprecated/cla-manager/approve-contributors.md).
