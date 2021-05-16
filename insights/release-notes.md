# Release Notes

## May 2021

The LFX Insights, May 2021 Release delivers support for new data sources and metrics— GitHub Reviews, Changeset Reviews metrics as source control systems, Circle CI as build system, and Google Groups as Email system to visualize project related communication activities.

* [Added Features](release-notes.md#added-features)
* [Deprecated Features](release-notes.md#deprecated-features)

## Added Features

## Deprecated Features

Following visualizations are deprecated in this release, and the dashboards are updated and enhanced with new visualizations in various data sources:

### GitHub PR Overview

**Pull Requests by Status Over Time** showed a stacked bar graph that represents the number of open and closed pull requests over time. Mouse over a color in the graph to see the total number of pull requests by status that occurred on a date.

**Pull Request by Organizations Over Time** showed a stacked bar graph that represents the number of pull requests per day by organization over time. Mouse over a color in the graph to see the total number of pull requests that occurred on a date for the organization.

**Pull Requests By Project** showed a table and lists and lets you sort values by project name, number of pull requests, submitters, and repositories per project.

### GitHub PR Efficiency

**Efficiency Closing GitHub Pull Requests** let you select an organization and project as values for the dashboard data. Select values from the respective drop-down lists, and click **Apply changes** to filter the dashboard as per selection.

**REI** \(Review Efficiency Index\) showed a multi-line graph that represents the REI. REI is defined as the number of closed pull requests divided by the number of open pull requests in a given period of time. This visualization measures efficiency in closing pull requests. REI as a moving average is set to 8 weeks to identify changes in trends. Average is also shown as a reference. REI values greater than 1 mean the community is closing more pull requests than those they are opening. Values smaller than 1 mean the opposite—more pull requests open than those closed during a given time frame. Mouse over this graph or **Lead Time** to show a line that displays the date and time at the top of the legend.

**Time to Merge** shows the time from pull request creation to the moment in which the pull request is closed. The gauge is set to show green color for less than 7 days, yellow for values from 7 to 30 days and red from 30 to 90 days. This setting means that a week is considered as a good time to merge.

**Lead Time** shows a multi-line graph that represents the average time expressed in days between the initiation and completion of a production process, in this case, a pull request. Mouse over this graph or REI to show a line that displays the date and time at the top of the legend.

**Repositories** shows a table with 50th percentile of Median Time Open \(days\) by repository, giving an insight to the differences between them. You can click repository name to open the repository in GitHub.

**Efficiency Closing GitHub Pull Requests:**

**REI**: Review Efficiency Index, defined as the number of closed pull requests divided by the number of open ones in a given period of time. Measures efficiency closing pull requests.

**Lead time**: the time expressed in days between the initiation and completion of a production process, in this case, a pull request. Shown in average.

### GitHub PR Timing

**Status** shows a doughnut chart that represents the total number of pull requests in the project by status: closed or open. Mouse over a color in the chart to see the status, total number of pull requests for the status, and the percentage of the project's pull requests for that status.

**Pull Requests By Status** shows a stacked bar graph that represents the total number of pull requests over time in the project by status: closed or open. Mouse over a color in the graph to see the status, the total number of issues for the status, and the date.

**Submitters Over Time** shows a bar graph that represents the total number of submitters over time in the project. Mouse over a color in the graph to see total number of submitters and the date.

**Pull Requests By Submitters** shows a table that lets you sort values by Submitter, number of pull requests, repositories, and average number of days for which the PRs remained opened .

**Latest Pull Requests** shows a table that lets you sort values by Title, Repository, Submitter, URL, Id, and Created on. The default sort is by most recently created issues.

**The Oldest Pull Requests** shows a table that lets you sort values by Title, Repository, Submitter, URL, Id, and Open Days. The default sort is by the greatest number of open days.

**95th Percentile Open Time \(days\)** shows a bar graph that represents number of days for which 95% of open pull requests \(out of all PRs created on a date\) remained open. Mouse over a color in the graph to see the number. Mouse over a color in the graph to see the  number.

### GitHub PR Backlog

**Open Pull Requests Statistics Summary** shows the total number of Open Pull Requests, cumulative number of days for which individual PRs are open, and the average time in days Open per Pull Request.

**Backlog: Pull Requests \(Accumulated Over Time\)** shows a bar graph that represents the cumulative number of days for which individual pull requests are open, on a particular date. Mouse over a color in the graph to see the accumulated number of days the pull requests were waiting to be closed on a date.

**Pull Requests Backlog Percentage By Organizations** shows a doughnut chart that represents the total number of pull requests in the project by organizations that are yet be closed. Mouse over a color in the chart to see the total number of pull requests by the organization, and their percentage of the project's organization.







