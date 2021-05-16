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

### Gerrit Changeset Efficiency

**Efficiency Closing Gerrit Reviews** lets you select an Organization and Repository as values for the dashboard data. Select values from the respective drop-down lists, and click **Apply changes** to filter the dashboard as per selection.

**Review Efficiency Index** shows a multi-line graph that represents the REI. REI is the number of closed reviews divided by the number of open ones in a given period of time. This visualization measures efficiency closing reviews. REI Moving Avg. \(8 weeks\) identifies changes in trends. Average is also shown as a reference. REI values greater than 1 mean the community is closing more reviews than those they are opening. Values smaller than 1 mean the opposite—more reviews open than those closed during a given time frame. Mouse over this graph or **Lead Time** to show a line that displays the date and time at the top of the legend.

**Repositories** shows a table that displays the number of days 50th percentile of repository's reviews or changesets are open before they are closed. It gives an insight on the efficiency of closing reviews per repository.

**Time to Merge** shows a gauge that represents the time from issue creation to the moment in which it is merged. The gauge is set to show green color for less than 7 days, yellow for values from 7 to 30 days, and red from 30 to 90 days. This color scheme means that a week is considered as a good time to merge. The color scheme is just a visual reference and you can always rely on the number, ignoring this color scheme.

**Lead Time** shows a multi-line graph that represents the average Time to Merge expressed in days together to its trend. This helps to identify peaks and visualize the time spent in closing reviews.  Mouse over this graph or **REI** to show a line that displays the date and time at the top of the legend.

### Gerrit Changeset Timing

**Changesets By Status** shows a doughnut chart that represents the total number of changesets in the project by status: MERGED, ABANDONED, NEW, DRAFT. Mouse over a color in the chart to see the status, total number of changesets for the status, and the percentage of the project's changesets for that status.

**Organizations** shows a doughnut chart that represents the total number of activities related to changeset, patchset, and approvals submitted  by an organization over a time range. Mouse over a color in the chart to see the total number of data activities for the organization, and their percentage.

### Gerrit Changeset Backlog

NEW Changesets Statistics Summary shows:

Total number of newly created Changesets over time.

Accumulated Open Time in Days\(Status: NEW\) shows cumulative number of days for which each newly created changeset was open.

Average Open Time in Days per Changeset \(Status: NEW\) shows average number of days for which each newly created changeset was open.

Backlog: Accumulated Days waiting to be Closed shows a bar graph that represents the cumulative number of days for which individual changesets are open, on a particular date. Mouse over a color in the graph to see the accumulated number of days issues were waiting to be closed on a date.

Backlog: New Changesets waiting to be Closed shows a bar graph that represents the number of newly opened changesets that are yet to be closed, on a particular day.

Changeset Backlog Percentage By Organization shows a doughnut chart that represents the total number of newly created changesets accumulated by an organization over a time range. Mouse over a color in the chart to see the total number of changesets, and their percentage.

Changeset Submitters shows a table that lists

Submitters: Name of the submitter

Changesets: Total number of changesets submitted by the submitter for the entire project

Projects: Total number of projects the submitter is submitting changeset for

Avg Patchsets: Average number of patchsets submitted by a submitter over time. 

### GitHub Issues Efficiency

**Efficiency Closing GitHub Issues** lets you select and organization and project as values for the dashboard data.

**Backlog Management Index** shows a multi-line graph that represents the Backlog Management Index \(BMI\). BMI is the number of closed issues divided by the number of open ones in a given period of time. Moving Avg. is set to 8 weeks to identify changes in trends. Average is also shown as a reference. BMI values greater than 1 mean the community is closing more issues than those they are opening. Values less than 1 mean the opposite—more issues are open than those closed during a given time frame. Mouse over this graph or **Lead Time** to show a line that displays the date and time at the top of the legend..

**Lead Time** shows a multi-line graph that represents the Average Time to Close issues expressed in days and what the trend is. This graph helps you to identify peaks and visualize the time spent in closing issues.

**Time to Close** shows a gauge that represents the time from issue creation to the moment in which it is closed. The gauge is set to show green color for less than 7 days, yellow for values from 7 to 30 days, and red from 30 to 90 days. This color scheme means that a week is considered as a good time to close. The color scheme is just a visual reference and you can always rely on the number, ignoring this color scheme.

**Median Time To Close Issues By Repositories** shows a table that lets you sort values by Repository and 50th percentile of Median Time Open \(days\).







