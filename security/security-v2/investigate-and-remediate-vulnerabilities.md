# Investigate and Remediate Vulnerabilities

Vulnerabilities in project code can cause a range of problems for your project and the developers who use it. LFX Security shows vulnerabilities in your repositories and helps you to remediate risks with automated updates and patches.

For each repository, LFX Security maps the dependencies and correlates them with the vulnerability database. You can investigate and remediate certain types of vulnerabilities in your Git repository. For example, an injection vulnerability means your project does not guard against code being injected in your system to extract, damage, or destroy data. Investigate the issue details to find out how to remediate the vulnerability if possible.

If possible, address a vulnerability by upgrading to a vulnerability-free version of the package you are using. If you cannot upgrade, because no sufficient direct upgrade is available or because the upgrade includes breaking changes, another option is to apply a patch. A patch changes the locally installed package file to fix the vulnerability. If an upgrade or patch is unavailable, assess the issue and weigh risk against effort. If the risk is high, consider removing the dependency.

## **View Issues **

Issues tab provides a list with all the issues related to the project. The issue list provides information such as repository name, open issues, type of issues such as critical, high, medium and  low. You can also see the complete details related to a issue.&#x20;

To view issues, perform the following:

1.Select **Issues** from the top menu.\
The dashboard shows all vulnerabilities with their details, and total number of open and fixed issues. By default, only Open status issues appear—use the filter to show Fixed issues.

![Issues Dashboard](<../../.gitbook/assets/Issues (1).png>)

2\. You can search for a particular repository using the Repositories drop-down list. You can select the required repositories and check the issues and their details.&#x20;

![Repositories ](../../.gitbook/assets/Issues\_Repo.png)

3.You can view the total number of open and fixed issues for a repository by clicking the **View Details**.&#x20;

![View Details](../../.gitbook/assets/Issues\_view.png)

4\. You can see the Open issues related to the repository. You can also refine the issues based on the priority such as Critical, High, Medium and Low. &#x20;

![Open Issues ](../../.gitbook/assets/Issues\_Details.png)

5.Click the ![](../../.gitbook/assets/Icon.png) icon to see more details and to investigate the vulnerabilities. You can check the following details related to vulnerabilities:

* Details about the issue, and when possible, a remediation and references to the corresponding PR, issue, CWE or CVE record, and so on.
* Read the details and decide how you want to fix the vulnerability, for example, by applying a Snyk patch

![Vulnerability Details ](../../.gitbook/assets/More.png)

{% hint style="info" %}
You can use the ![](../../.gitbook/assets/Eye\_icon.png) icon to dismiss the vulnerability. You can dismiss the vulnerability incase if you feel the issue cannot be fixed, if the issue is minor or you do not want to fix the issue.&#x20;
{% endhint %}

6.You can also click a CWE-# link or CVE-# link to read a description, references, and so on, about the vulnerability. The [Common Weakness Enumeration website](https://cwe.mitre.org) or [Common Vulnerabilities and Exposures website](https://cve.mitre.org) shows an identifier and details for the vulnerability by an identifier.

![CWE and CVE](<../../.gitbook/assets/CVE (1).png>)

7\. Investigate the vulnerabilities by opening the provided links to go directly to various websites for specific information about the vulnerability. For example:

* Click a **GitHub PR** link, a **GitHub Commit**, and then a **GitHub Issue** link to learn more about the corresponding pull request, commit, and issue, respectively.

![GitHub Links ](../../.gitbook/assets/Github.png)

### Download Issues

You have an option to download the CSV file that contains issues related to your repository. The downloaded CSV file contains information such as:

* Repository ID
* Snyk ID
* Status&#x20;
* Remediation&#x20;
* Severity&#x20;
* Disclosure and Publication time

Along with the above listed information, it also contains other generic information.&#x20;

You can download the issues related to all repositories or for the selected repositories and for the required date range. &#x20;

To download the issues CSV file,  perform the following:

1.Select **Issues** from the top menu.

2.From the Issues banner, click the ![](../../.gitbook/assets/Download\_Icon.png) icon. The exports.csv file will be downloaded. You can check all the information related to the repository issues in the downloaded file.

![Download Issues](<../../.gitbook/assets/Download (1).png>)



