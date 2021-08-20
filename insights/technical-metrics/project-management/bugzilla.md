# Bugzilla

{% hint style="info" %}
By default, Bot Commits are filtered, however, you can include the filter value by navigating to the filter section of dashboard. For details, see [Add and Manage Data Filters](../../filter-data/add-and-manage-data-filters.md).
{% endhint %}

Click ![](../../../.gitbook/assets/get-short-url.png) to copy the path of respective dashboards.

The Bugzilla dashboard is available from the **Issue Management** drop-down list, and represents the following dashboards:

* [Overview](bugzilla.md#Bugzilla-Bugzilla>Overview)
* [Backlog](bugzilla.md#backlog)
* [Timing](bugzilla.md#timing)

## Overview <a id="Bugzilla-Bugzilla&gt;Overview"></a>

Overview shows information about issues and submitters in Bugzilla organizations.

**Filter** lets you filter the dashboard data by submitter name, organization name, and project. Select values from the respective drop-down lists, and click **Apply changes** to filter the dashboard as per selection.

**Issues** shows the total number of Issues, Submitters, and Products.

**Issues by Status Over Time** shows a stacked bar graph that represents the number of issues by status per day over time such as: RESOLVED, CONFIRMED, IN\_PROGRESS, VERIFIED, UNCONFIRMED. Mouse over a color in the graph to see the total number of issues by status that occurred on a date.

**Submitters by Organization** shows a doughnut chart that represents the total number of submitters in the project by organization. Mouse over a color in the chart to see the total number of submitters for the organization, and their percentage of the project's organization.

**Projects** shows a table that lets you sort values by Organizations, Issues, Submitters, Assignees, Avg. Time to close \(days\) and Avg. Updates.

**Submitters Over Time** shows a bar graph that represents the number of submitters per day over time. Mouse over a color in the graph to see the total number of submitters that occurred on a date.

**Submitters** shows a table that lets you sort values by Submitter, Issues, Products, and Avg. Open Days.

**Issues by Organization Over Time** shows a stacked bar graph that represents the number of issues by organization per day over time. Mouse over a color in the graph to see the total number of issues that occurred on a date for the organization.

**Organizations** shows a table that lets you sort values by organization name, number of issues, submitters, assignees, average time to close \(days\) issues, and average updates per product.

## Backlog

Backlog focuses on open issues, their accumulated time, and associated organizations.

**Open Issues Statistics** shows total number of open issues, accumulated time in days for all open issues, and average time in days an issue is open.

**Issues waiting to be closed** shows a stacked bar graph that represents number of issues \(that are not closed\) per day by status: New, Unconfirmed, Assigned, and so on. These statuses are color coded. Mouse over a color in the graph to see the total number of issues by status that occurred on a date.

**Backlog** shows a table that lets you sort values by title, URL, number of comments, updates, days of open, and date of open for an issue backlog.

**Accumulated Time \(days\): Issues waiting to be closed** shows a bar graph that represents cumulative number of days for which individual issues were open, on a date. Mouse over a color in the graph to see the data.

**Assignee Organizations** shows a doughnut chart that represents the assigned organizations that have open issues to be closed. Mouse over a color in the chart to see the total number of assignees for the organization, and their percentage.

**Backlog Submitters** shows a table that lets you sort values by submitter name, number of issues, average time in days the issue was open for the submitter, and number of projects the submitter is associated with.

**Projects** shows a table that lets you sort values by project name, number of open issues, and average time in days the issues are open.

**bugzilla\_openissues\_per\_organization** shows a table that lets you sort values by organization name, number of open issues, and average time in days the issues are open for an organization.

## Timing

Timing shows information about open and closed issues in time and lets you focus on how long Issues remain open. Statistical information shows the 50th percentile of median time open in days. The number indicates the median number of days that issues were open. This number indicates that 50 percent of the issues were open longer than the total number and 50 percent of the issues were below the total number. A 50th percentile is the same as a median.

**Summary** shows the total number of Issues, Submitters, Assignees, 50th percentile of Median Open Days.

**Median Open Time \(days\)** shows a stacked bar graph that represents number of days for which the median or 50th percentile of total issues that were created per day over time, are open. Mouse over a color in the graph to see the median number of days issues were open on a date.

**80 percent Open Time \(days\)** shows a stacked bar graph that represents number of days for which the 80th percentile of total number of issues that were created per day, are open. Mouse over a color in the graph to see the 80th percentile number of days issues were open on a date.

**Issues** shows a stacked bar graph that represents the total number of issues over time in the project by status: closed, open, resolved, in progress, and so on. Mouse over a color in the graph to see the status, the total number of issue for the status, and the date.

**Issue By Status** shows a doughnut chart that represents the total number of issues in the project by status: closed, open, resolved, in progress, and so on. Statuses are color code. Mouse over a color in the chart to see the status, total number of issues for the status, and the percentage of that status.

**Issues Assigned by Organization** shows a doughnut chart that represents the total number of issues assigned by an organization. Mouse over a color in the chart to see the number of issues, and their percentage for an organization.

**Issues By Resolution** shows a doughnut chart that represents the number and percentage of issues by resolution status—Fixed, Duplicate, Invalid, Notabug. Mouse over a color to see the data.

**Issues By Severity** shows a doughnut chart that represents the number and percentage of issues by severity status—normal, enhancement, critical, major. Mouse over a color to see the data.

**Submitters** shows

* a bar graph that represents the total number of submitters over time for the project. Mouse over a color in the graph to see total number of submitters for a date.
* a table of submitters and their corresponding number of Issues, products, and Avg. Open Days.

**Organizations** shows a table that lets you sort values by organization name, number of open issues, submitters, assignees, and verage time in days issues are open for an organization.

**Projects** shows a table that lets you sort values by project name, number of open issues, submitters,  assignees, products, and verage time in days issues are open for an organization.

Products shows a table that lets you sort values by product name, number of open issues, submitters, assignees, and average time in days issues are open.

**Latest Issues** shows a table listing issues by Title, Product, Submitter, URL, Id, and Created on. The default sort is by most recently created issue.

