# EasyCLA Development Components

Following are the third-party services, backend components and frontend consoles used in the development of the EasyCLA tool.

### Third-party Services <a href="#third-party-services" id="third-party-services"></a>

Besides integration with the LFX platform and its underlying services, EasyCLA uses the following third party services:

* ​[Docusign](https://www.docusign.com) for the CLA agreement e-sign flow
* ​[Docraptor](https://docraptor.com) for converting CLA templates from HTML to PDF
* ​[GitHub](https://github.com) for GitHub PR CLA authorization checking/gating
* Gerrit for CLA authorization review checking/gating
* Auth0 For Single Sign On
* Salesforce through the LFX Platform APIs
* ​[GitLab](https://gitlab.com) supports two ways of registering your EasyCLA bot with GitLab :
  * **Integrations**: Navigate to **Integrations** tab of Project Settings. To have your EasyCLA bot listed under _Add an integration_ section, you must create a MR (Merge Request) to GitLab's codebase, and get that accepted. The code must be written in Ruby.
  * **Webhook :** The other way of integrating your bot with GitLab is to add a webhook which will be called on certain events that happen in GitLab Project, such as opening MR (Merge Request). The webhook must respond in certain time frame. GitLab has a [Webhook API](https://docs.gitlab.com/ce/api/projects.html#add-project-hook) where you can interact with programmatically and add/edit/delete your webhook which can make the integration smoother from user point of view.

### EasyCLA Backend <a href="#cla-backend" id="cla-backend"></a>

The EasyCLA tool has two backend components.

* Python - some older APIs are implemented in python and can be found in the [cla-backend](https://github.com/communitybridge/easycla/tree/main/cla-backend) directory.
* GoLang - Most of the backend development is implemented in Golang, and can be found in the [cla-backend-go](https://github.com/communitybridge/easycla/tree/main/cla-backend-go) directory. In particular, this backend contains APIs powering most of the v2 APIs which integrate with the LFX Platform (including Salesforce data), and the LFX platform permissions model.

### EasyCLA Frontend or Consoles <a href="#easycla-frontend-or-consoles" id="easycla-frontend-or-consoles"></a>

The EasyCLA frontend consists of three independent Single Page Applications (SPAs) built with the [Ionic](https://ionicframework.com) framework:

* ​[EasyCLA Project Console](https://projectadmin.lfx.linuxfoundation.org) for a project's director or manager (typically an LF staff member) to oversee the project's CLA setup. It is sometimes referred as the LFX Project Control Center in this documentation.
* ​[EasyCLA Contributor Console](https://github.com/communitybridge/easycla-contributor-console) for a contributor to a project to sign an Individual CLA (ICLA), or to kick off the corporate CLA (CCLA) signature process.
* ​[EasyCLA Corporate Console](https://organization.lfx.linuxfoundation.org) for a company's CLA Manager to coordinate the corporate CLA signature process, and then to manage their company's authorized contributors.

### License <a href="#license" id="license"></a>

This project’s source code is licensed under the MIT License. A copy of the license is available in [LICENSE](https://github.com/communitybridge/easycla/blob/main/LICENSE).The project includes source code from `keycloak`, which is licensed under the Apache License, version 2.0 (Apache-2.0), a copy of which is available in [LICENSE-keycloak](https://github.com/communitybridge/easycla/blob/main/LICENSE-keycloak).This project’s documentation is licensed under the Creative Commons Attribution 4.0 International License (CC-BY-4.0). A copy of the license is available in [LICENSE-docs](https://github.com/communitybridge/easycla/blob/main/LICENSE-docs).

## EasyCLA Architecture <a href="#easycla-architecture" id="easycla-architecture"></a>

The following diagram illustrates EasyCLA architecture:

![EasyCLA Architecture Overview](https://files.gitbook.com/v0/b/gitbook-legacy-files/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-MOb5j37wjwk61u\_ukKN%2F-MObHlodbcm0W1MV1whk%2Feasycla-architecture-overview.png?alt=media\&token=b6733d43-464d-4e42-b896-3ceccde87f42)

## EasyCLA Release Process <a href="#easycla-release-process" id="easycla-release-process"></a>

The following diagram illustrates the EasyCLA release process:

![EasyCLA Release Process](https://files.gitbook.com/v0/b/gitbook-legacy-files/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-M6cYV0z4DSsvgtt1MtI%2F-M6c\_728flGfhAMw3L5V%2Feasycla-software-development-and-release\_process.png?alt=media\&token=460da65a-6214-4139-aebe-aa85db69a26f)
