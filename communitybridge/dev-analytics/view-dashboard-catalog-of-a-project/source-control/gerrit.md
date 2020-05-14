# Gerrit

The Gerrit dashboards represent a set of metrics that shows detailed information about changesets and patchsets per changeset. Following are the various dashboards of Gerrit data source:

* [Overview](gerrit.md#overview)
* [Efficiency](gerrit.md#efficiency)
* [Timing](gerrit.md#timing)
* [Approvals](gerrit.md#approvals)
* [Backlog](gerrit.md#backlog)

By default, Bots and Changesets Only filters are applied. Click ![](../../../../.gitbook/assets/share-icon.png) to share the path for respective dashboards.

## Overview

Overview shows visualizations that provide information about changeset statuses, submitters, and organizations. Changeset information per organization and repository is also shown.

**Summary** shows the total number of changesets, total number of individuals who submitted changesets, total number of repositories, and average time in days to review the first changeset.

**Changesets Statistics \(Open Time in Days\)** shows the total number of days for which changesets \(by percentile\) are open. **Percentile rank 4 of "timeopen"** shows the percentage of changesets that were open for less than 4 days.   
The percentile rank of a score is the percentage of scores in its frequency distribution that are equal to or lower than it.

**Patchset Statistics per Changeset** shows the total number of patchsets \(by percentile\) per changeset with reference to the total number of changesets in the project. **Percentile rank 4 of "patchsets per review"** shows the percentage of patchsets that were reviewed per changesets that were open for less than 4 days.  
The percentile rank of a score is the percentage of scores in its frequency distribution that are equal to or lower than it.

**Changesets By Status** shows a stacked bar graph that represents the number of changesets by status—MERGED, ABANDONED, NEW, DRAFT— that were started per day. Mouse over a color in the graph to see the status along with its number, and the date the changesets was started.

**Changeset Submitters** shows a bar graph that represents total number of changeset submitters per day over time. Mouse over a color in the graph to see the number for a date.

**Authors Percentage By Organization** shows a doughnut chart that represents the total number of changesets per organization over time. Mouse over a color in the chart to see the total number of changesets per organization, and the percentage of changesets for that organization out of the total number.

**Organizations** shows a stacked bar graph that represents the number of changesets by an organization per day over time. Mouse over a color in the graph to see the total number of changesets for the organization and the date.

**Changeset Percentage By Status** shows a doughnut chart that represents the total number of changesets in the project by status: MERGED, ABANDONED, NEW, DRAFT. Mouse over a color in the chart to see the status, total number, and percentage of changesets by status.

**Patchsets per Changeset** shows a stacked bar graph that represents the number of patchsets \(by percentile\) per changeset for a day. Mouse over a color in the graph to see the total number of patchsets per percentile.

**Submitters** shows a table that lets you sort values by:

* Submitter: Name of the submitter
* Changesets: Total number of changesets submitted by the submitter for the entire project
* Projects: Total number of projects the submitter has submitted changeset to
* Avg Patchsets: Average number of patchsets submitted by a submitter over time. 

**Repositories** shows a table that lets you sort values by: 

* Repository: Name of the repository
* Changesets: Total number of changesets submitted to the repository
* Submitters: Number of contributors who submitted changesets to the repository

## Efficiency

Efficiency offers a view of efficiency closing reviews based on metrics: Review Efficiency Index \(REI\), Time to Merge, and Lead Time.

**Efficiency Closing Gerrit Reviews** lets you select an Organization and Repository as values for the dashboard data.

**Review Efficiency Index** shows a multi-line graph that represents the REI. REI is the number of closed reviews divided by the number of open ones in a given period of time. This visualization measures efficiency closing reviews. REI Moving Avg. \(8 weeks\) identifies changes in trends. Average is also shown as a reference. REI values greater than 1 mean the community is closing more reviews than those they are opening. Values smaller than 1 mean the opposite—more reviews open than those closed during a given time frame. Mouse over this graph or **Lead Time** to show a line that displays the date and time at the top of the legend.

![](../../../../.gitbook/assets/18088226.png)

**Repositories** shows a table that displays the number of days 50th percentile of repository's reviews or changesets are open before they are closed. It gives an insight on the efficiency of closing reviews per repository.

**Time to Merge** shows a gauge that represents the time from issue creation to the moment in which it is merged. The gauge is set to show green color for less than 7 days, yellow for values from 7 to 30 days, and red from 30 to 90 days. This color scheme means that a week is considered as a good time to merge. The color scheme is just a visual reference and you can always rely on the number, ignoring this color scheme.

**Lead Time** shows a multi-line graph that represents the average Time to Merge expressed in days together to its trend. This helps to identify peaks and visualize the time spent in closing reviews.  Mouse over this graph or **REI** to show a line that displays the date and time at the top of the legend.

## Timing

Timing shows information about open and closed changesets over time. The dashboard focuses on how long changesets remain open. Statistical information provides closing times and also tables with the latest and the oldest changesets.

**Gerrit Timing Summary** shows the total number of Changesets, Changeset Submitters, Repositories, and Average time in days to review the first changeset.

**Changesets Open in Median** shows a bar graph that represents number of days for which 50% of total number of changesets are open. Mouse over a color in the graph to see the data.

**Changesets Open \(best 80 percentile\)** shows a bar graph that represents number of days for which 80% of total number of changesets are open. Mouse over a color in the graph to see the data.

**Status** shows a doughnut chart that represents the total number of changesets in the project by status: MERGED, ABANDONED, NEW, DRAFT. Mouse over a color in the chart to see the status, total number of changesets for the status, and the percentage of the project's changesets for that status.

**Organizations** shows a doughnut chart that represents the total number of activities related to changeset, patchset, and approvals submitted  by an organization over a time range. Mouse over a color in the chart to see the total number of data activities for the organization, and their percentage.

**Submitters** shows a table that lists

* Submitter: Name of the submitter
* Changesets: Total number of changesets submitted by the submitter
* Avg. Patchsets: Average number of patchsets submitted by the submitter over time
* Avg. Time Open \(Days\): Average number of days that the submitter's changesets are open

**Repositories** shows a table that lists repository name, total number of changesets submitted to the repository, and total number of submitters of the repository.

**Changesets** shows a table that shows changeset URLs for the project. For each changeset, the table shows summary, number of days for which the changeset was open, submitter's name, changeset status, and the date the changeset was opened. You can click a URL to go to the changeset in the project.

## Approvals

Approvals shows statistics about changesets that are approved. The dashboard shows reviewers, repository names, numbers of respective data, and so on.

**Total Changesets and Approvals** shows total number of changesets submitted for the project, and the total number of approvals made for the changesets.

**Approvals by Reviewer** shows a table that lists reviewer's name, number of changesets approved by the reviewer, and number of code review ratings \(-2, -1, 1, 2\) given by the reviewer over time.

**Activity by Repository** shows a table that lists repository name, total number of changesets and patchsets pushed to the repository, and the total number of approved commits.

**Approvals by Reviewer Per Repo** shows a table that lists reviewer name, corresponding repository name, number of changes approved by the reviewer, and number of code review ratings \(-2, -1, 1, 2\) given by the reviewer for the repository over time.

**Approvals by Submitter** shows a table that lists submitter name, total number of changesets and patchsets that are approved for the submitter, and number of code review ratings \(-2, -1, 1, 2\) received by the submitter out of the total number of approved commits over time.

## Backlog

Backlog focuses on open changesets \(data is retrieved at the moment of dashboard creation\), their accumulated time, and associated organizations.

**NEW Changesets Statistics Summary** shows:

* Total number of newly created Changesets over time.
* Accumulated Open Time in Days\(Status: NEW\) shows cumulative number of days for which each newly created changeset was open.
* Average Time Open in Days over time per Changeset \(Status: NEW\) shows average number of days for which each newly created changeset was open.

**Backlog** shows a table that shows backlog URLs for the project. For each backlog, the table shows the backlog summary, the submitter name, the date and time the changeset was opened, and the number of days that the backlog was open. You can click a URL to go to the changeset in the project.

**Backlog: Accumulated Days waiting to be Closed** shows a bar graph that represents the cumulative number of days for which individual changesets are open, on a particular date. Mouse over a color in the graph to see the accumulated number of days issues were waiting to be closed on a date.

**Backlog: New Changesets waiting to be Closed** shows a bar graph that represents the number of newly opened changesets that are yet to be closed, on a particular day.

**Percentage of Backlog Accumulated By Organization** shows a doughnut chart that represents the total number of newly created changesets accumulated by an organization over a time range. Mouse over a color in the chart to see the total number of changesets, and their percentage.

**Changeset Submitters** shows a table that lists

* Submitters: Name of the submitter
* Changesets: Total number of changesets submitted by the submitter for the entire project
* Projects: Total number of projects the submitter is submitting changeset for
* Avg Patchsets: Average number of patchsets submitted by a submitter over time. 

**Organizations** shows a table that lists the organization name, and total number of changesets submitted by the organization.

