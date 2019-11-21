## What is EasyCLA?

_EasyCLA_ helps maintainers of open source projects streamline their workflows and reduce the hassle of managing Contributor License Agreements \(CLAs\) and authorizing contributors. By automating many of the manual processes, this open source solution hosted by the Linux Foundation reduces delays for developers to get authorized under a CLA.

## What is a CLA?

A _Contributor License Agreement_ \(CLA\) defines the terms under which intellectual property is contributed to a company or project. Typically, the intellectual property is software under an open source license. EasyCLA helps to ensure that contributions are not pulled into a project unless a CLA covering the contributor has been signed. CLAs typically fall into one of two categories:
* **Corporate Contributor License Agreement**

  If the company \(employer\) owns the contribution, a CCLA signatory signs a Corporate CLA. The Corporate CLA legally binds the corporation, so the agreement must be signed by a person with authority to enter into legal contracts on behalf of the corporation. A Corporate CLA may not remove the need for every employee \(developer\) to sign their own Individual CLA -- which separately covers contributions owned by the individual contributor -- if the project requires this.

* **Individual Contributor License Agreement**

  If as an individual you own the contribution, you sign the Individual CLA. A signed Individual CLA may be required before an individual's contribution can be merged into the project repository.

## How Does it Work?

This high-level diagram shows the different flows and roles that EasyCLA supports:

![CLA Diagram](imgs/cla_diagram_v8.png)

# EasyCLA Requirements

**Important:** Before you get started, make sure your project meets the EasyCLA requirements:

EasyCLA has the following requirements:

* \(Gerrit only\) Your project is hosted on the Linux Foundation platform
* Your project repositories are in GitHub or Gerrit
* You have a Linux Foundation identification and credentials. If you do not have a Linux Foundation identification \(LF ID\), go to [https://identity.linuxfoundation.org](https://identity.linuxfoundation.org) and complete the form to sign up.
* For Corporate CLAs, your company has a corporate authority role

As a repository administrator, enable Branch Restrictions and Branch Protection for your organizations in GitHub. Set the restrictions and protection to enable required status checks on a branch regardless of the role for the organization.

## What Role are You?

How you interact with EasyCLA depends on your role. EasyCLA supports the following roles in its workflow:

### Project Manager

You are a _project manager_ if you are the project maintainer who has responsibilities such as managing a project’s GitHub organization or Gerrit instance, members, repositories, and CLAs.

As the Project Manager, **fill out this pre-requisite form to provide the following information** : [Pre-requisite form for Project Manager](https://forms.gle/RuUgDKVg6m6Lj7LBA)

- Linux Foundation identification (LFID).
- Contact information.
- Project Details.
- Sample ICLA and CCLA template documents.

The CLA Administrator team will get back within a week. If you have any questions, contact the [CLA Support team](https://jira.linuxfoundation.org/servicedesk/customer/portal/4).
After the CLA administration team confirms your setup, you can sign in to the CLA Management Console to do the EasyCLA activities for project managers.

With EasyCLA, you do the following CLA set-up tasks:

1. Install the EasyCLA Application.
2. Add a CLA Group.
3. Add Contributor License Agreements).
4. Add GitHub repositories or Gerrit instances to enforce CLA monitoring.

### Corporate CLA Manager

You are a _Corporate CLA manager_ \(CCLA manager\) if you are the person authorized to manage the list of approved contributors under your company’s Corporate CLA.

As the CLA Manager or the CLA signatory, **Fill out this pre-requisite form to provide the following information** : [Pre-requisite form for CLA Manager](https://forms.gle/RiW8CVBxX7QTE9JQA) 

- Linux Foundation Identification (LFID)
- Project details
- Company details

The CLA Administrator team will get back within a week. If you have any questions, contact the [CLA Support team](https://jira.linuxfoundation.org/servicedesk/customer/portal/4).

Following are the CLA tasks after you Sign In to the CLA Corporate Console:

1. CLA manager: Add a Company to a Project.
1. CLA signatory: Sign a Corporate CLA on behalf of the company and Review and Sign a Corporate CLA by Request—this signatory has legal authority to sign documents on behalf of the company.
1. CLA manager: Whitelist Contributors—each whitelist applies to the project for which the company has signed a Corporate CLA.

### Contributor

You are a _contributor_ \(developer\) if you contribute code to GitHub or Gerrit projects. With EasyCLA, you will follow different workflows depending on whether the project is hosted on GitHub or Gerrit, and whether you contribute on behalf of a company or yourself as an individual:

* **GitHub company contributor**: confirm your association with a company that has a signed Corporate Contributor License Agreement.
* **GitHub individual contributor**: sign an Individual Contributor License Agreement.
* **Gerrit company contributor**: confirm your association with a company that has a signed Corporate Contributor License Agreement.
* **Gerrit individual contributor**: sign an Individual Contributor License Agreement.

### Corporate CLA Signatory

You are a _Corporate CLA signatory_ \(CCLA signatory\) if you are authorized to sign contracts, such as the project’s CLA, on behalf of the company. With EasyCLA, you can:

* Sign a Corporate CLA on behalf of the company - as a signatory you need to have legal authority to sign documents on behalf of the company.
* Review and sign a Corporate CLA by request.

The CLA Administrator team will get back within a week. If you have any questions, contact the [CLA Support team](https://jira.linuxfoundation.org/servicedesk/customer/portal/4).

