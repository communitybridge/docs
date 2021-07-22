# LFX Security FAQs

## What is LFX Security? <a id="VulnerabilityDetectionFAQs-WhatisCommunityBridgeVulnerabilityDetection?"></a>

LFX Security \(earlier  called as Vulnerability Detection\) is a service that helps the open source developers identify and remediate security vulnerabilities in order to create more secure code. Projects that are part of the Linux Foundation database receive free weekly scans via the LFX Security service in order to detect vulnerabilities in code repositories. A public dashboard gives developers visibility into open security issues and paths to remediation.

## Does LFX Security automatically scan my project’s code? <a id="VulnerabilityDetectionFAQs-DoesCommunityBridgeautomaticallyscanmyproject&#x2019;scode?"></a>

Yes, if your project is set up on  Linux Foundation database, then LFX Security automatically scans your code on a weekly basis, and adds any detected vulnerabilities to your project dashboards. Issues are classified as high, medium, or low risk based on information in databases including CVE and CWE. An inventory of your project’s detected dependencies and licenses is mapped along with the dependency details.

## Who can see Vulnerability reports?

Only maintainers and contributors can see details of a vulnerability scan. However, because these projects are on public repositories, anyone can see the vulnerability summary that shows the total number of issues. 

## What languages and programming ecosystems are supported for scanning? <a id="VulnerabilityDetectionFAQs-Whatlanguagesandprogrammingecosystemsaresupportedforscanning?"></a>

Dependency and vulnerability scanning is currently supported for JavaScript, Node.js \(npm\), Java, Scala, Ruby, Python, Golang, and PHP. 

## How are licenses identified? <a id="VulnerabilityDetectionFAQs-Howarelicensesidentified?"></a>

LFX Security uses Snyk to scan a project’s Git-based repository and identifies dependencies’ licenses against the SPDX license list. License identification varies by ecosystem, but generally it is produced via a combination of the stated license on the package, retrieving metadata from the registry, and license information in manifest files.

## What partners support the LFX Security service? <a id="VulnerabilityDetectionFAQs-WhatpartnerssupporttheCommunityBridgeVulnerabilityDetectionservice?"></a>

For LFX Security, we are partnering with a few solutions providers where it makes sense. For example, projects can choose to allocate funds raised through the LFX Funding service to administer bug bounty programs through a partnership with HackerOne. Snyk provides daily vulnerability scanning for all projects on LFX \(Funding and Mentorship\) to identify vulnerabilities and dependencies — and to help manage Internet Protocol \(IP\) risk with license verification.

## How does LFX help a project manage its intellectual property obligations? <a id="VulnerabilityDetectionFAQs-HowdoesCommunityBridgehelpaprojectmanageitsintellectualpropertyobligations?"></a>

Firstly all projects in LFX automatically get dependency license scans. LFX provides a project and its maintainers with visibility into the full tree of direct and indirect third-party dependencies that Snyk detects as leveraged by the project, along with reporting the licenses Snyk associates with those dependencies. Scan report provides a project's maintainer complete list of direct and indirect third-party dependencies affecting their project. Scan report also finds out licenses associated with those third-party dependencies. This reporting gives maintainers a simple, lightweight and zero-effort view into the array of third-party licenses that their project relies upon. It helps enable projects to make determinations about whether to avoid particular dependencies — for example, if their licenses might be incompatible with the project’s own license, IP policies and community objectives. It also helps projects identify their compliance obligations for the dependencies they use — for example, which license notices they need to reproduce when they distribute those dependencies.

Secondly, the Linux Foundation’s new EasyCLA \(Contributor License Agreement\) service tackles the difficult problem of ensuring that Contributor's assign IP rights on their source code to opensource projects. The new EasyCLA  service also handles corporate authority considerations by requiring corporate EasyCLA  to be signed by an authorized signatory of a company. It enables companies to control which of their employees are authorized to contribute to which projects under the signed EasyCLA . Depending on their own needs and processes, companies can take a fine-grained approach by specifying individual authorized contributors’ email addresses, or can easily authorize all employees across a domain name. The EasyCLA service facilitates all these workflows and ensures that code contributions can only be accepted after the contributor satisfies the EasyCLA requirements. Although the EasyCLA service is initially available to Linux Foundation-hosted projects, we hope to make it available to a broader set of projects, including those on LFX.

## When is the license information displayed as "Unknow"? <a id="VulnerabilityDetectionFAQs-HowdoesCommunityBridgehelpaprojectmanageitsintellectualpropertyobligations?"></a>

The license information is displayed as "Unknown"  when **License** field is **Unknown**. The Snyk API returns this information and the license information is displayed as "**Unknown"**.

## When is the license information displayed as empty without any license information? <a id="VulnerabilityDetectionFAQs-HowdoesCommunityBridgehelpaprojectmanageitsintellectualpropertyobligations?"></a>

The license information is displayed as empty when **License** field is blank with out having any license information. The Snyk API will be unable to find any information related to the license and the license information is displayed as empty.

