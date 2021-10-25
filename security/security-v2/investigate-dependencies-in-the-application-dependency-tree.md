# Investigate Dependencies in the Application Dependency Tree

LFX Security looks for vulnerabilities in your open-source dependencies and identifies the vulnerabilities. The Dependency Tree dashboard provides detailed information about any dependencies in a repository and maps the full application dependency tree. You can view details about a specific dependency and see which repositories are using it. The way the repository uses a dependency affects the problem severity level.

Vulnerabilities can be caused by either direct or deep dependencies.&#x20;

* A direct dependency is a package that you have included in your own repository.
* A deep (indirect) dependency is a package that you are not using directly, but one that is used by one of your direct dependencies. For example, if your application is using package A, and package A is using package B, then your application is indirectly depending on package B. And if package B is vulnerable, your project is vulnerable.

As an open-source developer, you should understand the direct and indirect dependencies your repositories and projects use, including any security flaws that might exist in the dependency tree. LFX Security determines all the paths through the dependency tree in which a vulnerable dependency can be reached, and identifies the vulnerability.

## All Dependencies&#x20;

To view all dependencies, perform the following:

1.Select **Dependency Tree** from the top menu and click **All Dependencies**.

A snapshot of dependencies in the repository in a tree format of the dependencies appears. The tree repository order is descendant from the greatest number of dependencies in a repository to the least number. Each item (a branch or a node) can have a number of subitems. By default, the first three levels appear. Expand nodes of interest to drill down in the tree.

![Dependency Tree](../../.gitbook/assets/Dependency.png)

2\. You can select a **repository** from the Repository drop-down list. Only dependencies for the selected repository and project appear.\


![Select Repository](../../.gitbook/assets/Dependency\_Select.png)

{% hint style="info" %}
Click the download ![](../../.gitbook/assets/Download\_icon.png) icon to download the dependency CSV file.&#x20;
{% endhint %}

3.Navigate the tree to identify vulnerable dependencies in the repository. A yellow warning icon indicates that an item has a child with a vulnerability—track a dependency by following the yellow warning icons down the tree. On vulnerable dependencies, colored labels indicate severity levels. You can click a label to go to the Details dashboard to see the issue details inside the project.\


![](../../.gitbook/assets/Tree.png)

4.Click a **license** of interest to go to SPDX and find out more information about a license. The SPDX License includes a full name, standardized short identifier, vetted license text, and other information about the license.

![License Details ](../../.gitbook/assets/apache-license.png)

## Vulnerability Details &#x20;

You can also check the vulnerability details only for a particular repository.&#x20;

To check the vulnerability details only, perform the following steps:

1.Click **Dependency Tree** and select **Vulnerabilities Only**.&#x20;

![Vulnerabilities Only](<../../.gitbook/assets/Vul (2).png>)

{% hint style="info" %}
Click the download ![](../../.gitbook/assets/Download\_icon.png) icon to download the vulnerabilities CSV file.&#x20;
{% endhint %}

2\. List of vulnerabilities related for a particular repositories are listed. You  can click on the links for a particular issue such as High, Medium and Low. By clicking the link, you will redirected to the issues page.&#x20;

![Issues Link ](../../.gitbook/assets/Vul\_link\_iss.png)



