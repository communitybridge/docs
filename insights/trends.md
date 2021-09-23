# Trends

Trends dashboards provide analytics of project performance, such as how many total contributors are contributing to your project, number of commits, total number of code backlogs, issues, and many more for a project. These performance-related data are grouped into different blocks of [_metrics_](trends.md#metrics-details).

* [Global Trends](trends.md#global-trends)
* [Project Trends](trends.md#project-trends)
* [Time-Based Data Aggregation Methods](trends.md#time-based-data-aggregation-methods)
* [Downloading a Metric Card](trends.md#downloading-a-metric-card)

You can [filter data by time range](filter-data/filter-data-by-time-range.md). For details about filtering data, see [Filter Data](filter-data/).

{% hint style="info" %}
**Note:** If you filter data by time range on Trends dashboard for a _sub project_ of a project group, then the selected Trends time range will also reflect on the _other sub projects_ of the project group.
{% endhint %}

## Global Trends

Global Trends dashboards provide high level analytics of project performance for all the projects onboarded to Insights. ****The performance-related data are grouped into different blocks of [_metrics_](trends.md#metrics-details).

![Global Trends](../.gitbook/assets/global-trends-card.png)

Following are the twelve most important _Key Performance Indicators \(KPIs\)_ of all projects, displayed at the top:  


| Metrics | Definition |
| :--- | :--- |
| **Total lines of Code** | Combined count of lines of code across each repository for all the projects. |
| **Commits** | Total number of [unique commits](glossary.md#unique-commits). |
| **Average lines of code added weekly** | Average number of lines of code added weekly across unique commits for all the projects during the selected time range. |
| **Average Lines of code deleted weekly** | Average number of lines of code deleted weekly across unique commits for all the projects during the selected time range. |
| **Code Contributors** | Total number of [unique developers](glossary.md#unique-contributors) across commits, PRs, changesets and issues aggregated for all projects. |
| **Contributing Companies** | Total number of affiliated companies \(only unique numbers\) contributing towards commits, PRs, changesets and issues aggregated for all projects. |
| **Repositories** | Total number of unique repositories actively monitored across all projects. |
| **Pull Requests** | Total number of PRs / Changesets \( includes both open and merged/closed/rejected\) across all projects of Insights. |
| **Logged Issues** | Total number of issues that are submitted and closed \(includes rejected\) across all projects. |
| **Project Builds** | Total number of project builds across all projects. |
| **Container downloads** | Total number of docker image downloads aggregated for each docker image across all projects. |
| **Email messages sent** | Total number of email messages monitored across all projects. |

## Project Trends

Project Trends dashboards provide analytics of project performance data, such as how many contributors are contributing to your project, total number of code backlogs, issues, and many more for the project. These performance-related data are grouped into different blocks of [_metrics_](trends.md#metrics-details).

![Project Trends](../.gitbook/assets/project-dashboard.png)

Based on the project's configured data sources, following key project performance indicators are displayed at the top:

* Total number of unique commits
* Number of repositories being monitored
* Total number of lines of code added and modified
* Total number of Pull Requests / Changesets submitted
* Total number of builds being monitored
* Total number of emails sent 
* Total number of relevant mentions on social media channels
* Total number of issues submitted
* Total number of messages sent in different chat platforms of the project
* Total number of project relevant document pages created on confluence, and
* Total number of container images downloaded

Click the icons for each metric to view details about the metrics. **No Data** is displayed for a metric if the relevant data source is not configured for the project.

Navigate to another project of the project group by selecting a project from **View Sub Projects** drop-down list under the project group name on the top right corner of the overview card.

#### **Metrics Details:**

**Contributor Strength**: Shows graphs that display total number of contributors on a periodic basis during the selected time range, and represents a periodic growth in the aggregated count of [unique contributors](glossary.md#unique-contributors) analyzed during the selected time range. 

The grey colored rectangular card shows the following data in each slide: 

* The increment number in percentage
* Monthly average contributor strength, and
* The exact time period during which the numbers increased the most.

**Contributor Growth And Retention:** Shows total count of contributors, active contributors, inactive contributors, and percentage of churn rate on a periodic basis during the selected time range. It also shows graphs representing the increment/decrement in active and inactive contributor numbers.

{% hint style="info" %}
1. **Active contributors** are those who have performed any code related activity, such as creating a PR or submitting a changeset or an issue, during the last 6 months. 
2. If a contributor has not done any contribution to the project in the last 6 months, they are considered _**inactive**_.
{% endhint %}

 Churn rate is calculated as:_`Total Inactive Contributors recorded at the end of the time period/  (Total Active Contributors recorded at the start + Total New Contributors who joined during the selected time period)`_

The grey colored rectangular card shows the following data in each slide: 

* Monthly average count of active contributors during the selected time range
* Time period during which number of active contributors increased the most
* Monthly average count of inactive contributors
* Time period that records the most inactive contributors, and
* Decrement percentage of active contributors during the selected time range

**Commits Growth:** Shows graphs that display the total number of unique commits on a periodic basis during the selected time range, growth percentage of commits, and monthly average number of code commits by active contributors for the selected time range.

**New Contributor Growth:** Shows periodic bar graphs that display the total number of new contributors joining the projects during the selected time range, and represents a periodic growth/decline in the count of new contributors during the selected time range.   
**Note:** New contributor is considered as someone who performed their first code activity during the selected time period.

The grey colored rectangular card shows the following data in each slide:

* Increment/decrement percentage rate of code contributors during the time range
* Average monthly count of new contributors, and
* Time periods that record highest and lowest number of new contributors joining the project during the selected time range.

**Commits By New Contributors:** Shows periodic graphs that display the count of ****total number of commits by new contributors during the selected time range. Hover over the points for a quarter to see the number of commits by new contributors for the quarter.   
**Note:** New contributor is considered as someone who performed their first code activity during the selected time period.

The grey colored rectangular card shows the following data in each slide:

* Increment/decrement percentage rate of code commits by new contributors during the time range, and
* Monthly average number of commits by new contributors

**LOC Added And Deleted:** Shows periodic graphs that display the number of the total lines of code added and deleted for each unique commit during the selected time range.

The grey colored rectangular card shows the following data in each slide:

* Increment/decrement percentage rate of lines of code changed per commit during the time range, and
* Churn rate of lines of code per commit, weekly and monthly average number of lines of code added to all repositories during the time range

**Contributor Role Distribution:** Shows graphs, in pie chart and line graph formats, that display the count of the total number of pull request creators, reviewers and approvers aggregated across unique PR and changesets over the selected time range.

The grey colored rectangular card shows the following data in each slide:

* Monthly average number of submitters and reviewers for pull requests and changesets during the time period
* Monthly average ratio between reviewers and submitters of pull requests and changesets, and
* percentage of pull requests submitted and reviewed by core maintainers during the selected time range

**Code Pipeline:** Shows total count of unique commits \(pull requests or changesets\) submitted, reviewed, approved and merged across all projects during the selected time range.

The grey colored rectangular card shows the following data in each slide:

* Percentage of approved changes out of the total number of changes submitted
* Percentage of changes merged out of the total number of reviewed changes, percentage of changes merged without approval, and
* Percentage of risky changes found during review that are not merged

**PR Cycle Time:** Shows the sum of the average time taken in each step of the pull request or changeset cycle.  

* Work in Progress: time taken for first review
* Review: time in reviewing the changes
* Merge: time taken to merge changes to the release branch

The grey colored rectangular card shows the following data in each slide:

* Median time taken to first review a pull request, and 
* Median time taken to first approve a pull request during the selected time range

**PR Merge Efficiency:** Shows graph that displays total time taken to merge a pull request. The time periods are divided into four slots: less than 1 day, between 1-7 days, between 7-30 days and greater than 30 days.

The grey colored rectangular card shows the following data in each slide: 

* Number of the pull requests merged during each time slot
* The average merge efficiency time and percentage of pull requests that are merged within a week

**Issues Backlog:** Shows a graph that represents the total number of issues in the backlog that are in Open and Resolved \(includes both closed and done\) states during the selected time range.   
**Note:** GitHub issues in open state are also considered as backlog.

The grey colored rectangular card shows the following data in each slide:

* Monthly average number of backlog issues
* Percentage of increment/decrement in new issues submitted
* Average number of resolved issues, and 
* Average number of activities recorded in the issue management system during the selected time range

**Issues Resolution Efficiency:** Shows graph that represents the median time taken to resolve \(close or reject\) an open issue. The time periods are divided into four slots: less than 1 day, between 1-7 days, between 7-30 days and greater than 30 days.

The grey colored rectangular card shows the following data in each slide:

* Showing the number of issues resolved during each time slot, and
* Mean time taken to first react to an Issue during the selected time range

**Builds Stats**: Shows a pie chart that displays the number of builds executed over time by their statuses: Successful Builds, Failed Builds, Unstable Builds, and Aborted Builds.

The grey colored rectangular card shows the following data in each slide:

* The increment/decrement percentage in the success rate of all builds during the selected time range
* Percentage rate in the increment/decrement of builds per day
* Average number of builds executed per day, and 
* Percentage rate in the increment/decrement of average build duration time taken during the selected time range

**Active Communication Channel:** Shows different communication platforms the community is using the most. It displays the number of messages shared on a communication platform on a periodic basis.

The grey colored rectangular card shows the following data in each slide:

* Average number of chats and emails sent per month
* Average number of community members who participated in the conversations per month, and 
* The communication platform that is used the most by community members during the selected time range

**Organizational Engagement:** Shows colored circular dots that represent the percentage of commits made by affiliated contributors, unaffiliated contributors and independent contributors during the selected time range.

The grey colored rectangular card shows the following data in each slide:

* Total number of organizations who participated in code commits
* Number of organizations that contributed to 50% of the total commits
* Average number of commits contributed by individual contributors, and
* Average number of commits contributed by unaffiliated contributors during the selected time range.

## Time-Based Data Aggregation Methods

For different time periods, different strategies are used to collect, aggregate, and visualize _Trends_ data. Depending upon the selected time period, the data are displayed with different numbers of break points, also called _buckets_. Following are the different time periods, of Trends dashboard, and the strategies used to aggregate data for each of the time period:

#### 3M:

This shows aggregated data for the last 3 months from the current date. The data are aggregated based on a specific interval in days of a month, and are displayed with 12 breakpoints \(also called buckets\).

#### 6M:

This shows aggregated data for last the 6 months from the current date. The data are aggregated based on a specific interval in days of a month, like it is for [3 months](trends.md#3m), and are displayed with 12 breakpoints.

#### 1Y:

This shows aggregated data for last one year from the current date. The data are aggregated monthly, and are displayed with 12 breakpoints.

#### 2Y:

This shows aggregated data for the last two years from the current date. The data are aggregated quarterly, and are displayed with 8 breakpoints.

#### 3Y:

This shows aggregated data for the last three years from the current date. The data are aggregated every 4th month, and are displayed with 9 breakpoints.

#### 5Y:

This shows aggregated data for the last five years from the current date. The data are aggregated half-yearly \(every 6th month\), and are displayed with 10 breakpoints.

#### 10Y:

This shows aggregated data for last the ten years from the current date. The data are aggregated on a yearly basis, and are displayed with 10 breakpoints.

#### SINCE 2000:

This shows aggregated data from the year 2000 till the current year and date. The data are aggregated yearly, but are displayed with numbers of breakpoints based on the current year. For example, if the current year is 2021, the break points will start from 2000 to 2021, showing 20 breakpoints.

## Downloading a Metric Card

You can download a metric card in image \(.png\) format by clicking the download button from the top right corner of the card. It is applicable to all the metrics cards displayed  in Insights. Following is an example:

![Downloading a Metrics Card](../.gitbook/assets/downloading-metrics.png)

