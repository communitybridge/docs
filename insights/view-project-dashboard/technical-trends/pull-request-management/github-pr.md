# GitHub PR

{% hint style="info" %}
By default, Bot commit is filtered. To add/manage filters, see [Add and Manage Data Filters](../../../filter-data/add-and-manage-data-filters.md).
{% endhint %}

 The GitHub PR dashboards represent a set of metrics that shows pull request information of GitHub repositories of the project. Following are the various dashboards of GitHub PR:

* [Overview](github-pr.md#overview)
* [Efficiency](github-pr.md#efficiency)
* [Timing](github-pr.md#timing)
* [Backlog](github-pr.md#backlog)

By default, **Bots** filter is applied. To apply more filters, see [add and manage data filters](../../../filter-data/add-and-manage-data-filters.md).

Click ![](../../../../.gitbook/assets/copy-short-url.png) to copy the path of respective dashboards.

## Overview

Overview shows all the information about pull requests for a project.

**Filter** lets you filter the dashboard data by author name, organization name, repository name, and repository URL. Select values from the respective drop-down lists, and click **Apply changes** to filter the dashboard as per selection.

**Summary** shows the total number of pull requests, submitters, and repositories of the project over time.

**Submitters Over Time** shows a bar graph that represents the number of pull request submitters per day over time. Mouse over a color in the graph to see the total number of submitters that occurred on a date.

**Pull Requests By Organization** shows a doughnut chart that represents the total number of pull requests per organization over a time range. Mouse over a color \(organization\) in the chart to see the organization name, total number and percentage of pull requests.

**Pull Requests by Status Over Time** shows a stacked bar graph that represents the number of open and closed pull requests over time. Mouse over a color in the graph to see the total number of pull requests by status that occurred on a date.

**Pull Request by Organizations Over Time** shows a stacked bar graph that represents the number of pull requests per day by organization over time. Mouse over a color in the graph to see the total number of pull requests that occurred on a date for the organization.

**Pull Requests By Submitters** shows a table that lists submitter name, number of pull requests by the submitter, number of repositories the submitter submitted PRs, and average number of days the submitter's PRs were open before they were closed.

**Organization** shows a table that lists and lets you sort values by organization name, number of Pull Requests submitted by the organization over time, total number of submitters of the organization, and number of repositories to which the submitters of the organization have submitted PRs .

**Pull Requests By Repositories** shows a table that lists and lets you sort values by repository link, number of pull requests, authors, assignees, and labels per repository. You can select a repository to view details on GitHub.

**Pull Requests By Project** shows a table and lists and lets you sort values by project name, number of pull requests, submitters, and repositories per project.

## Efficiency

Efficiency offers a view of efficiency closing issues based on metrics: Review Efficiency Index \(REI\), Time to Merge, and Lead Time.

**Efficiency Closing GitHub Pull Requests** lets you select an organization and project as values for the dashboard data. Select values from the respective drop-down lists, and click **Apply changes** to filter the dashboard as per selection.

**Note:** You can select more than one organization.

**REI** \(Review Efficiency Index\) shows a multi-line graph that represents the REI. REI is defined as the number of closed pull requests divided by the number of open pull requests in a given period of time. This visualization measures efficiency in closing pull requests. REI as a moving average is set to 8 weeks to identify changes in trends. Average is also shown as a reference. REI values greater than 1 mean the community is closing more pull requests than those they are opening. Values smaller than 1 mean the opposite—more pull requests open than those closed during a given time frame. Mouse over this graph or **Lead Time** to show a line that displays the date and time at the top of the legend.

![](../../../../.gitbook/assets/18088226%20%281%29.png)

**Time to Merge** shows the time from pull request creation to the moment in which the pull request is closed. The gauge is set to show green color for less than 7 days, yellow for values from 7 to 30 days and red from 30 to 90 days. This setting means that a week is considered as a good time to merge.

**Lead Time** shows a multi-line graph that represents the average time expressed in days between the initiation and completion of a production process, in this case, a pull request. Mouse over this graph or REI to show a line that displays the date and time at the top of the legend.

**Repositories** shows a table with 50th percentile of Median Time Open \(days\) by repository, giving an insight to the differences between them. You can click repository name to open the repository in GitHub.

**Efficiency Closing GitHub Pull Requests:**

This panel focuses on **closed** GitHub pull requests.

**REI**: Review Efficiency Index, defined as the number of closed pull requests divided by the number of open ones in a given period of time. Measures efficiency closing pull requests.

**Lead time**: the time expressed in days between the initiation and completion of a production process, in this case, a pull request. Shown in average.

## Timing

Timing shows information about open and closed pull requests in time. The dashboard focuses on how long pull requests remain open. Statistical information provides closing times and also tables with the latest and the oldest pull requests.

**Filter** lets you filter the dashboard data by author name, organization name, and repository. Select values from the respective drop-down lists, and click **Apply changes** to filter the dashboard as per selection.

**Summary** shows the total number of Pull Requests, Submitters, Assignees, and 50th percentile of Median Time Open \(Days\) over time—number of days for which 50% of Open Pull Requests remained open.

**Median Open Time \(days\)** shows a bar graph that represents number of days for which 50% of open pull requests \(out of all PRs created on a date\) remained open. Mouse over a color in the graph to see the number.

**95th Percentile Open Time \(days\)** shows a bar graph that represents number of days for which 95% of open pull requests \(out of all PRs created on a date\) remained open. Mouse over a color in the graph to see the number. Mouse over a color in the graph to see the  number.

**Status** shows a doughnut chart that represents the total number of pull requests in the project by status: closed or open. Mouse over a color in the chart to see the status, total number of pull requests for the status, and the percentage of the project's pull requests for that status.

**Pull Requests by Organization** shows a doughnut chart that represents the total number of pull requests submitted by an organization. Mouse over a color in the chart to see the total number of pull requests for the organization, and their percentage.

**Pull Requests By Status** shows a stacked bar graph that represents the total number of pull requests over time in the project by status: closed or open. Mouse over a color in the graph to see the status, the total number of issues for the status, and the date.

**Submitters:**

* shows a bar graph that represents the total number of submitters over time in the project. Mouse over a color in the graph to see total number of submitters and the date.
* shows a table that lets you sort values by Submitter, number of pull requests, repositories, and average number of days for which the PRs remained opened .

**Organizations** shows a table that lets you sort values by Organization, Pull Requests, Submitters, Assignees, and Avg. Open Days.

**Repositories** shows a table that lets you sort values by Repository, Pull Requests, Submitters, Assignees, and Avg. Open Days.

**Latest Pull Requests** shows a table that lets you sort values by Title, Repository, Submitter, URL, Id, and Created on. The default sort is by most recently created issues.

**The Oldest Pull Requests** shows a table that lets you sort values by Title, Repository, Submitter, URL, Id, and Open Days. The default sort is by the greatest number of open days.

## Backlog

Backlog focuses on open pull requests \(data is retrieved at the moment of dashboard creation\), their accumulated time, and associated organization.

**Filter** lets you filter the dashboard data by author name, organization name, and repository. Select values from the respective drop-down lists, and click **Apply changes** to filter the dashboard as per selection.

**Open Pull Requests Statistics Summary** shows the total number of Open Pull Requests, cumulative number of days for which individual PRs are open, and the average time in days Open per Pull Request.

**Backlog \(Open Pull Requests\)** shows a table that lets you sort values by Summary, URL, Open Date, and Days Open. Click **+Info** to open the URL to go to the pull request in the project.

**Backlog** shows a bar graph that represents the number of pull requests that are open on a particular day. Mouse over a color in the graph to see the total number of pull requests on a date.

**Backlog: Pull Requests \(Accumulated Over Time\)** shows a bar graph that represents the cumulative number of days for which individual pull requests are open, on a particular date. Mouse over a color in the graph to see the accumulated number of days the pull requests were waiting to be closed on a date.

**Pull Requests Backlog Percentage By Organizations** shows a doughnut chart that represents the total number of pull requests in the project by organizations that are yet be closed. Mouse over a color in the chart to see the total number of pull requests by the organization, and their percentage of the project's organization.

**Organizations** shows a table that lets you sort values by Organization, Pull Requests Open, Submitters, and Repositories.

**Backlog Submitters** shows a table that lets you sort values by Submitter, Pull Requests, Avg. Time Open \(Days\), and Repositories.

