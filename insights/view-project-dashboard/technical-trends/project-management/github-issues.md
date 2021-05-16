# GitHub Issues

{% hint style="info" %}
By default, Bot Commits are filtered, however, you can include the filter values by navigating to the filter section of dashboard. For details, see [Add and Manage Data Filters](../../../filter-data/add-and-manage-data-filters.md).
{% endhint %}

Click ![](../../../../.gitbook/assets/get-short-url.png) to copy the path of respective dashboards.

Following are the various dashboards of GitHub Issues:

* [Overview](github-issues.md#overview)
* [Efficiency](github-issues.md#efficiency)
* [Timing](github-issues.md#timing)
* [Backlog](github-issues.md#backlog)

## Overview

Overview shows information about issues in project repositories and who submitted the issues and when. For each commit, information about the corresponding organization is also provided.

**Filter** lets you filter the dashboard data by author name, organization name, and repository. Select values from the respective drop-down lists, and click **Apply changes** to filter the dashboard as per selection.

**Summary** shows the total number of issues, submitters, and repositories for the project.

**Issues by Organization Over Time** shows a stacked bar graph that represents the number of issues created by organizations per day.

**Issues by Status Over Time** shows a stacked bar graph that represents the number of open and closed issues over time.

**Issues Percentage by Organization** shows a doughnut chart that represents the total number of issues created by each organization over time. Mouse over a color \(organization\) in the chart to see the organization name, total number and percentage of issues.

**Issue Submitters Over Time** shows a bar graph that shows the number of submitters of issues per day over time.

**Issues By Submitters** shows a table that lists submitter name, total number of issues raised by the submitter, number of issues that are in open and closed state out of the total issues, number of repositories the submitter worked upon, and average number of days it took to close the issues raised by the submitter.

**Issues By Organizations** shows a table that organization name, total number of issues raised by the organization, number of issues in open and closed states, number of submitters, and average number of days the it took to close the issues raised by the organization.

**Issues By Repositories** shows a table that lists project's repository links, total number of issues, number of issues in open and closed states for the repository, number of submitters, and average number of days it took to close the issues. You can select a repository to view its details in GitHub.

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

**Time to Close** shows line graphs that represent number of issues that took certain amount of time to get closed. These time slots are divided into four categories, such as less than 1 day, 1 to 7 days, 7 to 30 days, and more than 30 days. Hover mouse over the graph to view number of of PRs along with the time taken to get merged.

* Less than 1 day: The number of pull requests merged in less than one day.
* 1 to 7 days: The number of pull requests merged in more than one day but less than seven days.
* 7 to 30 days: The number of pull requests merged in more than seven days but less than thirty days.
* More than 30 days: The number of pull requests merged in more than thirty days.

**Repositories** shows a table that lists repository link, time it took for 50% and 95% of the issues to get closed per repository. Click a repository to navigate to GitHub to view details.

## Timing

Timing shows information about open and closed issues in time. The dashboard focuses on how long Issues remain open. Statistical information provides closing times and also tables with the latest and the oldest Issues.

**Filter** lets you filter the dashboard data by author name, organization name, and repository. Select values from the respective drop-down lists, and click **Apply changes** to filter the dashboard as per selection.

**Summary** shows the total number of Issues, Submitters, Assignees, and 50th percentile of Median Time Open \(Days\)—number of days for which 50% of open issues remained open.

**Issues By Status** shows a doughnut chart that represents the total number of issues over time in the project by status: closed or open. Mouse over a color in the graph to see the status, the total number of issue for the status, and the date.

**Status** shows a doughnut chart that represents the total number of issues in the project by status: closed or open. Mouse over a color in the chart to see the status, the total number of issues for the status, and the percentage of the project's issues for that status.

**Median of Days An Issue is in Open State** shows a bar graph that represents number of days for which 50% of issues, out of total issues that are created on a particular day, are open.

**95th Percentile of Days An issue is in Open State** shows a bar graph that represents number of days for which 95% of issues, out of total issues that are created on a particular day, are open.

**Submitters** shows:

* a bar graph that represents the total number of submitters over time in the project. Mouse over a color in the graph to see the status, total number of submitters and the date.
* a table of submitters and their corresponding number of Issues, Repositories, and Avg. Open Days.

**Issues By Organization** shows doughnut chart that represents the total number of issues \(closed and open\) by an organization over time. Mouse over a color in the chart to see organization name, total number of issue for the organization, and date.

**Organizations** shows a table that lets you sort values by Organization, Issues Open, Submitters, Assignees, and Avg. Open Days.

**Repositories** shows a table listing repositories by name and Issues Open, Submitters, Assignees, and Avg. Open Days.

**Latest Issues** shows a table listing issues by Title, Repository, Submitter, URL, Id, and Created on. The default sort is by most recently created issue.

**The Oldest Issues** shows a table listing issues by Title, Repository, Submitter, URL, Id, and Open Days. The default sort is by the greatest number of open days.

## Backlog

Backlog focuses on open issues, their accumulated time, and associated organization.

**github\_filter** lets you filter the dashboard data by author name, organization name, and repository. Select values from the respective drop-down lists, and click **Apply changes** to filter the dashboard as per selection.

**Open Issues Statistics Summary** shows the total number of Open Issues, Accumulated time in days for Open issues, and Average Time Open per Issue.

**Backlog \(Open Issues\)** shows a table that lets you sort values by Summary, URL, Open Date, and Days Open. Click **+Info** from URL column to go to the issue in the project.

**Backlog** shows a bar graph that represents the number of issues that are open on a particular day. Mouse over a color in the graph to see the total number of issues on a date.

**Backlog: Issues \(Accumulated Over Time\)** shows a bar graph that represents the cumulative number of days for which individual issues are open, on a particular date. Mouse over a color in the graph to see the accumulated number of days the issues were waiting to be closed on a date.

**Percentage of Issues Opened By Organizations** shows a doughnut chart that represents the total number of issues opened by organization. Mouse over a color in the chart to see the total number of issues for the organization, and their percentage of the project's organization.

**Backlog Submitters** shows a table that lets you sort values by Submitters, Issues, Avg. Time Open \(Days\), and Repositories.

**Organizations** shows a table that lets you sort values by Organization, Issues open, Submitters, Assignees, and Labels.

