# GitHub

The GitHub dashboards represent a set of metrics that shows pull request information of GitHub repositories of the project. Following are the various dashboards of GitHub:

* [Pull Requests](github.md#pull-requests)
* [PR Backlog](github.md#pr-backlog)
* [PR Efficiency](github.md#pr-efficiency)
* [PR Timing](github.md#pr-timing)

Click ![](../../../../.gitbook/assets/share-icon.png) to share the path for respective dashboards.

## Pull Requests

Pull Requests shows all the information about pull requests for a project.

**Summary** shows the total number of pull requests, submitters, and repositories of the project over time.

**Pull Requests by Status, over time** shows a stacked bar graph that represents the number of open and closed pull requests over time. Mouse over a color in the graph to see the total number of pull requests by status that occurred on a date.

**Submitters by Organization** shows a doughnut chart that represents the total number of submitters per organization. Mouse over a color \(organization\) in the chart to see the organization name, total number of submitters, and the percentage of the project's submitters.

**Submitters Over Time** shows a bar graph that represents the number of pull request submitters per day over time. Mouse over a color in the graph to see the total number of submitters that occurred on a date.

**Pull Requests By Submitters** shows a table that lists submitter name, number of pull requests by the submitter, number of repositories the submitter submitted PRs, and average number of days the submitter's PRs were open before they were closed.

**Pull Request by Organizations Over Time** shows a stacked bar graph that represents the number of pull requests per day by organization over time. Mouse over a color in the graph to see the total number of pull requests that occurred on a date for the organization.

**Pull Requests By Organization** shows a table that lists and lets you sort values by organization name, number of Pull Requests submitted by the organization over time, total number of submitters of the organization, and number of repositories to which the submitters of the organization have submitted PRs .

**Pull Requests By Repositories** shows a table that lists and lets you sort values by repository link, number of pull requests, authors, assignees, and labels per repository. You can select a repository to view details on GitHub.

## PR Backlog

PR Backlog focuses on open pull requests \(data is retrieved at the moment of dashboard creation\), their accumulated time, and associated organization.

**Open Pull Requests Statistics** shows the total number of Open Pull Requests, Accumulated Open Time in Days, and the Average Time Open per Pull Request.

**Backlog \(Open Pull Requests\)** shows a table that lets you sort values by Summary, URL, Open Date, and Days Open. Click **+Info** to open the URL to go to the pull request in the project.

**Backlog** shows a bar graph that represents the number of pull requests by day. Mouse over a color in the graph to see the total number of pull requests on a date.

**Backlog: Pull Requests \(Accumulated Time\)** shows a bar graph that represents the number of issues accumulated by day. Mouse over a color in the graph to see the accumulated number of days, pull requests were waiting to be closed on a date.

**Organizations**

* shows a doughnut chart that represents the total number of pull requests in the project by organizations. Mouse over a color in the chart to see the total number of pull requests by the organization, and their percentage of the project's organization.
* shows a table that lets you sort values by Organization, Pull Requests Open, Submitters, and Repositories.

**Backlog Submitters** shows a table that lets you sort values by Submitter, Pull Requests, Avg. Time Open \(Days\), and Repositories.

## PR Efficiency

PR Efficiency offers a view of efficiency closing issues based on metrics: Review Efficiency Index \(REI\), Time to Merge, and Lead Time.

**Efficiency Closing GitHub Pull Requests** lets you select an organization and project as values for the dashboard data.

**Note:** You can select more than one organization.

**REI** \(Review Efficiency Index\) shows a multi-line graph that represents the REI. REI is defined as the number of closed pull requests divided by the number of open pull requests in a given period of time. This visualization measures efficiency in closing pull requests. REI as a moving average is set to 8 weeks to identify changes in trends. Average is also shown as a reference. REI values greater than 1 mean the community is closing more pull requests than those they are opening. Values smaller than 1 mean the opposite—more pull requests open than those closed during a given time frame. Mouse over this graph or **Lead Time** to show a line that displays the date and time at the top of the legend.

![](../../../../.gitbook/assets/18088229.png)

**Time to Merge** shows the time from pull request creation to the moment in which the pull request is closed. The gauge is set to show green color for less than 7 days, yellow for values from 7 to 30 days and red from 30 to 90 days. This setting means that a week is considered as a good time to merge.

**Lead Time** shows a multi-line graph that represents the average time expressed in days between the initiation and completion of a production process, in this case, a pull request. Mouse over this graph or REI to show a line that displays the date and time at the top of the legend.

**Repositories** shows a table with 50th percentile of Median Time Open \(days\) by repository, giving an insight to the differences between them. You can click repository name to open the repository in GitHub.

**Efficiency Closing GitHub Pull Requests:**

This panel focuses on **closed** GitHub pull requests.

**REI**: Review Efficiency Index, defined as the number of closed pull requests divided by the number of open ones in a given period of time. Measures efficiency closing pull requests.

**Lead time**: the time expressed in days between the initiation and completion of a production process, in this case, a pull request. Shown in average.

## PR Timing

Timing shows information about open and closed pull requests in time. The dashboard shows submitters, repositories and organizations, but focuses on how long pull requests remain open. Statistical information provides closing times and also tables with the latest and the oldest pull requests.

**Summary** shows the total number of Pull Requests, Submitters, Assignees, and 50th percentile of Median Time Open \(Days\) over time.

**Median Open Time \(days\)** shows a bar graph that represents number of days for which the median number or 50th percentile of pull requests are open per day out of the total number of pull requested that were created. Mouse over a color in the graph to see the  number.

**80 Percent Open Time \(days\)** shows a bar graph that represents number of days for which the 80th percentile of pull requests are open per day out of the total number of pull requested that were created. Mouse over a color in the graph to see the  number.

**Status** shows a doughnut chart that represents the total number of pull requests in the project by status: closed or open. Mouse over a color in the chart to see the status, total number of pull requests for the status, and the percentage of the project's pull requests for that status.

**Pull Requests by Organization** shows a doughnut chart that represents the total number of pull requests in the project by organization. Mouse over a color in the chart to see the total number of pull requests for the organization, and their percentage of the project's organization.

**Pull Requests** shows a stacked bar graph that represents the total number of pull requests over time in the project by status: closed or open. Mouse over a color in the graph to see the status, the total number of issues for the status, and the date.

**Submitters:**

* shows a bar graph that represents the total number of submitters over time in the project. Mouse over a color in the graph to see total number of submitters and the date.
* shows a table that lets you sort values by Submitter, Pull Requests, Repositories, and Avg. Open Days.

**Organizations** shows a table that lets you sort values by Organization, Pull Requests, Submitters, Assignees, and Avg. Open Days.

**Repositories** shows a table that lets you sort values by Repository, Pull Requests, Submitters, Assignees, and Avg. Open Days.

**Latest Pull Requests** shows a table that lets you sort values by Title, Repository, Submitter, URL, Id, and Created on. The default sort is by most recently created issues.

**The Oldest Pull Requests** shows a table that lets you sort values by Title, Repository, Submitter, URL, Id, and Open Days. The default sort is by the greatest number of open days

