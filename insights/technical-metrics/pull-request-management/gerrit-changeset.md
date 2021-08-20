# Gerrit Changeset

{% hint style="info" %}
By default, Bots and Changesets Only are filtered. Dashboard shows data only for number of changesets, not for comments, approvals, and other values. Empty changesets— Changesets that have value as zero— are also filtered. To add/manage filters, see [Add and Manage Data Filters](../../filter-data/add-and-manage-data-filters.md).
{% endhint %}

The Gerrit Changesets dashboards represent a set of metrics that shows detailed information about changesets and patchsets per changeset. Following are the various dashboards of Gerrit data source:

* [Overview](gerrit-changeset.md#overview)
* [Efficiency](gerrit-changeset.md#efficiency)
* [Timing](gerrit-changeset.md#timing)
* [Backlog](gerrit-changeset.md#backlog)
* [Approvals](gerrit-changeset.md#approvals)
* [Reviews](gerrit-changeset.md#reviews)

By default, **Bots** and **Changesets Only** filters are applied. To apply more filters, see [add and manage data filters](../../filter-data/add-and-manage-data-filters.md).

Click ![](../../../.gitbook/assets/get-short-url.png) to copy the path of respective dashboards.

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

**50th Percentile of Time To Merge By Repo** shows a cloud of top 10 repositories for which it took the most time for 50% of the changesets to get merged. Click  a repository to filter the dashboard data to view metrics related to the repository.

**Time to Merge** shows line graphs that represent number of changesets that took certain amount of time to get merged. These time slots are divided into four categories, such as less than 1 day, 1 to 7 days, 7 to 30 days, and more than 30 days. Hover mouse over the graph to view number of of PRs along with the time taken to get merged.

* Less than 1 day: The number of changesets merged in less than one day.
* 1 to 7 days: The number of changesets merged in more than one day but less than seven days.
* 7 to 30 days: The number of changesets merged in more than seven days but less than thirty days.
* More than 30 days: The number of changesets merged in more than thirty days.

**Repositories** shows a table that lists repositories, total number of merged changesets along with the time it took for 50% and 95% of the changesets to get merged per repository. Click a repository to navigate to GitHub to view details.

## Timing

Timing shows information about open and closed changesets over time. The dashboard focuses on how long changesets remain open. Statistical information provides closing times and also tables with the latest and the oldest changesets.

**Filter** lets you filter the dashboard data by repository, author who submitted changesets, and author who approved the changesets. Select values from the respective drop-down lists, and click **Apply changes** to filter the dashboard as per selection.

**Summary** shows the total number of changeset submitters, number of new, merged, and abandoned changesets, and average number of days the changesets are open, and average number of days it took for the changesets to be merged.

**Changesets By Organization** shows a doughnut chart that represent number and percentage of changesets submitted by an organization over a time period. Mouse over a color to view details related to an organization.

**Median Time To Merge \(Days\)** shows line graphs that represent the increase or decrease in time it takes for 50 percent of the changesets to be merged.

**Submitters** shows line graphs that represent the increase or decrease in the number of changeset submitters and their affiliated organizations over time.

**Median Time To First Review** shows line graphs that represent the 50th percentile of days it takes for a changeset to get reviewed in a given timeframe.

**Organizations** shows a table that lists organization name, number of submitters from the organization, number changesets submitted by the organization's submitters, number of changesets in different stages, such as new, merged and abandoned, average number of patchsets submitted per total changesets, and average number of days it took to merge the changesets for an organization.

**Submitters** shows a table that lists name of the submitters, total number of changesets submitted by the submitter, number of changesets in different stages, such as new, merged and abandoned, average number of patchsets submitted by the submitter over time, and average number of days it took to merge the changesets submitted by a submitter.

**Repositories** shows a table that lists repository name, total number of changesets submitted to the repository, total number of submitters, number of changesets \(submitted to the repository\) in different stages, such as new, merged and abandoned , average number of patchsets per changesets over time, and average number of days it took to merge the changesets for a repository.

## Backlog

Backlog focuses on open changesets \(data is retrieved at the moment of dashboard creation\), their accumulated time, and associated organizations.

**Filter** lets you filter the dashboard data by author name, organization name, and repository. Select values from the respective drop-down lists, and click **Apply changes** to filter the dashboard as per selection.

**Summary** shows total number of new changesets that are in open state, number of repositories where the new changesets are submitted, and are in open state, and average number of days changesets have been in open state.

**Changeset Backlog Percentage By Organization** shows a doughnut chart that displays number and percentage of changesets created by on organization over time. Mouse over a color to view details.

**Backlog \(New Changesets\)** shows a table that provides a summary of oldest changesets that are in open states, and are waiting to be closed. It lists changeset URLs for the project. For each changeset, the table shows the summary, the submitter name, the date and time the changeset was created, and how long \(in days\) the changeset have been in open state. Click a URL to go to the changeset in the project.

**Backlog** shows line graphs that displays the number of new changesets created over time.

**Backlog By Submitters** shows a table that provides summary of new changesets created by individual submitters. It lists submitter's names, number of changesets and average number of patchsets created by the submitter, and average number of days the changesets have been in open state.

**Backlog By Organizations** shows a table that provides summary of new changesets created by organizations. It lists organizations' names, number of submitters of the organization, number of changesets and average number of patchsets created by the organizations' submitters, and average number of days the changesets have been in open state.

**Backlog By Repositories** shows a table that provides summary of new changesets submitted to repositories. It lists repository names, number of submitters to the repository, number of changesets and average number of patchsets submitted to the repository, and average number of days the changesets have been in open state for a repository.

## Approvals

Approvals shows statistics about changesets that are approved. The dashboard shows reviewers, repository names, numbers of respective data, and so on.

**Filter** lets you filter the dashboard data by repository, author who submitted changesets and author who approved changesets. Select values from the respective drop-down lists, and click **Apply changes** to filter the dashboard as per selection.

**Summary** shows 

* Approvals: Sum of all approvals given on all the changesets
* Changesets Approved: Number of changesets that were given an approval
* Approvers: The number of reviewers that approved the changesets

**Approvals By Organization** shows a doughnut chart that represents the number and percentage of changesets that are approved by the authors of the organization. Mouse over a color in the chart to view details.

**Reviewers Over Time** shows a graph that represents total number of reviewers who reviewed changesets for the project over time.

**Approvals Over Time** shows graphs that represent number of changesets in different states over time. Mouse over a color to view details.

**Activity by Repository** shows a table that lists name of the repository, total number of changesets, patchsets, and approved changesets per repository.

**Approvals Done by Reviewer** shows a table that lists reviewer name, number of changes approved by the reviewer, and number of code review ratings \(-2, -1, 1, 2\) given by the reviewer for the repository over time.

**Approvals by Reviewer Organization** shows a table that provides summary of organizations that approved changesets. It lists name of the organization that approved changesets, number of changesets approved by the organization, and number of code review ratings \(-2, -1, 1, 2\) given by the reviewers of the organization over time.

**Approvals Received** shows a table that provides summary of changeset submitters who received maximum number of approvals. It lists name of the changeset submitter, number of approvals received by the submitter, and number of code review ratings \(-2, -1, 1, 2\) received by the submitter over time.

## Reviews

Reviews shows metrics about reviewed changesets. The dashboard shows reviewers, repository names, numbers of respective data, and so on.

**Filter** lets you filter the dashboard data by reviewer name, organization name, and repository. Select values from the respective drop-down lists, and click **Apply changes** to filter the dashboard as per selection.

**Summary** shows the total number of changesets, total number of individuals who reviewed changesets, total number approved changesets, total number of review comments received for the submitted changesets, and average time in days it took to review the first changeset.

**Repos By Review Activity** shows a cloud of top 10 repositories where maximum number of review activities happened. Click a repository to view the dashboard data specific to the repository.

**Review Types** shows a doughnut chart that represents the total number and percentage of changesets in the project by review status: Comment, Approval, Patchset, and Changeset. Mouse over a color in the chart to see the status, total number, and percentage of changesets by review status.

**Median Time to First Review** shows a graph that displays 50th percentile of days it takes for a changeset to get a review in a given timeframe_._ Mouse over a color in the graph to see the data.

**Changesets Merged Without Approval** shows graph that displays number of changesets that are merged without going through a approval process, over a period of time.

**Repository Changeset Review Summary** shows a table that displays review activity per repository, and lets you sort values by repository name, number of submitters and reviewers per repository, total number of changesets submitted to the repository, number review comments and approvals received for changesets per repository.

**Organization Changeset Review Summary** shows a table that displays review activities per organization, and lets you sort values by organization name, number of submitters and reviewers of an organization, total number of changesets submitted by an organization, number review comments and approvals given by an organization's submitters over time.

**Reviewer Activity** shows a table that displays activities by top reviewers. It list reviewer name, reviewer's organization name, number of  changesets and patchsets reviewed by the reviewer, number of review comments given, number of changesets approved by the reviewer along with the total number of activities done by the reviewer.

