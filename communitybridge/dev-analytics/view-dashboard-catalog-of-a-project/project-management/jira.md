# Jira

The Jira dashboards under **Issue Management** represents a set of metrics that shows an analysis of Jira issues . Following are the various dashboards of Jira dashboard:

* [Overview](jira.md#overview)
* [Backlog](jira.md#backlog)
* [Effort](jira.md#effort)
* [Timing](jira.md#timing)

## Overview

Overview shows information about issues in repositories and who submitted the issues and when. For each commit, information about the corresponding organization is also provided.

**Summary** shows total number of issues, submitters , and projects.

**Issues by Status** shows a stacked bar graph that represents the number of issues by status per day over time. Issue statuses are color code. Mouse over a color in the graph to see the total number of issues by status that occurred on a date.

**Issues by Organization** shows a bar graph that represents the number of issues by organization per day over time. Organizations are color code. Mouse over a color in the graph to see the total number of issues for the organization on a date.

**Submitters** hows a bar graph that represents the number of submitters per day over time. Mouse over a color in the graph to see the total number of submitters and the date.

**Submitters by Organization** shows a doughnut chart that represents the organizations that submitted issues \(not unique issues; it includes activities on issues, such as comments, approvals, and so on\) in the project. Mouse over a color in the chart to see the total number of submitters for the organization, and their percentage of the project's organization.

**Assignees by Organization** shows a doughnut chart that represents the organizations that are assigned with the issues \(not unique issues; it includes activities on issues, such as comments, approvals, and so on\) in the project. Mouse over a color in the chart to see the total number of assignees for the organization, and their percentage of the project's organization.

**Projects** shows a table that lets you sort values by project name, number of issues, submitters, assignees, average number of watchers, and average time in days to close the issues per project over time.

**Submitters** shows a table that lets you sort values by submitters names, number of issues, projects, assignees, and average number of days the issues were open per submitter over time .

## Backlog

Backlog focuses on open issues \(data is retrieved at the moment of dashboard creation\), their accumulated time, and associated organization.

**Summary** shows the total number of open issues, accumulated time in days while issues were open, and the average time in days per open issue over time.

**Issues By Projects** shows a table that lets you sort values by project name, number of issues and average time in days the issue were open per project over time.

**Accumulated Time \(days\): Issues waiting to be closed** shows a bar graph that represents cumulative number of days for which individual issues were open, on a date. Mouse over a color in the graph to see the data.

**Issues waiting to be closed** shows a stacked bar graph that represents number of issues \(that are not closed\) per day by status: Open, In Progress, To Do, and so on. These statuses are color coded. Mouse over a color in the graph to see the total number of issues by status that occurred on a date.

**Issues By Organizations** shows a table that lets you sort values by organization name, number of issues, average time in days the issues were open per organization over time, and average number of watchers per issue over time.

**Assignee Organizations** shows a doughnut chart that represents the assigned organizations that have open issues to be closed. Mouse over a color in the chart to see the total number of assignees for the organization, and their percentage of the project's organization.

**Issues Submitters** shows a table that lets you sort values by submitter name, number of issues, average time in days the issue was open for the submitter, and number of projects the submitter is associated with.

**Issue Backlog Summary** shows a table that lets you sort values by title, Info, repository, submitter, and total number of days the issue backlog was open. The default sort is by the greatest number of open days.

## Effort

Effort shows data about authors and assignees, and their effort in hours per project and organization.

**Summary** shows the total number of Items, Authors, Assignees, Total Hours Estimated, Total Hours Remaining, and Total Hours Logged for the project.

**Assigned Organizations** shows a doughnut chart that represents the total number of assignees per organization. Mouse over a color in the chart to see the total number of assignees per organization, and the percentage of assignees for that organization out of the total assignees.

**Estimated by Repository** shows a doughnut chart that represents the total number of estimated hours per repository. Mouse over a color in the chart to see the total number of estimated hours per repository, and the percentage of estimated hours for that repository out of the total hours.

**Logged by Repository** shows a doughnut chart that represents the total number of logged hours per repository. Mouse over a color in the chart to see the total number of logged hours per repository, and the percentage of logged hours for that repository out of the total hours.

**Effort \(hours\)** shows a stacked bar graph that represents the effort expressed in the number of estimated, remaining, and logged hours over time. Mouse over a color in the graph to see the total number of hours: Estimated, Remaining, or Logged for a date.

**Effort \(hours, cumulative sum\)** shows a multi-line graph that represents the effort expressed in the number of time estimated, time remaining and time logged hours over time. Mouse over a color in the graph to see a vertical line that represents the time and date, and shows the total number of hours: Estimated, Remaining, or Logged for that date.

**Averages and Medians** shows a table that lets you sort values by Avg. Hours Estimated, Avg. Hours Remaining, Avg. Hours Logged, 50th percentile of Median Hours Estimated, 50th percentile of Median Hours Remaining, and 50th percentile of Median Hours Logged. The 50th percentile number indicates the median number of hours estimated or remaining. A 50th percentile is the same as a median.

**Remaining by Repository** shows a doughnut chart that represents the total number of remaining hours per repository. Mouse over a color in the chart to see the total number of remaining hours per repository, and the percentage of remaining hours for that repository out of the total hours.

**Effort by Author and Assignee \(hours\)** shows a table that lets you sort values by authors, assignees, URL, and estimated, remaining, and logged hours.

**Effort by Organization \(hours\)** shows a table that lets you sort values by organization name, number of issues, submitters, assignees, average number of watchers, Avg. Estimated Time \(hours\), Avg. Logged Time \(hours\), and Avg. Remaining Time \(hours\) per organization,.

**Effort by Repository \(hours\)** shows a table that lets you sort values by Repository, Issues, Submitters, Assignees, Avg. Num. Watchers, Avg. Estimated Time \(hours\), Avg. Logged Time \(hours\), and Avg. Remaining Time \(hours\).

## Timing

Timing shows information about open and closed issues in time and lets you focus on how long Issues remain open. Statistical information shows the 50th percentile of median time open in days. The number indicates the median number of days that issues were open. This number indicates that 50 percent of the issues were open longer than that number and 50 percent of the issues were below that number. A 50th percentile is the same as a median.

**Summary** shows the total number of Issues, Submitters, Assigned, 50th percentile of Median Open Days, and Avg. Open Days.

**Issues Open in Median** shows a bar graph that represents number of days for which the median number of total issues that were created per day over time, are open. Mouse over a color in the graph to see the median number of days issues were open on a date.

**Issues Open \(best 80 percent of them\)** shows a bar graph that represents number of days for which the 80th percentile of total number of issues that were created per day over time, are open. Mouse over a color in the graph to see the 80th percentile number of days issues were open on a date.

**Issue Count By Status** shows a doughnut chart that represents the total number of issues in the project by status: closed, open, to do, and so on. Statuses are color code. Mouse over a color in the chart to see the status, total number of issues for the status, and the percentage of the project's issues for that status.

**Organizations** shows a table that lets you sort values by organization name, number of issues, submitters, assignees, 50th percentile of Median Time Open Days, and 50th percentile of Median Changes per organization over time.

**Projects** shows a table that lets you sort values by project name, number of issues, submitters,  assignees, 50th percentile of Median Time Open Days, and 50th percentile of Median Changes per project over time.

**Issues** shows a table that lets you sort values by Summary, Submitter, Status, Project, +Info, Open Date, and Open Days.

