# Gerrit Changeset

{% hint style="info" %}
By default, Bots and Changesets Only are filtered. Dashboard shows data only for number of changesets, not for comments, approvals, and other values. Empty changesets— Changesets that have value as zero— are also filtered. To add/manage filters, see [Add and Manage Data Filters](../../../filter-data/add-and-manage-data-filters.md).
{% endhint %}

The Gerrit Changesets dashboards represent a set of metrics that shows detailed information about changesets and patchsets per changeset. Following are the various dashboards of Gerrit data source:

* [Overview](gerrit-changeset.md#overview)
* [Efficiency](gerrit-changeset.md#efficiency)
* [Timing](gerrit-changeset.md#timing)
* [Backlog](gerrit-changeset.md#backlog)
* [Approvals](gerrit-changeset.md#approvals)
* [Reviews](gerrit-changeset.md#reviews)

By default, **Bots** and **Changesets Only** filters are applied. To apply more filters, see [add and manage data filters](../../../filter-data/add-and-manage-data-filters.md).

Click ![](../../../../.gitbook/assets/get-short-url.png) to copy the path of respective dashboards.

## Overview

Overview shows visualizations that provide information about changeset statuses, submitters, and organizations. Changeset information per organization and repository is also shown.

**Filter** lets you filter the dashboard data by author name, organization name, and repository. Select values from the respective drop-down lists, and click **Apply changes** to filter the dashboard as per selection.

**Summary** shows total number of changeset submitters, repositories the changesets belong to, new changesets, merged changesets, and total number of abandoned changesets.

**Changeset Percentage By Status** shows a doughnut chart that represents the total number of changesets in the project by status: MERGED, ABANDONED, NEW, DRAFT. Mouse over a color in the chart to see the status, total number, and percentage of changesets by status.

**Changeset Percentage By Organization** shows a doughnut chart that represents the total number and percentage of changesets submitted by an organization over time. Mouse over a color in the chart to see details.

**Changesets By Status** shows stacked line graphs that represent the increase or decrease in the number of changesets by status—MERGED, ABANDONED, NEW, DRAFT— that were started per day. Mouse over a color in the graph to see the status along with its number, and the date the changesets was started.

**Changeset Submitters** shows stacked line graphs that represent increase or decrease in the total number of changeset submitters over time along with the number of organizations the submitters belong to. Mouse over a color in the graph to see the numbers for a date.

**Patchsets per Changeset** shows stacked line graphs that represent the 50th, 75th, and 95th percentile of patchsets created per changeset in a given timeframe. Mouse over a color in the graph to see number of patchsets.

**Changesets By Organizations** shows a stacked bar graph that represents the number of changesets submitted by an organization over time. Mouse over a color in the graph to see details.

**Submitters** shows a table that lists name of the submitters, total number of changesets submitted by the submitter, total number of new, merged, and abandoned changesets per submitter. It also lists average number of patchsets over total number of changesets submitted by a submitter over time.

**Organizations** shows a table that lists organization names, number of submitters from the organization, total number of changesets submitted by the organization's submitters, number of changesets in different stages, such as new, merged, and abandoned, and average number of patchsets over total number of changesets submitted by an organization over time.

**Repositories** shows a table that lists name of the repository, total number of changesets submitted to the repository, number of contributors who submitted changesets to the repository, number of changesets in different stages, such as new, merged, and abandoned, and average number of patchsets over total number of changesets submitted by to the repository over time.

**Latest Changeset Activity** shows a table that lists changeset URL, changeset submitter's name, affiliated organization of the changeset submitter, status of the changeset, number of patchsets created for the changeset, and date and time when the changeset was updated.

## Efficiency

Efficiency offers an overall view of understanding and optimizing project efficiency in closing/merging Gerrit Changesets.

**Filter** lets you filter the project data by organization name, author name, and repository name. Select values from the respective drop-down lists, and click **Apply changes** to filter the dashboard as per selection.

**Summary** shows a cluster of

* 50th percentile of Time To Merge \(Days\): The number of days it took to merge 50 percent of the changesets.
* 95th percentile of Time To Merge \(Days\): The number of days it took to merge 95 percent of the changesets.
* Merged Changesets: Total number of changesets merged over time.
* Organizations: Total number of organizations whose submitters authored the merged changesets.
* Submitters: Total number of submitters whose changesets were merged.
* Repositories: Total number of repositories the merged changesets belonged to.

**Time to Merge** shows line graphs that represent number of changesets that took certain amount of time to get merged. These time slots are divided into four categories, such as less than 1 day, 1 to 7 days, 7 to 30 days, and more than 30 days. Hover mouse over the graph to view number of of PRs along with the time taken to get merged.

* Less than 1 day: The number of changesets merged in less than one day.
* 1 to 7 days: The number of changesets merged in more than one day but less than seven days.
* 7 to 30 days: The number of changesets merged in more than seven days but less than thirty days.
* More than 30 days: The number of changesets merged in more than thirty days.

**Repositories** shows a table that lists repositories, total number of merged changesets along with the time it took for 50% and 95% of the changesets to get merged per repository. Click a repository to navigate to GitHub to view details.

## Timing

Timing shows information about open and closed changesets over time. The dashboard focuses on how long changesets remain open. Statistical information provides closing times and also tables with the latest and the oldest changesets.

**Filter** lets you filter the dashboard data by repository, author who submitted changesets, and author who approved the changesets. Select values from the respective drop-down lists, and click **Apply changes** to filter the dashboard as per selection.

**Gerrit Timing Summary** shows the total number of Changesets, Changeset Submitters, Repositories, and Average time in days to review the first changeset.

**Changesets Merged By Organization** shows graphs that display number of changesets merged by organizations over a period of time. Mouse over a color to view details related to an organization.

**Changesets Open in Median** shows a line graph that represents number of days for which 50% of total number of changesets are open. Mouse over a color in the graph to see the data.

**Changesets Open \(best 80 percentile\)** shows a line graph that represents number of days for which 80% of total number of changesets are open. Mouse over a color in the graph to see the data.

**Submitters** shows a table that lists name of the submitters, total number of changesets submitted by the submitter, average number of patchsets submitted by the submitter over time, and average number of days that the submitter's changesets are in open state.

**Repositories** shows a table that lists repository name, total number of changesets submitted to the repository along with total number of submitters to the repository.

**Changesets** shows a table that shows changeset URLs for the project. For each changeset, the table shows summary, number of days for which the changeset was open, submitter's name, changeset status, and the date the changeset was opened. You can click a URL to go to the changeset in the project.

## Backlog

Backlog focuses on open changesets \(data is retrieved at the moment of dashboard creation\), their accumulated time, and associated organizations.

**Filter** lets you filter the dashboard data by author name, organization name, and repository. Select values from the respective drop-down lists, and click **Apply changes** to filter the dashboard as per selection.

**Summary** shows total number of new changesets that are in open state, cumulative number of days the changesets have been in open state, and average number of days each changeset has been in open state.

**Backlog: NEW Changesets waiting to be Closed** shows a line graph that shows number of new changesets created over time. Mouse over the graph to view numbers over time.

**Changeset Backlog Percentage By Organization** shows a doughnut chart that displays number and percentage of changesets created by on organization over time. Mouse over a color to view details.

 **Changeset Submitters** shows a table that lists name of submitters, number of changesets, average number patchsets submitted the submitter, and average number of days the changesets are in open state for a submitter.

Organizations shows a table that lists name of the organization, number of changesets, submitters of the organization, and average number of days the changesets are open submitted by an organization.

**Backlog** shows a table that lists backlog URLs for the project. For each backlog, the table shows the backlog summary, the submitter name, the date and time the changeset was opened, and the number of days that the backlog was open. Click a URL to go to the changeset in the project.

## Approvals

Approvals shows statistics about changesets that are approved. The dashboard shows reviewers, repository names, numbers of respective data, and so on.

**Filter** lets you filter the dashboard data by repository, author who submitted changesets and author who approved changesets. Select values from the respective drop-down lists, and click **Apply changes** to filter the dashboard as per selection.

**Total Approvals** shows 

* Approvals: Sum of all approvals given on all the changesets
* Changesets Approved: Number of changesets that were given an approval
* Approvers: The number of reviewers that approved the changesets

**Approvals By Organization** shows a doughnut chart that represents the number and percentage of changesets that are approved by the authors of the organization. Mouse over a color in the chart to view details.

**Reviewers Over Time** shows a graph that represents total number of reviewers who reviewed changesets for the project over time.

**Approvals Over Time** shows graphs that represent number of changesets in different states over time. Mouse over a color to view details.

**Activity by Repository** shows a table that lists name of the repository, total number of changesets, patchsets, and approved changesets per repository.

**Approvals Done by Reviewer** shows a table that lists reviewer name, number of changes approved by the reviewer, and number of code review ratings \(-2, -1, 1, 2\) given by the reviewer for the repository over time.

**Approvals By Reviewer Per Repo** shows a table that lists name of the reviewer, corresponding repository the reviewer worked upon, number of changesets approved by the reviewer for the repository, and number of code review ratings \(-2, -1, 1, 2\) given by the reviewer for the repository over time.

**Approvals Received** shows a table that lists name of the changeset submitter, number of approvals received by the submitter, and number of code review ratings \(-2, -1, 1, 2\) received by the reviewer for the repository over time.

## Reviews

Reviews shows metrics about reviewed changesets. The dashboard shows reviewers, repository names, numbers of respective data, and so on.

**Filter** lets you filter the dashboard data by reviewer name, organization name, and repository. Select values from the respective drop-down lists, and click **Apply changes** to filter the dashboard as per selection.

**Summary** shows the total number of changesets, total number of individuals who reviewed changesets, total number approved changesets, total number of review comments for the submitted changesets, and average time in days to review the first changeset.

**Review Types** shows a doughnut chart that represents the total number of changesets in the project by review status: Comment, Approval, Patchset, and Changeset. Mouse over a color in the chart to see the status, total number, and percentage of changesets by review status.

**Median Time to First Review** shows a graph that represents number of days taken to first review a changeset over a period of time. Mouse over a color in the graph to see the data.

**Median Time to First Approval** shows a graph that represents number of days taken for first approval a changeset over a period of time. Mouse over a color in the graph to see the data.

**Changesets Merged Without Approval** shows graph that displays number of changesets that are merged without approval over a period of time.

**Repository Changeset Review Summary** shows a table that displays review activity per repository, and lets you sort values by repository name, number of submitters and reviewers per repository, number review comments, approvals, and changesets.

**Organization Changeset Review Summary** shows a table that displays review activity per organization, and lets you sort values by organization name, number of submitters and reviewers per organization, number review comments, approvals, and changesets.

**Reviewer Activity** shows a table that displays activities by top reviewers, and lets you sort values by reviewer name, reviewer's organization name, number of approved changesets, and review comments.

