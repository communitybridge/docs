# Getting Started

## What Role are You? <a href="what-role-are-you" id="what-role-are-you"></a>

How you interact with EasyCLA depends on your role. EasyCLA supports the following roles in its workflow:

* [Project Manager](getting-started.md#project-manager)
* [Contributor](getting-started.md#contributor)
* [CLA Manager](getting-started.md#cla-manager)
* [CLA Signatory](getting-started.md#cla-signatory)

When a CCLA is first being signed, the Contributor, CLA Manager, and CLA Signatory all might be the same person--or they might be different people. Each contributing company will determine for themselves which employees have these roles. Read below to understand these roles so that you can discuss with your company's management and legal counsel about who should be designated for each.

### Project Manager <a href="project-manager" id="project-manager"></a>

A _Project Manager_ is someone (typically project administrator or maintainer of the project) who is responsible for setting up the project's CLA templates and configuring the corresponding repositories in the [EasyCLA Project Console](https://projectadmin.lfx.linuxfoundation.org)** **(also called Project Control Center). For more details, see [Project Managers](v1-deprecated/project-managers/).

### Contributor <a href="contributor" id="contributor"></a>

A _Contributor_ is someone (typically a developer) who contributes code to a GitHub or Gerrit project that is set up on EasyCLA.

The specific workflow that a contributor follows will depend on:

* whether the project is hosted on GitHub or Gerrit; and
* whether they are contributing on behalf of themselves or a company (typically their employer). 

After submitting a contribution on GitHub or Gerrit, if a Contributor has not yet been authorized under a signed CLA, then their contribution will be initially blocked. They will use the EasyCLA Contributor Console to either:

* sign an ICLA (if contributing on their own behalf); or
* identify the company on whose behalf they are contributing, so that they can either be authorized under a signed CCLA or else start the CCLA signing process.

### CLA Manager

A _CLA Manager_ is someone who is authorized by a company to manage the list of authorized Contributors, and other CLA Managers, under that company’s CCLA for a project.

A CLA Manager uses the [EasyCLA Corporate Console](https://organization.lfx.linuxfoundation.org/company/dashboard) to:

* [Add Contributors to Approved List](v1-deprecated/cla-manager/approve-contributors.md)
* [Add or Delete CLA Managers](broken-reference)

When a CCLA is first being set up for signature, it will specify an "Initial CLA Manager". This person uses the EasyCLA Corporate Console to coordinate the signing of the CLA (see [CLA Signatory](v1-deprecated/getting-started/#cla-signatory) below).

After the CCLA is fully signed, then the specified Initial CLA Manager will be able to use the EasyCLA Corporate Console to manage the list of authorized Contributors. They can also designate additional CLA Managers.

By default, a CLA Manager is not automatically an authorized Contributor themselves, unless they add themselves to the authorized Contributor list.

### CLA Signatory <a href="cla-signatory" id="cla-signatory"></a>

A _CLA Signatory_ is someone who has been authorized by their company to sign a CCLA on its behalf.

If a company's CLA Signatory is the same as their Initial CLA Manager, then they will be redirected to sign the CCLA via the EasyCLA Corporate Console. If the CLA Signatory is a different person from the Initial CLA Manager, then the CLA Signatory will receive an email to review and sign the CCLA.

If you are authorized and receive an email request to sign contracts, then [review and sign the project’s CLA on behalf of the company](broken-reference).
