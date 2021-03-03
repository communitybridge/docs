# EasyCLA FAQs

**Who do I contact to enable my Linux Foundation-hosted project in order to use EasyCLA?**

Open [https://jira.linuxfoundation.org/plugins/servlet/theme/portal/4/create/143](https://jira.linuxfoundation.org/plugins/servlet/theme/portal/4/create/143), submit the form describing your requirements, and import your existing CLAs.

**Why does The Linux Foundation ask contributors of some projects to sign CLAs?**

Some project communities have elected to use CLAs as a required mechanism for code contributions. When a project community has decided to use a CLA, The Linux Foundation uses EasyCLA to help ensure that contributions to the project are made under a signed CLA, in accordance with the project's policies specified in its charter.

**What is the difference between a Corporate CLA (CCLA) and an Individual CLA (ICLA)?**

A CCLA governs code that is contributed behalf of the contributor's employer. A Corporate CLA should be signed by a person who is authorized to sign the CLA on behalf of the company. Each company or organization has its own processes to manage who is an authorized signatory, so you may need to check with your management or legal department if you are not sure who this should be.

After a CCLA is signed, the CLA Manager from that company is responsible for managing the approved list of authorized Contributors from that company.

Unlike a CCLA, an ICLA is signed by an individual for contributions that they make on their own behalf. Frequently this will be, for example, code that is written and contributed entirely on the individual's own time and unrelated to their employment.

If you are uncertain whether you should be contributing under a CCLA or an ICLA, you should consult your employer's legal department to discuss.

**Which CCLA approval criteria option has the lowest maintenance overhead?**

When a CLA Manager manages the list of authorized Contributors, EasyCLA provides several different types of "Approval Criteria" to do so. For example, a CLA Manager can specify only particular email addresses or GitHub / Gerrit usernames; or they can specify a domain name to authorize all email addresses under that domain.

Using the email address domain approval criteria typically requires less overhead, because the CLA Manager does not need to separately add and manage each contributing employee's email address.

**I contribute to an open source project on behalf of my employer. Do I need to sign anything?**

Probably not. If your company has previously signed a CCLA, then you will be guided to request that your CLA Manager add you to the list of authorized contributors (if you are not already on the list). After you are added, then you will simply confirm your association to the company during your code submission process the first time you contribute to the project.

However, if you are the first person from your company to contribute to a project, then your company will need to sign a CCLA. You may or may not be authorized to sign the CCLA yourself, or to manage the list of approved contributors as a CLA Manager after it is signed. You will likely want to check with your company's management or legal department to confirm who will be the CLA Manager and CLA Signatory for this project. After confirming this, the EasyCLA workflow will help guide you and your company through the signature process.

**When I am trying to contribute code under a CCLA, what should I do if my company is not listed?**

If your company is not listed after searching for it in the Contributor Console, then as part of the process you will need to create a record for your company as described [here](../contributors/corporate-contributor.md#if-the-select-company-dialog-appears-1).

**Do I need to be authorized under a CLA for each project to which I contribute?**

Yes, provided that the project has adopted a CLA as a required step for code contributions.

* If you are contributing as an individual, you must sign an ICLA for the project.
* If you are contributing as an employee of a company, your company's CLA Signatory must sign a CCLA, and then you must be authorized to contribute under it by your company's CLA Manager for that project.

**Do I have to sign a CLA every time I contribute code to a project?**

No, once a CLA check is cleared for the first contribution, you are free to contribute code to that project thereafter.

However, you may need to sign or be authorized under a separate CLA for other projects that require CLAs.

**What is the acceptable email format?**

A valid email address with an email prefix and an email domain, for example _abc@mail.com_ 

The allowed characters for email prefix are letters \(a-z\), numbers, underscores, periods, and dashes, and an underscore, period, or dash must be followed by one or more letter or number, for example:  
_abc-d@mail.com/abc.def@mail.com/abc@mail.com/abc\_def@mail.com_

The allowed characters for email domain are letters, numbers, dashes, and the last portion of the domain must be at least two characters, for example: _.com_, _.org_, _.cc_

