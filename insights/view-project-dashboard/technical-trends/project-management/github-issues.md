# GitHub Issues

{% hint style="info" %}
By default, Bot Commits are filtered, however, you can include the filter values by navigating to the filter section of dashboard. For details, see [Add and Manage Data Filters](../../../filter-data/add-and-manage-data-filters.md).
{% endhint %}

Click ![](../../../../.gitbook/assets/copy-short-url.png) to copy the path of respective dashboards.

Following are the various dashboards of GitHub Issues:

* [Overview](github-issues.md#overview)
* [Efficiency](github-issues.md#efficiency)
* [Timing](github-issues.md#timing)
* [Backlog](github-issues.md#backlog)

## Overview

Overview shows information about issues in project repositories and who submitted the issues and when. For each commit, information about the corresponding organization is also provided.

**Filter** lets you filter the dashboard data by author name, organization name, and repository. Select values from the respective drop-down lists, and click **Apply changes** to filter the dashboard as per selection.

**Summary** shows the total number of Issues, Submitters, and Repositories for the project.

**Issues by Organization Over Time** shows a stacked bar graph that represents the number of issues created by organizations per day.

**Issues by Status Over Time** shows a stacked bar graph that represents the number of open and closed issues over time.

**Issues Percentage by Organization** shows a doughnut chart that represents the total number of issues created by each organization over time. Mouse over a color \(organization\) in the chart to see the organization name, total number and percentage of issues.

**Issue Submitters Over Time** shows a bar graph that shows the number of submitters of issues per day over time.

**Submitters** shows a table that lets you sort values by Submitter, Issues, Repositories, and Avg. Open Days.

**Organizations** shows a table that lets you sort values by Organization, Issues Open, Submitters, Assignees, and Labels. 

**Repositories** shows a table that lists project's repositories, total number of Issues Open, Submitters, Assignees, and Labels per repository. You can select a repository to view its details in GitHub.

## Efficiency

Efficiency offers a view of efficiency closing issues based on metrics: Backlog Management Index \(BMI\), Lead Time, and Time to Close.

**Efficiency Closing GitHub Issues** lets you select and organization and project as values for the dashboard data.

**Backlog Management Index** shows a multi-line graph that represents the Backlog Management Index \(BMI\). BMI is the number of closed issues divided by the number of open ones in a given period of time. Moving Avg. is set to 8 weeks to identify changes in trends. Average is also shown as a reference. BMI values greater than 1 mean the community is closing more issues than those they are opening. Values less than 1 mean the opposite—more issues are open than those closed during a given time frame. Mouse over this graph or **Lead Time** to show a line that displays the date and time at the top of the legend..

![](../../../../.gitbook/assets/18088187%20%281%29%20%281%29.png)

**Lead Time** shows a multi-line graph that represents the Average Time to Close issues expressed in days and what the trend is. This graph helps you to identify peaks and visualize the time spent in closing issues.

**Time to Close** shows a gauge that represents the time from issue creation to the moment in which it is closed. The gauge is set to show green color for less than 7 days, yellow for values from 7 to 30 days, and red from 30 to 90 days. This color scheme means that a week is considered as a good time to close. The color scheme is just a visual reference and you can always rely on the number, ignoring this color scheme.

**Median Time To Close Issues By Repositories** shows a table that lets you sort values by Repository and 50th percentile of Median Time Open \(days\).

## Timing

Timing shows information about open and closed issues in time. The dashboard focuses on how long Issues remain open. Statistical information provides closing times and also tables with the latest and the oldest Issues.

**Filter** lets you filter the dashboard data by author name, organization name, and repository. Select values from the respective drop-down lists, and click **Apply changes** to filter the dashboard as per selection.

**Summary** shows the total number of Issues, Submitters, Assignees, and 50th percentile of Median Time Open \(Days\)—number of days for which 50% of open issues remained open.

**Issues By Status** shows a stacked bar graph that represents the total number of issues over time in the project by status: closed or open. Mouse over a color in the graph to see the status, the total number of issue for the status, and the date.

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

