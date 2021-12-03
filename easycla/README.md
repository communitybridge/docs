# EasyCLA

## What is LFX EasyCLA? <a href="#what-is-easycla" id="what-is-easycla"></a>

_LFX EasyCLA_ streamlines the contribution process for open source projects that use [Contributor License Agreements (CLAs)](./#what-is-a-cla), by streamlining workflows for project maintainers, contributors, and organizations whose employees are contributing to the project. EasyCLA coordinates the process of getting CLAs signed and, for companies and other organizations, the process of authorizing employees to contribute under a signed CLA. By automating many of the manual processes, this open source solution hosted by The Linux Foundation reduces delays for developers to get authorized under a CLA.

&#x20;It is the only CLA management tool to correctly support both individual and corporate CLA workflows in an automated environment.

## What is a CLA? <a href="#what-is-a-cla" id="what-is-a-cla"></a>

Some projects use a _Contributor License Agreement_ (CLA) to define the terms under which content (such as source code or documentation) is contributed to the project.

Not all projects use CLAs; many use alternative contribution mechanisms, such as the [Developer Certificate of Origin](https://developercertificate.org) sign-off process. For those that do use CLAs, LFX EasyCLA helps to ensure that contributions are not merged into a project unless the contributors are covered under a signed CLA.

There are two types of CLAs:

*   **Corporate Contributor License Agreement (CCLA)**

    If a contribution is made on behalf of a company (typically the contributor's employer), then the contribution should be made under a CCLA. The CCLA must be signed by a person with authority to enter into legal contracts on behalf of the company, which often may not be the contributor themselves.

    After a company signs a CCLA, the company's [CLA Manager](v2-current/corporate-cla-managers/) will use the EasyCLA Corporate Console to manage the list of that company's authorized contributors to the project.
*   **Individual Contributor License Agreement (ICLA)**

    If a contributor owns the contribution themselves (typically a contribution they create on their own time), then the contribution should be made under an ICLA. The individual contributor would sign the ICLA before their contribution can be merged into the project repository.

For either a CCLA or an ICLA, after the contributor is authorized under a signed CLA, thereafter they will be able to contribute to that project without being blocked by the EasyCLA checks.

## How Does EasyCLA Work? <a href="#how-does-it-work" id="how-does-it-work"></a>

Following is a high-level diagram, showing the different flows and roles that EasyCLA supports:

![](https://files.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-MObJ9DOddapQNA8RbwE%2F-MObKQQDBwKU4CF3QhNd%2Fcla%20flow%20diagram.png?alt=media\&token=cc042063-32df-4ef9-9141-bd862a378567)

## Different Consoles of EasyCLA:

* [EasyCLA Project Console](https://projectadmin.lfx.linuxfoundation.org) for a project's director or manager (typically an LF staff member) to oversee the project's CLA setup. It is sometimes referred as the LFX Project Control Center in this documentation.
* [EasyCLA Contributor Console](https://github.com/communitybridge/easycla-contributor-console) for a contributor to a project to sign an Individual CLA (ICLA), or to start the corporate CLA (CCLA) signature process.
* [EasyCLA Corporate Console](https://organization.lfx.linuxfoundation.org) for a company's CLA Manager to coordinate the corporate CLA signature process, and then to manage their company's authorized contributors.

## Quick Help <a href="#quick-help" id="quick-help"></a>

For information about how to get started with contributing to a project that uses EasyCLA, please see Getting Started and our FAQs page.

For support questions, please see our Troubleshooting page or [file a support ticket](https://jira.linuxfoundation.org/plugins/servlet/theme/portal/4/create/143).
