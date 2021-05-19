# Compare and View Project Health

Project Health Dashboard is a tool that lets you compare key code related metrics for a project or between projects \(at the most you can compare 10 projects side-by-side\). These metrics come from a variety of data sources that can be broadly categorized into Version Control System and Issue Management System, and include supported systems, such as Git, Github, Gerrit, Jira and Bugzilla.

The dashboard serves two purposes:

1. Comparing the key metrics for the same project for different time periods.
2. Comparing the key metrics between multiple projects for the selected time period.

{% hint style="info" %}
**Note:** For better comparing of metrics between projects, compare projects that have the same data sources as version control or issue management systems. If you compare projects that use different data sources, the side-by-side comparison will not be available, and metrics will show separately. For example if you compare between Onap and Yocto, Onap uses Jira and Yocto uses Bugzilla as issue management systems, the comparison of these two metrics will not be displayed side-by-side, rather will show separately.
{% endhint %}

The Following metrics are displayed under various data sources:

* [Commits](compare-and-view-project-health.md#commits)
* [Pull Requests](compare-and-view-project-health.md#pull-requests)
* [Changesets](compare-and-view-project-health.md#changesets)
* [GitHub Issues](compare-and-view-project-health.md#github-issues)
* [Jira/Bugzilla Issues](compare-and-view-project-health.md#jira-bugzilla-issues)

#### **Commits:**

* **Days Since Last Commit:** Number of days there has not been any code contributions to the project.
* **Last Commit Date:** Day when there was a last code contribution to the project.
* **Number of Commits:** Total number of code commits to the project for the selected time range.
* **Number of total code contributors:** Total number of contributors to the project for the selected time range.
* **Percent of commits from the top organization:** Displays name of the organization that contributed most number of code changes to the project. It also displays the percentage of code commits from the organization compared to the total number of commits made to the project by all the organizations.
* **Percent of commit contributors from the top organization:** Displays name of the organization from which maximum number of contributors committed code changes. It also displays the percentage of contributors from the organization compared to the total number of contributors to the project.
* **Percent of commits by affiliated contributors:** Displays percentage of code contributions made by those contributors who are affiliated with organizations. It means these percentage of contributions are not from "Unknown" authors.
* **Percent of affiliated contributors:** Displays percentage of contributors who are affiliated with organizations. It means these percentage of contributors are not tagged "Unknown".

#### **Pull Requests:**

* **Number of contributors reviewing PRs:** Total number of contributors who are currently reviewing the pull requests for the project for a selected time range.
* **Number of PRs rejected:** Total number of pull requests that are rejected for a selected time period.
* **Organization reviewing most PRs:** Displays name of the organization whose contributors are reviewing most number of pull requests. It also displays the percentage of reviews done by the organization in relation to the total reviews done by other organizations to the project.
* **Average PR lead time \(time in days for a PR to get merged\):** Displays average number of days it took for a PR to get merged.
* **Number of contributors merging PRs:** Total number of contributors, for a selected time range, who are merging the pull requests.
* **Number of new contributors merging PRs** \(it is displayed for a selected time range\): Total number of new contributors, over a selected time range, who are merging PRs.
* **Number of PRs closed:** Total number of pull requests that are closed for a selected time range.
* **Number of PRs opened:** Total number of pull requests that are newly created over a selected time range.
* **Number of PRs merged:** Total number of pull requests that are merged over a selected time range.
* **Opened to closed rate:** 
* **Percent of contributors merging PRs from the top organization:** Displays name of the organization from which maximum number of contributors are merging pull requests for a selected time range. It also displays the percentage of contributors from the organization compared to the total number of contributors to the project.
* **Percent of PRs merged from the top organization:** Displays name of the organization whose contributors are merging maximum number of pull requests for a selected time range. It also displays the percentage of PRs merged by the organization compared to the total number of PRs merged by all the organizations.

#### **Changesets**

* **Number of contributors merging changesets:** Total number of contributors, for a selected time range, who merged the changesets.
* **Number of new contributors merging changesets** \(it is displayed for a selected time range\): Total number of new contributors, for a selected time range, who are merging changesets.
* **Number of changesets merged:** Total number of changesets merged over a selected time range.
* **Number of changesets approved:** Total number of changesets approved over a selected time range.
* **Number of changesets opened:** Total number of changesets that are newly created over a selected time range.
* **Number of changesets closed:** Total number of changesets that are closed over a selected time range.
* **Opened to closed rate:** 
* **Percent of contributors merging changesets from the top organization:** Displays name of the organization from which maximum number of contributors are merging changesets for a selected time range. It also displays the percentage of contributors from the organization compared to the total number of contributors to the project.
* **Percent of changesets merged from the top organization:** Displays name of the organization whose contributors are merging maximum number of changesets for a selected time range. It also displays the percentage of changesets merged by the organization compared to the total number of changesets merged by all the organizations.

#### **GitHub Issues**

* **75th Percentile of time issue in open state:** Total number of days for which 75% of the total GitHub issues are in open state.
* **95th Percentile of time issue in open state:** Total number of days for which 95% of the total GitHub issues are in open state.
* **Median time issue in open state:** Average number of days for which the issues are in open state.
* **Number of issues closed:** Total number of issues that are closed over a selected time range.
* **Number of issues opened:** Total number of issues that are created over a selected time range.
* **Opened to closed rate:** 

#### **Jira/Bugzilla Issues:**

Each section displays the following metrics:

* **Total number of issues:** Total number of issues created over a selected time range.
* **Number of submitters:** Total number issue submitters for a selected time range.
* **Number of assignees:** Number authors, over a selected time range, who are assigned with the created issues.
* **75th Percentile of time issue in open state:** Total number of days for which 75% of the total issues are in open state.
* **95th Percentile of time issue in open state:** Total number of days for which 95% of the total issues are in open state.
* **Median time issue in open state:** Average number of days for which the issues are in open state.
* **Total Number of reopened issues:** Total number of issues that are re-opened over a selected time range.
* **Total Number of issues in closed/completed state:** Total number of issues that are closed or completed over a selected time range.
* **Total Number of issues in open/to-do state:** Total number of issues that are in open or to-do state over a selected time range.
* **Open to closed rate:** 
* **Percent of issues submitted from the top organization:** Displays name of the organization whose contributors are submitting maximum number of issues over a selected time range. It also displays the percentage of issues submitted by the organization compared to the total number of issues submitted to the project by all organizations.
* **Percent of submitters from the top organization:** Displays name of the organization from which maximum number of contributors submitted issues for a selected time range. It also displays the percentage of issue submitters from the organization compared to the total number of submitters of the project from all organizations.

### **To View Project Health Dashboard:**

 1. Go to[ https://insights.lfx.linuxfoundation.org/](https://insights.lfx.linuxfoundation.org/)

2. From the top left corner, click Compare Project Health.

![Compare Project Health](https://lh5.googleusercontent.com/jkn4-dxyPJSXTkbZKrpvsv56tnE8v0Alhsfc5_1Ok_P8MHuD-hMPhVx8Q_nw8U42RgIDJrooQ1n6SmODF4VcYIGbfCJXxFHN_i1yc8X4-acn0fgHRxRz3zAXbCMbp33ekFlul0i2)

3. Type and select a project in the **Search Projects** field.

4. Click **+Project** to add a new field to select and compare projects.   
**Note:** Default time range is “All”. Select a time range from the available options to change the metrics for the time period.

![Compare Project Health](../../.gitbook/assets/compare-project-health.png)



