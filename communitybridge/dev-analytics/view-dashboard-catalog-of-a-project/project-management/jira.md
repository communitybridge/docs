# Jira

The Jira dashboards are available from the **Project Management** drop-down list, and represent a set of metrics that shows an analysis of Jira issues . Following are the various dashboards of Jira dashboard:

* [Overview](jira.md#overview)
* [Backlog](jira.md#backlog)
* [Effort](jira.md#effort)
* [Timing](jira.md#timing)

## Overview

Overview shows information about issues in repositories and who submitted the issues and when. For each commit, information about the corresponding organization is also provided.

**Issues** shows the \# Issues, \# Submitters, and \# Projects.

**Issues by Status, over time** shows a stacked bar graph that represents the number of issues by status per day over time. Mouse over a color in the graph to see the total number of issues by status that occurred on a date.

**Issues by Organization, over time** shows a bar graph that represents the number of issues by organization per day over time. Mouse over a color in the graph to see the total number of issues for the organization on a date.

**Submitters, over time** shows a bar graph that represents the number of submitters per day over time. Mouse over a color in the graph to see the total number of submitters and the date.

**Submitters by Organization** shows a doughnut chart that represents the total number of submitters in the project by organization. Mouse over a color in the chart to see the total number of submitters for the organization, and their percentage of the project's organization.

**Assignees by Organization** shows a doughnut chart that represents the total number of assignees of an organization in the project. Mouse over a color in the chart to see the total number of assignees for the organization, and their percentage of the project's organization.

**Projects** shows a table that lets you sort values by Project, Issues, Submitters, Assignees, Avg. Time to close \(days\), and Avg. Num. Watchers.

**Submitters** shows a table that lets you sort values by Submitters, Issues, Repositories, Assignees, and Avg. Open Days.

## Backlog

Backlog focuses on open issues \(data is retrieved at the moment of dashboard creation\), their accumulated time, and associated organization.

**Open Issues Statistics** shows the total number of Open Issues, Accumulated Open Days, and the Average Time Open Days per Issue.

**Backlog** shows a table that lets you sort values by Title, Info, Repository, Submitter, and Days Open. The default sort is by the greatest number of open days.

**Issues waiting to be closed** shows a stacked bar graph that represents the number of issues that are not closed per day over time by status: Open or In Progress. Mouse over a color in the graph to see the total number of issues by status that occurred on a date.

**Accumulated Time \(days\): Issues waiting to be closed** shows a bar graph that represents the number of issues by accumulated open days per day over time. Mouse over a color in the graph to see the accumulated number of days issues were waiting to be closed on a date.

**Assignee Organizations** shows a doughnut chart that represents the total number of assignees in the project by organization. Mouse over a color in the chart to see the total number of assignees for the organization, and their percentage of the project's organization.

**Backlog Submitters** shows a table that lets you sort values by Submitters, Issues, Avg. Time Open Days, and Repositories, which is the number of repositories per submitter.

**Organizations** shows a table that lets you sort values by Organization, Issues, Avg. Time Open \(Days\), and Avg. Num. Watchers.

**Repositories** shows a table that lets you sort values by Repository, Issues, and Avg. Time Open \(Days\).

## Effort

SUMMARY: Effort shows data about authors and assignees, and their effort in hours per repository and organization.

**Summary** shows the \# Items, \# Authors, \# Assignees, Total Hours Estimated, Total Hours Remaining, and Total Hours Logged.

**Assigned Organizations** shows a doughnut chart that represents the total number of assignees per organization. Mouse over a color in the chart to see the total number of assignees per organization, and the percentage of assignees for that organization out of the total assignees.

**Estimated by Repository** shows a doughnut chart that represents the total number of estimated hours per repository. Mouse over a color in the chart to see the total number of estimated hours per repository, and the percentage of estimated hours for that repository out of the total hours.

**Logged by Repository** shows a doughnut chart that represents the total number of logged hours per repository. Mouse over a color in the chart to see the total number of logged hours per repository, and the percentage of logged hours for that repository out of the total hours.

**Remaining by Repository** shows a doughnut chart that represents the total number of remaining hours per repository. Mouse over a color in the chart to see the total number of remaining hours per repository, and the percentage of remaining hours for that repository out of the total hours.

**Effort \(hours\)** shows a stacked bar graph that represents the effort expressed in the number of estimated, remaining, and logged hours over time. Mouse over a color in the graph to see the total number of hours: Estimated, Remaining, or Logged for a date.

**Effort \(hours, cumulative sum\)** shows a multi-line graph that represents the effort expressed in the number of time estimated, time remaining and time logged hours over time. Mouse over a color in the graph to see a vertical line that represents the time and date, and shows the total number of hours: Estimated, Remaining, or Logged for that date.

**Averages and Medians** shows a table that lets you sort values by Avg. Hours Estimated, Avg. Hours Remaining, Avg. Hours Logged, 50th percentile of Median Hours Estimated, 50th percentile of Median Hours Remaining, and 50th percentile of Median Hours Logged. The 50th percentile number indicates the median number of hours estimated or remaining. A 50th percentile is the same as a median.

**Effort by Author and Assignee \(hours\)** shows a table that lets you sort values by authors, assignees, URL, and estimated, remaining, and logged hours.

**Effort by Organization \(hours\)** shows a table that lets you sort values by Organization, Issues, Submitters, Assignees, Avg. Num. Watchers, Avg. Estimated Time \(hours\), Avg. Logged Time \(hours\), and Avg. Remaining Time \(hours\).

**Effort by Repository \(hours\)** shows a table that lets you sort values by Repository, Issues, Submitters, Assignees, Avg. Num. Watchers, Avg. Estimated Time \(hours\), Avg. Logged Time \(hours\), and Avg. Remaining Time \(hours\).

## Timing

Timing shows information about open and closed issues in time and lets you focus on how long Issues remain open. Statistical information shows the 50th percentile of median time open in days. The number indicates the median number of days that issues were open. This number indicates that 50 percent of the issues were open longer than that number and 50 percent of the issues were below that number. A 50th percentile is the same as a median.

**Jira Summary** shows the \# issues, \# Submitters, \# Assigned, 50th percentile of Median Open Days, and Avg. Open Days.

**Issues Open in Median** shows a bar graph that represents the median number of issues that were created per day over time. Mouse over a color in the graph to see the median number of days issues were open on a date.

**Issues Open \(best 80 percent of them\)** shows a bar graph that represents the 80th percentile number of issues that were open per day over time. Mouse over a color in the graph to see the 80th percentile number of days issues were open on a date.

**Status** shows a doughnut chart that represents the total number of issues in the project by status: closed or open. Mouse over a color in the chart to see the status, total number of issues for the status, and the percentage of the project's issues for that status.

**Assigned Organization** shows a doughnut chart that represents the total number of organizations in the project. Mouse over a color in the chart to see the total number of submitters for the organization, and their percentage of the project's organization.

**Issues** shows a stacked bar graph that represents the total number that represents issues over time in the project by status: Closed, Done, Open, Delivered, In Progress, To Do, Submitted, and REOPENED. Mouse over a color in the graph to see the status, total number of issue for the status, and the date.

**Submitters** shows a bar graph that represents the total number of submitters over time in the project. Mouse over a color in the graph to see the status, total number of submitters, and the date.

**Organizations** shows a table that lets you sort values by Organization, Issues, Submitters, Assignees, 50th percentile of Median Time Open Days, and 50th percentile of Median Changes.

**Submitters** shows a table that lets you sort values by Submitters, Issues, Repositories, Assignees, and Avg. Open Days.

**Projects** shows a table that lets you sort values by Projects, Issues, Submitters,  Assignees, 50th percentile of Median Time Open Days, and 50th percentile of Median Changes

**Closed Issues by Repository** shows a table that lets you sort values by Repository, Issues Open, Submitters, Assignees, 50th percentile of Median Time Open Days, and 50th percentile of Median Changes.

**Issues** shows a table that lets you sort values by Summary, Submitter, Status, Project, +Info, Open Date, and Open Days.

