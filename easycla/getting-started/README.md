# Getting Started

## What is LFX EasyCLA? <a id="what-is-easycla"></a>

_LFX EasyCLA_ helps maintainers of open source projects streamline their workflows, reduce the hassle of managing Contributor License Agreements \(CLAs\) and authorizing contributors. By automating many of the manual processes, this open source solution hosted by the Linux Foundation reduces delays for developers to get authorized under a CLA.

## What is a CLA? <a id="what-is-a-cla"></a>

A _Contributor License Agreement_ \(CLA\) defines the terms under which intellectual property is contributed to a company or project. Typically, the intellectual property is software under an open source license. LFX EasyCLA helps to ensure that contributions are not pulled into a project unless a CLA covering the contributor has been signed. CLAs typically fall into one of two categories:

* **Corporate Contributor License Agreement \(CCLA\)**

  If the company \(employer\) owns the contribution, a CCLA signatory signs a Corporate CLA. The Corporate CLA legally binds the corporation, so the agreement must be signed by a person with authority to enter into legal contracts on behalf of the corporation. A Corporate CLA may require every employee \(developer\) to sign their own Individual CLA -- which separately covers contributions owned by the individual contributor -- if the project requires this.

* **Individual Contributor License Agreement \(ICLA\)**

  If as an individual you own the contribution, you sign the Individual CLA. A signed Individual CLA may be required before an individual's contribution can be merged into the project repository.

## How Does it Work? <a id="how-does-it-work"></a>

This high-level diagram shows the different flows and roles that EasyCLA supports:

![EasyCLA Flow Diagram](../../.gitbook/assets/cla-flow-diagram.png)

## What Role are You? <a id="what-role-are-you"></a>

How you interact with EasyCLA depends on your role. EasyCLA supports the following roles in its workflow:

* [Project Manager](./#project-manager)
* [Contributor](./#contributor)
* [Corporate CLA Manager](./#corporate-cla-manager)
* [Corporate CLA Manager Designee](./#corporate-cla-manager-designee)
* [Corporate CLA Signatory](./#corporate-cla-signatory)

### Project Manager <a id="project-manager"></a>

You are a _project manager_  or _project admin_ if you are authorized by The Linux Foundation to maintain project\(s\). You use the project console, also referred as Project Control Center, where you have access to specific projects as per permissions provided by The Linux Foundation, and perform project related activities. ****For details, see [Project Managers](../project-managers/).

### Contributor <a id="contributor"></a>

You are a _contributor_ \(developer\) if you contribute code to GitHub or Gerrit projects. With LFX EasyCLA, you will follow different workflows depending on whether the project is hosted on GitHub or Gerrit, and whether you contribute on behalf of a company or yourself as an individual. As [individual](../contributors/individual-contributor.md) and [corporate contributors](../contributors/corporate-contributor.md), you use LFX contributor console to you sign CLA or confirm your association with company before you can contribute code.

### Corporate CLA Manager

You are a _Corporate CLA manager_ \(CCLA manager\) if you are authorized to manage the list of approved contributors under your company’s corporate CLA. There can be one or more CLA managers for a company. You use corporate CLA console to:

* [Add Contributors to Approved List](../corporate-cla-managers/approve-and-manage-contributors.md)
* [Add or Delete CLA Managers](../corporate-cla-managers/add-or-delete-cla-managers.md)

### Corporate CLA Manager Designee

You are a _Corporate CLA Manager Designee_ \(CCLA manager designee\) if there are no existing CLA manager for a company, and you are the first person to sign a Corporate CLA for a project. You use corporate CLA console to sign CLA. For details, see [Corporate CLA Manager Designee or Initial CLA Manager](../corporate-cla-manager-designee-or-initial-cla-manager/).

You become a CLA manager designee:

* When you receive an email informing you that you are identified as a CLA manager for a project. You must have an LF login to sign the CLA.
* When you are authorized to [sign CLA](../corporate-cla-manager-designee-or-initial-cla-manager/sign-corporate-cla-for-a-company.md) for a company as an initial CLA manager. After you sign CLA, you become [CLA manager](../corporate-cla-managers/). 

### Corporate CLA Signatory <a id="corporate-cla-signatory"></a>

A _Corporate CLA signatory_ \(CCLA signatory\) is a person with legal authority to sign documents on behalf of the company. If you are authorized and receive an email notification to sign contracts, then [review and sign the project’s CLA on behalf of the company](../corporate-cla-signatories/review-and-sign-a-corporate-cla-by-request.md).

