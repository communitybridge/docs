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

Click ![](../../../../.gitbook/assets/get-short-url.png) to copy the path of respective dashboards.

## Overview

Overview shows all the information about pull requests for a project.

**Filter** lets you filter the dashboard data by author name, organization name, repository name, and repository URL. Select values from the respective drop-down lists, and click **Apply changes** to filter the dashboard as per selection.

**Summary** shows the total number of pull requests, submitters, and repositories of the project over time.

**Most Used PR Labels** shows a cluster of top 10 Pull request labels. Click a label to filter the project dashboard to view label related details. Click the cross mark next to a label in the **Add Filter** navigation bar to remove the filter.

**Submitters Over Time** shows a bar graph that represents the number of pull request submitters per day over time. Mouse over a color in the graph to see the total number of submitters that occurred on a date.

**Pull Requests By Organization** shows a doughnut chart that represents the total number of pull requests per organization over a time range. Mouse over a color \(organization\) in the chart to see the organization name, total number and percentage of pull requests.

**PRs Created Over Time** shows a periodic line graph that displays the number of Pull Requests created over time. Hover mouse over the graph to view the date and number of PRs created on the date.

**Pull Requests By Submitters** shows a table that lists submitter name, number of pull requests by the submitter, number of repositories the submitter submitted PRs to, number of merged, rejected and open PRs by the submitter, and average number of days taken to merge the submitter's PRs.

**Pull Request by Organization** shows a table that lists and lets you sort values by organization name, number of Pull Requests submitted by the organization over time, total number of submitters of the organization, and number of repositories to which the submitters of the organization have submitted PRs .

**Pull Requests By Repositories** shows a table that lists and lets you sort values by repository link, number of pull requests per repository, number of PR submitters for the repository, and average time taken in days to merge the PRs. You can select a repository to view details on GitHub.

## Efficiency

Efficiency offers an overall view of understanding and optimizing project efficiency in closing GitHub issues.

**Filter** lets you filter the project data by organization name, author name, repository name, and repository URL. Select values from the respective drop-down lists, and click **Apply changes** to filter the dashboard as per selection.

**Summary** shows a cluster of 

* Total number of closed issues
* Number of submitters whose issues are closed
* Number organizations that helped in closing the issues
* Repositories of the project to which the closed issues belong to
* Number of days it took to close 50 percentage of the issues, and 
* Number of days it took to close 95 percentage of the issues over time

**50th percentile of Time To Close By Repo** shows a cluster of top 10 repositories  names for which it took most time to close 50% of the issues.

**Time to Merge** shows a graph that displays number of Pull Requests that took certain amount of time to get merged. These time slots are divided into four categories, such as less than 1 day, 1 to 7 days, 7 to 30 days, and more than 30 days. Hover mouse over the graph to view number of of PRs along with the time taken to get merged.

* Less than 1 day: The number of pull requests merged in less than one day.
* 1 to 7 days: The number of pull requests merged in more than one day but less than seven days.
* 7 to 30 days: The number of pull requests merged in more than seven days but less than thirty days.
* More than 30 days: The number of pull requests merged in more than thirty days.

**Repositories** shows a table that lists repositories, total number of PRs merged along with the time it took for 50% and 95% of the PRs to get merged per repository. Click a repository to navigate to GitHub to view details. 

## Timing

Timing shows information about open and closed pull requests in time. The dashboard focuses on how long pull requests remain open. Statistical information provides closing times and also tables with the latest and the oldest pull requests.

**Filter** lets you filter the dashboard data by author name, organization name, and repository. Select values from the respective drop-down lists, and click **Apply changes** to filter the dashboard as per selection.

**Summary** shows the total number of Pull Requests, Submitters, Assignees, and 50th percentile of Median Time Open \(Days\) over time—number of days for which 50% of Open Pull Requests remained open.

**Median Open Time \(days\)** shows a bar graph that represents number of days for which 50% of open pull requests \(out of all PRs created on a date\) remained open. Mouse over a color in the graph to see the number.

**95th Percentile Open Time \(days\)** shows a bar graph that represents number of days for which 95% of open pull requests \(out of all PRs created on a date\) remained open. Mouse over a color in the graph to see the number. Mouse over a color in the graph to see the  number.

**Status** shows a doughnut chart that represents the total number of pull requests in the project by status: closed or open. Mouse over a color in the chart to see the status, total number of pull requests for the status, and the percentage of the project's pull requests for that status.

**Pull Requests by Organization** shows a doughnut chart that represents the total number of pull requests submitted by an organization. Mouse over a color in the chart to see the total number of pull requests for the organization, and their percentage.

**Pull Requests By Status** shows a stacked bar graph that represents the total number of pull requests over time in the project by status: closed or open. Mouse over a color in the graph to see the status, the total number of issues for the status, and the date.

**Submitters Over Time** shows a bar graph that represents the total number of submitters over time in the project. Mouse over a color in the graph to see total number of submitters and the date.

Pull Requests By Submitters shows a table that lets you sort values by Submitter, number of pull requests, repositories, and average number of days for which the PRs remained opened .

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

