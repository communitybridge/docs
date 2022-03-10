# LFX Security FAQs

## What is LFX Security? <a href="#vulnerabilitydetectionfaqs-whatiscommunitybridgevulnerabilitydetection" id="vulnerabilitydetectionfaqs-whatiscommunitybridgevulnerabilitydetection"></a>

LFX Security is a service that helps the open source developers identify and remediate security vulnerabilities in order to create more secure code. LFX security also detects code secrets and non inclusive language in your code. Projects that are part of the Linux Foundation database receive free weekly scans via the LFX Security service in order to detect vulnerabilities in code repositories. A public dashboard gives developers visibility into open security issues and paths to remediation.

## Does LFX Security automatically scan my project’s code? <a href="#vulnerabilitydetectionfaqs-doescommunitybridgeautomaticallyscanmyprojectscode" id="vulnerabilitydetectionfaqs-doescommunitybridgeautomaticallyscanmyprojectscode"></a>

Yes, if your project is set up on Linux Foundation database, then LFX Security automatically scans your code on a weekly basis, and adds any detected vulnerabilities to your project dashboards. Issues are classified as critical, high, medium, or low risk based on information in databases including  Common _Weakness_ Enumeration (CVE), Common _Vulnerabilities_ and Exposures (CWE) GitHub Advisory Database (GHSA). An inventory of your project’s detected dependencies and licenses is mapped along with the dependency details. LFX Security also scans for code secrets and non inclusive language.&#x20;

## What do Critical/High/Medium/Low Vulnerabilities mean?

