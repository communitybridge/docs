# GitHub PR

{% hint style="info" %}
By default, Bot commit is filtered. To add/manage filters, see [Add and Manage Data Filters](../../../filter-data/add-and-manage-data-filters.md).
{% endhint %}

 The GitHub PR dashboards represent a set of metrics that shows pull request information of GitHub repositories of the project. Following are the various dashboards of GitHub PR:

* [Overview](github-pr.md#overview)
* [Efficiency](github-pr.md#efficiency)
* [Timing](github-pr.md#timing)
* [Backlog](github-pr.md#backlog)
* [Reviews](github-pr.md#reviews)

By default, **Bot** commits are filtered. To apply more filters, see [add and manage data filters](../../../filter-data/add-and-manage-data-filters.md).

Click ![](../../../../.gitbook/assets/get-short-url.png) to copy the path of respective dashboards.

## Overview

Overview shows all the information about pull requests for a project.

**Filter** lets you filter the dashboard data by author name, organization name, repository name, and repository URL. Select values from the respective drop-down lists, and click **Apply changes** to filter the dashboard as per selection.

**Summary** shows the total number of pull requests, submitters, and repositories of the project over time.

**Most Used PR Labels** shows a cluster of top 10 Pull request labels. Click a label to filter the project dashboard to view label related details. Click the cross mark next to a label in the **Add Filter** navigation bar to remove the filter.

**Submitters Over Time** shows a bar graph that represents the number of pull request submitters per day over time. Mouse over a color in the graph to see the total number of submitters that occurred on a date.

**Pull Requests By Organization** shows a doughnut chart that represents the total number of pull requests per organization over a time range. Mouse over a color \(organization\) in the chart to see the organization name, total number and percentage of pull requests.

**PRs Created Over Time** shows a periodic line graph that displays the number of Pull Requests created over time. Hover mouse over the graph to view the date and number of PRs created on the date.

**Pull Requests By Submitters** shows a table that lists submitter name, number of pull requests by the submitter, number of repositories the submitter submitted PRs to, number of merged, rejected and open PRs by the submitter, and average number of days taken to merge the submitter's PRs.

**Pull Request by Organization** shows a table that lists and lets you sort values by organization name, number of Pull Requests submitted by the organization over time, total number of submitters of the organization, and number of repositories to which the submitters of the organization have submitted PRs .

**Pull Requests By Repositories** shows a table that lists and lets you sort values by repository link, number of pull requests per repository, number of PR submitters for the repository, and average time taken in days to merge the PRs. You can select a repository to view details on GitHub.

## Efficiency

Efficiency offers an overall view of understanding and optimizing project efficiency in closing GitHub Pull Requests.

**Filter** lets you filter the project data by organization name, author name, repository name, and repository URL. Select values from the respective drop-down lists, and click **Apply changes** to filter the dashboard as per selection.

**Summary** shows a cluster of

* 50th percentile of Time To Merge \(Days\): The number of days it took to merge 50 percent of the pull requests.
* 95th percentile of Time To Merge \(Days\): The number of days it took to merge 95 percent of the pull requests.
* Merged PRs: Total number of pull requests merged.
* Organizations: Total number of organizations whose submitters authored the merged pull requests.
* Submitters: Total number of submitters whose pull requests were merged.
* Repositories: Total number of repositories the merged pull requests belonged to.

**50th percentile of Time To Close By Repo** shows a cluster of top 10 repositories  names for which it took most time to merge 50% of the pull requests.

**Time to Merge** shows a graph that displays number of Pull Requests that took certain amount of time to get merged. These time slots are divided into four categories, such as less than 1 day, 1 to 7 days, 7 to 30 days, and more than 30 days. Hover mouse over the graph to view number of of PRs along with the time taken to get merged.

* Less than 1 day: The number of pull requests merged in less than one day.
* 1 to 7 days: The number of pull requests merged in more than one day but less than seven days.
* 7 to 30 days: The number of pull requests merged in more than seven days but less than thirty days.
* More than 30 days: The number of pull requests merged in more than thirty days.

**Repositories** shows a table that lists repositories, total number of PRs merged along with the time it took for 50% and 95% of the PRs to get merged per repository. Click a repository to navigate to GitHub to view details. 

## Timing

Timing shows information about open and closed pull requests in time. The dashboard focuses on how long pull requests remain open. Statistical information provides closing times and also tables with the latest and the oldest pull requests.

**Filter** lets you filter the dashboard data by author name, organization name, repository name, and repository URL. Select values from the respective drop-down lists, and click **Apply changes** to filter the dashboard as per selection.

**Summary** shows the total number of Pull Requests, Submitters, Assignees, Average number of days the PRs are in open state, and average number of days taken to merge Pull Requests.

**Pull Requests by Organization** shows a doughnut chart that represents the total number and percentage of pull requests submitted by organizations. Mouse over a color in the chart to see the total number and percentage of pull requests submitted by the organization.

**Median Time to Merge \(Days\)** shows a line graph that represents number of days it took for 50% of open pull requests \(out of all PRs created on a date\) to get merged . Mouse over a color in the graph to see the number.

**Submitters** shows line graphs that represent the number of submitters and organizations who raised pull request over time. Mouse over a color in the graph to view the date and number of organizations and submitters that created PRs.

**Median Time To First Review** shows a line graph that displays the number days it takes for 50% of the pull request to get their first review over time.

**Median Time To First Approval** shows a line graph that displays the number days it takes for 50% of the pull request to get their first approval over time.

**Submitters** shows a table that lists name of submitters, number of pull requests raised by the submitter, number of repositories the submitter worked upon, total number pull requests raised by the submitter by status, such as merged, rejected and open states, and average time in days it takes to merge the pull request submitted by the submitter.

**Organizations** shows a table that lists organization name, total number of pull requests submitted by the organization along with number of PRs by status, such as merged, rejected and open state, and average time taken in days to merge the PRs per organization.

**Repositories** shows a table that lists and let you sort values by repositories, number of pull requests along with number of PRs by status, such as merged, rejected and open state, submitters, and average time taken to merge the PRs per repository.

## Backlog

Backlog focuses on open pull requests \(data is retrieved at the moment of dashboard creation\), their accumulated time, associated organizations and submitters.

**Filter** lets you filter the dashboard data by author name, organization name, repository name and URL. Select values from the respective drop-down lists, and click **Apply changes** to filter the dashboard as per selection.

**Summary** shows total number of pull requests in open state, total number of repositories having pull requests in open state, and average number of days pull requests have been in open state.

**Pull Request Backlog Percentage By Organizations** shows a pie chart that displays the number and percentage of pull requests in open state by organization. Mouse over a color in the chart to view details.

**Backlog \(Open Pull Requests\)** shows a table that provides a summary of oldest PRs that are in open states, and are waiting to be closed. It lists PR URLs for the project. For each PR, the table shows the summary, date and time the PR was created, and how long \(in days\) the PR have been in open state. Click a URL to go to the changeset in the project.

shows a table that lets you sort values by Summary, URL, Open Date, and average time in days the pull requests are in open stat. Click the URL to go to the pull request in the project.

**Backlog** shows a line graph that represents the number of pull requests that are open on a particular day. Mouse over a color in the graph to see the total number of pull requests on a date.

**Backlog By Submitters** shows a table that lists submitter name, number of pull requests raised by the submitter, number of repositories the submitter worked upon, and average time in days the pull requests are in open state for a submitter.

**Backlog By Organizations** shows a table that lists organization name, number of pull requests raised by the organization, number of submitters from the organization, number of repositories the submitters of the organization worked upon, and average number of days the pull requests raised by the organization are in open state.

**Backlog By Repositories** shows a table that lists repository URL, number of pull requests raised, number of submitters, and average number of days the pull requests are in open state per repository.

## Reviews

Reviews provides an overall analysis of reviewed pull requests, approved ones, dismissals, average time to first review, approve, and so on along with the associated organizations and reviewers.

**Filter** lets you filter the dashboard data by reviewer name, organization name, repository name and URL. Select values from the respective drop-down lists, and click **Apply changes** to filter the dashboard as per selection.

**Summary** shows the following details:

* Submitted: Total number of PRs created \(submitted\) and reviewed across all monitored repositories.
* Reviewers: Total number of unique PR reviewers across all monitored repositories.
* Approvals: Total number of approvals received on all submitted PRs.
* Changes Requested: Total number of 'Request Changes' received on all submitted PRs.
* Review Comments: Total number of Comments received on all submitted PRs.
* Dismissed: Total number of PR reviews being dismissed.
* Avg. Time to First Review: The average time it took to get the first review on the PR across all submitted PRS.

**Repos By Review Activity** shows a cluster of top 10 repositories on which most review activity happened. Click a repo to view dashboard data specific to the repository.

**PR Review States** shows a doughnut chart that displays the number and percentage of pull request reviews by state, such as commented, approved, changes requested, and dismissed. Mouse over a color to view details.

**Median Time To First Review** shows a line graph that displays the 50th percentile of days it takes for a pull request to get a review in a given timeframe. Mouse over the graph to view details.

**Median Time To First Approval** shows a line graph that displays the 50th percentile of days it takes for a pull request to get an approval in a given timeframe. Mouse over the graph to view details.

**PRs Merged Without Approval** shows a line graph that shows the number of pull requests merged without approval on a particular day. Mouse over the graph to view details.

**Repository PR Review Summary** shows a table that lists repository URL, number of submitters, reviewers, review comments received per repository, and number of approved, changes requested, and dismissed PRs per repository over time.

**Organization PR Review Summary** shows a table that lists organization name, total number of pull requests raised by the organization, number of reviewers, review comments received for PRs raised by the organization, and number of approved, changes requested, and dismissed PRs per organization over time.

**Reviewer Activity** shows a table that lists reviewer names, total number of activity by the reviewer, number of approved, changes requested, review comments and dismissed PRs per reviewer over time. Total Activity is the sum of all activities done by the reviewer, such as how many PRs they approved, provided comments for, dismissed, and requested changes.

**Latest PRs Review Activity** shows a table that lists GitHub pull request link, date on which the PR is created, and if the PR is approved or dismissed, or any number of review comments and changes requested for the PR. Numbers as one and zero are used to indicate true or false for approved and dismissed PRs.

