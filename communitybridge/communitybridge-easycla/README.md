# CommunityBridge EasyCLA

​[​![CircleCI](https://circleci.com/gh/communitybridge/easycla.svg?style=svg)​](https://circleci.com/gh/communitybridge/easycla)​

The Contributor License Agreement \(CLA\) service of the Linux Foundation lets project contributors read, sign, and submit contributor license agreements easily.

This repository contains both the backend and front-end UI for supporting and managing the application.

This platform supports both GitHub and Gerrit source code repositories. Additional information can be found in the [Getting Started Guide](getting-started/).

## Third-party Services <a id="third-party-services"></a>

​[EasyCLA​](./#easycla-architechture)

Besides integration with Auth0 and Salesforce, the CLA system has the following third party services:

* ​[Docusign](https://www.docusign.com/) for CLA agreement e-sign flow
* ​[Docraptor](https://docraptor.com/) for convert html CLA template as PDF file

## CLA Backend <a id="cla-backend"></a>

The CLA project has two backend projects.

The majority of the backend APIs are implemented in python, and can be found in the [`cla-backend`](https://github.com/communitybridge/easycla/tree/master/cla-backend) directory.

Recent backend development was implemented in Golang, and can be found in the [`cla-backend-go`](https://github.com/communitybridge/easycla/tree/master/cla-backend-go) directory. In particular, this backend contains APIs powering Automated Templates, GitHub Approved List of contributors, and Duplicate Company handling in the Corporate Console.

## CLA Frontend <a id="cla-frontend"></a>

### Overview <a id="overview"></a>

CLA frontend consists of three independent SPA build with [Ionic](https://ionicframework.com/) framework:

* [CLA front-end project console](https://github.com/communitybridge/easycla/tree/master/cla-frontend-project-console) for LinuxFoundation director/admin/user to manage project CLA
* [CLA front-end corporate console](https://github.com/communitybridge/easycla/tree/master/cla-frontend-corporate-console) for company CCLA manager to sign a CCLA and manage employee CLA approved list
* [CLA front-end contributor console](https://github.com/communitybridge/easycla/tree/master/cla-frontend-contributor-console) for any project contributor to sign ICLA or CCLA

## EasyCLA Architechture <a id="easycla-architechture"></a>

The following diagram explains the EasyCLA architecture.

![EasyCLA Architecture](../../.gitbook/assets/cla-architecture-overview.png)

## EasyCLA Release Process <a id="easycla-release-process"></a>

The following diagram illustrates the EasyCLA release process:

![EasyCLA Release Process](../../.gitbook/assets/easycla-software-development-and-release_process.png)

## License <a id="license"></a>

Copyright The Linux Foundation and each contributor to CommunityBridge.

This project’s source code is licensed under the MIT License. A copy of the license is available in LICENSE.

The project includes source code from `keycloak`, which is licensed under the Apache License, version 2.0 \(Apache-2.0\), a copy of which is available in LICENSE-keycloak.

This project’s documentation is licensed under the Creative Commons Attribution 4.0 International License \(CC-BY-4.0\). A copy of the license is available in LICENSE-docs.

