# Gerrit

{% hint style="info" %}
Where: The Gerrit dashboards are available from the **Code** drop-down list.
{% endhint %}

## Gerrit &gt; **Overview** <a id="Gerrit-Gerrit&gt;Overview"></a>

SUMMARY: Overview shows visualizations that provide information about changeset statuses, submitters, and organizations. Changeset information per organization and repository is also shown.

**Summary** shows the total number of changesets, total number of individuals who submitted changesets, total number of repositories, and average time in days to first review a changeset after it is submitted.

**Changesets Statistics \(Open Time in Days\)** shows the total number of changesets that were open in days by percentile: 50th, 75th, 95th, and the percentile rank for time open. The percentile rank of a score is the percentage of scores in its frequency distribution that are equal to or lower than it.

**Patchset Statistics per Changeset** shows the total number of patches by percentile: 50th, 75th, 95th, and the percentile rank of patchsets per review. The percentile rank of a score is the percentage of scores in its frequency distribution that are equal to or lower than it.

**Changesets by Status** **Per Day** shows a stacked bar graph that represents the number of changesets that were started per day for the project by status: MERGED, ABANDONED, NEW, DRAFT. Mouse over a color in the graph to see the status, total number of reviews, and the date the changesets was started.

**Changeset Submitters** **Per Day** shows a bar graph that represents submitters and their corresponding number of changesets per day over time. Mouse over a color in the graph to see the total number of changeset submitters for a date.

**Authors Percentage by Organization** shows a doughnut chart that represents the total number of changesets per organization for the project. Mouse over a color in the chart to see the total number of changesets per organization, and the percentage of changesets for that organization out of the total number.

**Organizations:**

* shows a stacked bar graph that represents the number of changesets by an organization per day over time. Mouse over a color in the graph to see the total number of changesets for the organization and the date.

**Status** shows a doughnut chart that represents the total number of changesets in the project by status: MERGED, ABANDONED, NEW, DRAFT. Mouse over a color in the chart to see the status, total number of changesets for the status, and the percentage of the project's changesets for that status.

**Repositories** shows a table that lets you sort values by Repository, \# Changesets, and \# Submitters.

**Submitters** shows a table that lets you sort values by Submitter, \# Changesets, \# Projects, and Avg Patchsets.

**Patchsets per Changeset** shows a stacked bar graph that represents the number of patchsets by percentage of the total number: 50th, 75th, and 95th percentile. Mouse over a color in the graph to see the total number of changesets per percentile.

## Gerrit &gt; **Backlog** <a id="Gerrit-Gerrit&gt;Backlog"></a>

SUMMARY: Backlog focuses on open changesets \(data is retrieved at the moment of dashboard creation\), their accumulated time, and associated organizations.

**NEW Changesets Statistics** shows the total \# Changesets \(Status: NEW\), Accumulated Open Time in Days \(Status: NEW\), and Average Time Open in Days per Changeset \(Status: NEW\).

**Backlog** shows a table that lets you sort values by URL, Summary, Submitter, Project, Open Date, and Days Open. You can click a URL to go to the changeset in the project.

**Backlog: Accumulated Days waiting to be Closed** shows a bar graph that represents the number of changesets by accumulated open days per day over time. Mouse over a color in the graph to see the accumulated number of days issues were waiting to be closed on a date.

**Backlog: New Changesets waiting to be Closed** shows a bar graph that represents the number of changesets that are new per day over time. Mouse over a color in the graph to see the accumulated number of days new changesets were waiting to be closed on a date.

**Organizations:**

* shows a doughnut chart that represents the total number of changesets in the project by organization. Mouse over a color in the chart to see the total number of changesets for the organization, and their percentage of the project's organization.
* shows a table that lets you sort values by Organization and \# Changesets.

**Changeset Submitters** shows a table that lets you sort values by Submitter, \# Changesets, \# Projects, and Avg Patchsets. 

**Projects** shows a table that lets you sort values by Projects and \# Changesets.

## Gerrit &gt; **Efficiency** <a id="Gerrit-Gerrit&gt;Efficiency"></a>

SUMMARY: Efficiency offers a view of efficiency closing reviews based on metrics: Review Efficiency Index \(REI\), Time to Merge, and Lead Time.

**Efficiency Closing Gerrit Reviews** lets you select an Organization and Repository as values for the dashboard data.

**Review Efficiency Index** shows a multi-line graph that represents the REI. REI is the number of closed reviews divided by the number of open ones in a given period of time. This visualization measures efficiency closing reviews. REI Moving Avg. \(8 weeks\) identifies changes in trends. Average is also shown as a reference. REI values greater than 1 mean the community is closing more reviews than those they are opening. Values smaller than 1 mean the opposite—more reviews open than those closed during a given time frame. Mouse over this graph or **Lead Time** to show a line that displays the date and time at the top of the legend.

![](../../../../.gitbook/assets/18088226.png)

**Lead Time** shows a multi-line graph that represents the average Time to Merge expressed in days together to its trend. This helps to identify peaks and visualize the time spent in closing reviews.  Mouse over this graph or **REI** to show a line that displays the date and time at the top of the legend.

**Time to Merge** shows a gauge that represents the time from issue creation to the moment in which it is merged. The gauge is set to show green color for less than 7 days, yellow for values from 7 to 30 days, and red from 30 to 90 days. This color scheme means that a week is considered as a good time to merge. The color scheme is just a visual reference and you can always rely on the number, ignoring this color scheme.

**Repositories** shows a table with 50th percentile of Median Time Open by repository, giving an insight on the efficiency of closing reviews per repository.

## Gerrit &gt; **Timing** <a id="Gerrit-Gerrit&gt;Timing"></a>

SUMMARY: Timing shows information about open and closed changesets in time. The dashboard shows submitters, repositories and organizations, but focuses on how long changesets remain open. Statistical information provides closing times and also tables with the latest and the oldest changesets.

**Gerrit Summary** shows the total \# Changesets, \# Changeset Submitters, and \# Repositories.

**Changesets Open in Median** shows a bar graph that represents the median number of changesets that were open per day over time. Mouse over a color in the graph to see the median number of days changesets were open on a date.

**Changesets Open \(best 80 percentile\)** shows a bar graph that represents the 80th percentile number of changesets that were open per day over time. Mouse over a color in the graph to see the 80th percentile number of days changesets were open on a date.

**Status** shows a doughnut chart that represents the total number of changesets in the project by status: MERGED, ABANDONED, NEW, DRAFT. Mouse over a color in the chart to see the status, total number of changesets for the status, and the percentage of the project's changesets for that status.

**Organizations** shows a doughnut chart that represents the total number of changesets in the project by organization. Mouse over a color in the chart to see the total number of changesets for the organization, and their percentage of the project's organization.

**Submitters** shows a table that lets you sort values by submitters and their corresponding number of changesets, the average number of patchsets, and average number of days that their changesets were open.

**Repositories** shows a table that lets you sort values by Repository, \# Changesets, and \# Submitters.

**Changesets** shows a table that lets you sort values by changeset URLs in the project. For each changeset, the table shows the changeset summary, the number of days that the changeset was open, the submitter name, the changeset status, and the date the changeset was opened. You can click a URL to go to the changeset in the project.

