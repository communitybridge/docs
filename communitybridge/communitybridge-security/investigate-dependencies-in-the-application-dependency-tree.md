# Investigate Dependencies in the Application Dependency Tree

CommunityBridge Security looks for vulnerabilities in your open-source dependencies and identifies the vulnerabilities. The Dependency Tree dashboard provides detailed information about any dependencies in a repository and maps the full application dependency tree. You can view details about a specific dependency and see which repositories are using it. The way the repository uses a dependency affects the problem severity level.

Vulnerabilities can be caused by either direct or deep dependencies. 

* A direct dependency is a package that you have included in your own repository.
* A deep \(indirect\) dependency is a package that you are not using directly, but one that is used by one of your direct dependencies. For example, if your application is using package A, and package A is using package B, then your application is indirectly depending on package B. And if package B is vulnerable, your project is vulnerable.

As an open-source developer, you should understand the direct and indirect dependencies your repositories and projects use, including any security flaws that might exist in the dependency tree. CommunityBridge Security determines all the paths through the dependency tree in which a vulnerable dependency can be reached, and identifies the vulnerability.

**Do these steps:**

1. Select **Dependency Tree** from the top menu.

   A snapshot of dependencies in the repository in a tree format of the dependencies appears. The tree repository order is descendant from the greatest number of dependencies in a repository to the least number. Each item \(a branch or a node\) can have a number of subitems. By default, the first three levels appear. Expand nodes of interest to drill down in the tree.

2. Select a **repository** from the Repository drop-down list. ![](../../.gitbook/assets/7410955.png) Only dependencies for that repository and project appear.
3. Navigate the tree to identify vulnerable dependencies in the repository. A yellow warning icon indicates that an item has a child with a vulnerability—track a dependency by following the yellow warning icons down the tree. On vulnerable dependencies, colored labels indicate severity levels. You can click a label to go to the Details dashboard to see the issue details inside the project. ![](../../.gitbook/assets/7410956.png)
4. Find out more about a dependency:
   * Click a **dependency** of interest. Information from the Snyk Vulnerability Database appears. Read the details and decide how you want to fix the vulnerability, for example fix it by applying a patch if one is available.
   * Click a **license** of interest to go to SPDX and find out more information about a license. The SPDX License includes a full name, standardized short identifier, vetted license text, and other information about the license.

