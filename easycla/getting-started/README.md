# Getting Started

## What is LFX EasyCLA? <a id="what-is-easycla"></a>

_LFX EasyCLA_ helps streamline the contribution process for open source projects that use Contributor License Agreements \(CLAs\), by streamlining workflows for project maintainers, contributors, and organizations whose employees are contributing to the project. EasyCLA coordinates the process of getting CLAs signed and, for companies and other organizations, the process of authorizing employees to contribute under a signed CLA. By automating many of the manual processes, this open source solution hosted by The Linux Foundation reduces delays for developers to get authorized under a CLA.

## What is a CLA? <a id="what-is-a-cla"></a>

Some projects use a _Contributor License Agreement_ \(CLA\) to define the terms under which content \(such as source code or documentation\) is contributed to the project.

Not all projects use CLAs; many use alternative contribution mechanisms, such as the [Developer Certificate of Origin](https://developercertificate.org/) sign-off process. For those that do use CLAs, LFX EasyCLA helps to ensure that contributions are not merged into a project unless the contributors are covered under a signed CLA.

There are two types of CLAs:

* **Corporate Contributor License Agreement \(CCLA\)**

  If a contribution is made on behalf of a company \(typically the contributor's employer\), then the contribution should be made under a CCLA. The CCLA must be signed by a person with authority to enter into legal contracts on behalf of the company, which often may not be the contributor themselves.

  After a company signs a CCLA, the company's [CLA Manager](./#cla-manager) will use the EasyCLA Corporate Console to manage the list of that company's authorized contributors to the project.

* **Individual Contributor License Agreement \(ICLA\)**

  If a contributor owns the contribution themselves \(typically a contribution they create on their own time\), then the contribution should be made under an ICLA. The individual contributor would sign the ICLA before their contribution can be merged into the project repository.

For either a CCLA or an ICLA, after the contributor is authorized under a signed CLA, thereafter they will be able to contribute to that project without being blocked by the EasyCLA checks.

## How Does it Work? <a id="how-does-it-work"></a>

This high-level diagram shows the different flows and roles that EasyCLA supports:

![EasyCLA Flow Diagram](../../.gitbook/assets/cla-flow-diagram.png)

## What Role are You? <a id="what-role-are-you"></a>

How you interact with EasyCLA depends on your role. EasyCLA supports the following roles in its workflow:

* [Project Manager](./#project-manager)
* [Contributor](./#contributor)
* [CLA Manager](./#cla-manager)
* [CLA Signatory](./#cla-signatory)

When a CCLA is first being signed, the Contributor, CLA Manager, and CLA Signatory all might be the same person--or they might be different people. Each contributing company will determine for themselves which employees have these roles. Read below to understand these roles so that you can discuss with your company's management and legal counsel about who should be designated for each.

### Project Manager <a id="project-manager"></a>

A _Project Manager_ is responsible for setting up the project's CLA templates and configuring the corresponding repositories in the [EasyCLA Project Console](https://projectadmin.lfx.linuxfoundation.org/) ****\(also called Project Control Center\). For more details, see [Project Managers](../project-managers/).

### Contributor <a id="contributor"></a>

A _Contributor_ is someone \(typically a developer\) who contributes code to a GitHub or Gerrit project that is set up on EasyCLA.

The specific workflow that a contributor follows will depend on:

* whether the project is hosted on GitHub or Gerrit; and
* whether they are contributing on behalf of themselves or a company \(typically their employer\). 

After submitting a contribution on GitHub or Gerrit, if a Contributor has not yet been authorized under a signed CLA, then their contribution will be initially blocked. They will use the EasyCLA Contributor Console to either:

* sign an ICLA \(if contributing on their own behalf\); or
* identify the company on whose behalf they are contributing, so that they can either be authorized under a signed CCLA or else start the CCLA signing process.

### CLA Manager

A _CLA Manager_ is someone who is authorized by a company to manage the list of authorized Contributors, and other CLA Managers, under that company’s CCLA for a project.

A CLA Manager uses the [EasyCLA Corporate Console](https://organization.lfx.linuxfoundation.org/company/dashboard) to:

* [Add Contributors to Approved List](../corporate-cla-managers/approve-and-manage-contributors.md)
* [Add or Delete CLA Managers](../corporate-cla-managers/add-or-delete-cla-managers.md)

When a CCLA is first being set up for signature, it will specify an "Initial CLA Manager". This person uses the EasyCLA Corporate Console to coordinate the signing of the CLA \(see [CLA Signatory](./#cla-signatory) below\).

After the CCLA is fully signed, then the specified Initial CLA Manager will be able to use the EasyCLA Corporate Console to manage the list of authorized Contributors. They can also designate additional CLA Managers.

By default, a CLA Manager is not automatically an authorized Contributor themselves, unless they add themselves to the authorized Contributor list.

### CLA Signatory <a id="cla-signatory"></a>

A _CLA Signatory_ is someone who has been authorized by their company to sign a CCLA on its behalf.

If a company's CLA Signatory is the same as their Initial CLA Manager, then they will be redirected to sign the CCLA via the EasyCLA Corporate Console. If the CLA Signatory is a different person from the Initial CLA Manager, then the CLA Signatory will receive an email to review and sign the CCLA.

If you are authorized and receive an email request to sign contracts, then [review and sign the project’s CLA on behalf of the company](../corporate-cla-signatories/review-and-sign-a-corporate-cla-by-request.md).