To understand more on this, please refer this link [NVD](https://nvd.nist.gov/vuln-metrics/cvss).&#x20;

## Who can see LFX Security  reports?

LFX Security fetches the permissions from GitHub and maps those permissions into the following categories:&#x20;

* Owner/Admin -> GitHub admin permissions
* Maintainer -> GitHub maintain permissions&#x20;
* Contributor -> GitHub triage, push, pull permissions.&#x20;

These users are given elevated Contributor/Maintainer permission. They can dismiss irrelevant vulnerability issues, send notifications and mark issues as false positive.

## What languages and programming ecosystems are supported for vulnerability scanning? <a href="#vulnerabilitydetectionfaqs-whatlanguagesandprogrammingecosystemsaresupportedforscanning" id="vulnerabilitydetectionfaqs-whatlanguagesandprogrammingecosystemsaresupportedforscanning"></a>

Dependency and vulnerability scanning is currently supported for JavaScript, Node.js (npm), Java, Scala, Ruby, Python, Golang, and PHP.

## Why is there a mismatch between "Vulnerabilities Fixed" and "Top 10 projects most active in fixing vulnerabilities"? <a href="#vulnerabilitydetectionfaqs-howarelicensesidentified" id="vulnerabilitydetectionfaqs-howarelicensesidentified"></a>

On the Security Leaderboard, you can see "Vulnerabilities Fixed" count and "Top 10 projects most active in fixing vulnerabilities" count. In general, both counts should match.&#x20;

"Vulnerabilities Fixed" value is a count of distinct (or unique) vulnerabilities found in all the projects that were scanned.

"Top 10 projects most active in fixing vulnerabilities" value is the total count of distinct or unique vulnerabilities in that particular project.&#x20;

For example, if the "Vulnerabilities Fixed" count is 100, the "Top 10 projects most active in fixing vulnerabilities" when added should be 100. But on the Security Leaderboard, the "Top 10 projects most active in fixing vulnerabilities" count is always higher then "Vulnerabilities Fixed".&#x20;

The reason behind this mismatch is repetition of vulnerabilities in other projects. These repeated vulnerabilities will lead to higher aggregate count when compared with distinct "Vulnerabilities Fixed" count.

## How are licenses identified? <a href="#vulnerabilitydetectionfaqs-howarelicensesidentified" id="vulnerabilitydetectionfaqs-howarelicensesidentified"></a>

LFX Security uses Snyk to scan a project’s Git-based repository and identifies dependencies’ licenses against the SPDX license list. License identification varies by ecosystem, but generally it is done by reviewing stated license on the package, retrieving metadata from the registry, and license information in manifest files.

## What partners support the LFX Security service? <a href="#vulnerabilitydetectionfaqs-whatpartnerssupportthecommunitybridgevulnerabilitydetectionservice" id="vulnerabilitydetectionfaqs-whatpartnerssupportthecommunitybridgevulnerabilitydetectionservice"></a>

For LFX Security, we are partnering with a few solutions providers where it makes sense. For example, projects can choose to allocate funds raised through the LFX Funding service to administer bug bounty programs through a partnership with HackerOne. \
\
Snyk provides daily vulnerability scanning for all projects on LFX (Funding and Mentorship) to identify vulnerabilities and dependencies — and to help manage Internet Protocol (IP) risk with license verification.\
\
BluBracket scans the code for code secrets and non inclusive language.&#x20;

## How does LFX Security help a project manage its intellectual property obligations? <a href="#vulnerabilitydetectionfaqs-howdoescommunitybridgehelpaprojectmanageitsintellectualpropertyobligation" id="vulnerabilitydetectionfaqs-howdoescommunitybridgehelpaprojectmanageitsintellectualpropertyobligation"></a>

Firstly all projects in LFX Security automatically get dependency license scans. LFX Security  provides a project and its maintainers with visibility into the full tree of direct and indirect third-party dependencies that Snyk detects for that leveraged by the project. Snyk also associates licenses with libraries and packages that are using those licenses in dependency tree. This reporting gives maintainers a simple, lightweight and zero-effort view into the array of third-party licenses that their project relies upon. It helps enable projects to make determinations about whether to avoid particular dependencies — for example, if their licenses might be incompatible with the project’s own license, IP policies and community objectives. It also helps projects identify their compliance obligations for the dependencies they use — for example, which license notices they need to reproduce when they distribute those dependencies.

Secondly, the Linux Foundation’s new EasyCLA (Contributor License Agreement) service tackles the difficult problem of ensuring that Contributor's assign IP rights on their source code to opensource projects. The new EasyCLA service also handles corporate authority considerations by requiring corporate EasyCLA to be signed by an authorized signatory of a company. It enables companies to control which of their employees are authorized to contribute to which projects under the signed EasyCLA . Depending on their own needs and processes, companies can take a fine-grained approach by specifying individual authorized contributors’ email addresses, or can easily authorize all employees across a domain name. The EasyCLA service facilitates all these workflows and ensures that code contributions can only be accepted after the contributor satisfies the EasyCLA requirements. Although the EasyCLA service is initially available to Linux Foundation-hosted projects, we hope to make it available to a broader set of projects, including those on LFX Security.

## When is the license information displayed as "Unknown"? <a href="#vulnerabilitydetectionfaqs-howdoescommunitybridgehelpaprojectmanageitsintellectualpropertyobligation" id="vulnerabilitydetectionfaqs-howdoescommunitybridgehelpaprojectmanageitsintellectualpropertyobligation"></a>

The license information is displayed as "Unknown" when Snyk API cannot find license information and returns "unknown" value to LFX Security.

## When is the license information displayed as empty without any license information? <a href="#vulnerabilitydetectionfaqs-howdoescommunitybridgehelpaprojectmanageitsintellectualpropertyobligation" id="vulnerabilitydetectionfaqs-howdoescommunitybridgehelpaprojectmanageitsintellectualpropertyobligation"></a>

The license information is displayed as empty when **License** field is blank with out having any license information. The Snyk API will be unable to find any information related to the license and the license information is displayed as empty.

## What are Code Secrets?

Code secrets are private valuable information. LFX Security searches for different secrets in code, which include tokens, keys, IDs, credentials and passwords.

## What is Non Inclusive Language?

Non inclusive language are words that depict people unfairly in an insulting manner and exclude people based on their ethnicity, gender or color. Usage of these words is not expected use in the open source code. LFX Security scans for non inclusive language in the code.&#x20;
