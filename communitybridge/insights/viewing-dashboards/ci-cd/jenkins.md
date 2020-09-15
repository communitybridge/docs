# Jenkins

The Jenkins dashboards under CI/CD drop-down list represents a set of metrics that show overview analysis of Jenkins data. Following are the various dashboards of Jenkins:

* [Overview](jenkins.md#overview)
* [Jobs](jenkins.md#jobs)
* [Job Categories](jenkins.md#job-categories)
* [Nodes](jenkins.md#nodes)
* [Build data](jenkins.md#build-data)

Click ![](../../../../.gitbook/assets/copy-short-url.png) to share the path of respective dashboards.

## Overview

Overview shows an overview of Jenkins build and job data over time.

**Filter** lets you filter the dashboard data by job name. Select values from the drop-down list, and click **Apply changes** to filter the dashboard as per selection.

**Summary** shows the number of builds, jobs, nodes, and average time of build duration in minute for a project.

**Builds Over Time** shows a bar graph that represents the total number of builds per day over time.

**Build Results Percentage** shows a stacked bar graph that represents the percentage of build results—Success and Failures— per day over time. The build results are color coded. Mouse over a color to see the percentage of build result for a day.

**Build Results By Categories** shows a doughnut chart that represents the total number of builds in the project by status: SUCCESS, FAILURE, UNSTABLE, ABORTED. Mouse over a color in the chart to see the status, total number of builds for the status, and the percentage of the project's builds for that status.

**Active Nodes Over Time** shows a bar graph that represents the  number of active nodes per day over time. Mouse over a color to see the number of active nodes for a day.

**Nodes** shows a table that lists name of node, number of builds, median or 50th percentile of duration in minute,  and total duration in minute per node.

**Builds** shows a table that lets you sort values by build date and time, job name with build number \(job\_build\), URLs for build and job, type of result, node on which the job is built, and time taken in minutes to execute the build.

## Jobs

Jobs shows data about Jenkins jobs such as duration, successes, and failures over time.

**Filter** lets you filter the dashboard data by job name. Select values from the drop-down list, and click **Apply changes** to filter the dashboard as per selection.

**Summary** shows the number of build results—Success, Failure, Unstable, Aborted.

**Results** shows a doughnut chart that represents the total number of jobs in the project by status: SUCCESS, FAILURE, UNSTABLE, ABORTED. Mouse over a color in the chart to see the status, total number of jobs for the status, and the percentage of the project's jobs for that status.

**Jobs Per Branch** shows a doughnut chart that represents the total number of jobs per branch. Mouse over a color to see the branch name, total number of jobs per branch, and percentage of jobs out of total jobs in project.

**Jobs** shows a bar graph that represents the number of jobs per day over time. Mouse over a color to see the total number of jobs per day.

**Duration Trend** shows the time in minutes for the total number of jobs per day over time and a trend line to show an increase, decrease, or stability in the job time.

**Avg. Build Duration Over Time Per Job** shows a stacked bar graph that represents the average time in minutes taken for the execution of a job per day. Mouse over a color to see the job names per day and average time taken for a job .

**Jobs** shows a table that lets you sort values by job name, number of builds per job, 50th percentile of build duration in minutes, total build duration in minutes, number of success and failure results.

## Job Categories

Job Categories shows data about Jenkins jobs that are grouped into certain categories in a project.

**Filter** lets you filter the dashboard data by job name. Select values from the drop-down list, and click **Apply changes** to filter the dashboard as per selection.

**Summary** shows number of builds, jobs, nodes, and job categories for a project.

**Jobs Evolution** shows number of builds executed per day.

**Categories** shows a table that lists name of categories the jobs are grouped to, total number of jobs and builds per category, and number of build results per success and failures.

**Results Across Top Categories** shows number of builds per category by status: SUCCESS, FAILURE, UNSTABLE, ABORTED. Top categories are listed based on the total number of builds per category.

## Nodes

Nodes shows an overview of Jenkins build and job data over time. It shows a table that lists and  lets you sort values by node name, number of builds per node, 50th percentile of build duration in minutes, total build duration in minutes, success and failure counts of builds per node.

## Build Data

Build Data shows an overview of Jenkins build data over time

**Builds** shows a table that lets you sort values by build name, build result such as Success, Failure, and so on per build, node where the build happened, time taken in minutes for the build to be executed, and date and time when the build happened.

