# EasyCLA

EasyCLA streamlines the management and execution of Contributor License Agreements \(CLAs\), to help projects ensure that contributions are made in accordance with project policies. It is the only CLA management tool to correctly support both individual and corporate CLA workflows in an automated environment.

## Quick Help <a id="quick-help"></a>

For information about how to get started with contributing to a project that uses EasyCLA, please see [Getting Started](getting-started/) and our [FAQs](getting-started/easycla-faqs.md) page.

For support questions, please see our [Troubleshooting page](getting-started/cla-troubleshooting/) or [file a support ticket](https://jira.linuxfoundation.org/plugins/servlet/theme/portal/4/create/143).

## EasyCLA Development

### Third-party Services

Besides integration with Auth0 and Salesforce, the EasyCLA system uses the following third party services:

* ​[Docusign](https://www.docusign.com/) for CLA agreement e-sign flow
* ​[Docraptor](https://docraptor.com/) for converting html CLA template to PDF file
* [GitHub](https://github.com/) for GitHub PR CLA authorization checking/gating
* Gerrit for CLA authorization review checking/gating
* Auth0 For Single Sign On
* Salesforce through the LFX Platform APIs

### EasyCLA Backend

The EasyCLA project has two backend components.

The majority of the backend APIs are implemented in python, and can be found in the [`cla-backend`](https://github.com/communitybridge/easycla/tree/master/cla-backend) directory.

Recent backend development was implemented in Golang, and can be found in the [`cla-backend-go`](https://github.com/communitybridge/easycla/tree/master/cla-backend-go) directory. In particular, this backend contains APIs powering Automated Templates, GitHub Approved List of contributors, and Duplicate Company handling in the Corporate Console.

### EasyCLA Frontend

EasyCLA frontend consists of three independent Single Page Application \(SPA\) built with [Ionic](https://ionicframework.com/) frameworks:

* [EasyCLA front-end project console](https://github.com/communitybridge/easycla/tree/master/cla-frontend-project-console) for the Linux Foundation director/admin/user to manage project CLA
* [EasyCLA front-end corporate console](https://github.com/communitybridge/easycla/tree/master/cla-frontend-corporate-console) for company CCLA manager to sign a CCLA and manage employee CLA approved list
* [EasyCLA front-end contributor console](https://github.com/communitybridge/easycla/tree/master/cla-frontend-contributor-console) for any project contributor to sign ICLA or CCLA

## EasyCLA Architecture <a id="easycla-architechture"></a>

The following diagram explains the EasyCLA architecture.

![EasyCLA Architecture](../.gitbook/assets/easycla-architecture-overview.png)

## EasyCLA Release Process <a id="easycla-release-process"></a>

The following diagram illustrates the EasyCLA release process:

![EasyCLA Release Process](../.gitbook/assets/easycla-software-development-and-release_process.png)

## License <a id="license"></a>

This project’s source code is licensed under the MIT License. A copy of the license is available in [LICENSE](https://github.com/communitybridge/easycla/blob/main/LICENSE).

The project includes source code from `keycloak`, which is licensed under the Apache License, version 2.0 \(Apache-2.0\), a copy of which is available in [LICENSE-keycloak](https://github.com/communitybridge/easycla/blob/main/LICENSE-keycloak).

This project’s documentation is licensed under the Creative Commons Attribution 4.0 International License \(CC-BY-4.0\). A copy of the license is available in [LICENSE-docs](https://github.com/communitybridge/easycla/blob/main/LICENSE-docs).

