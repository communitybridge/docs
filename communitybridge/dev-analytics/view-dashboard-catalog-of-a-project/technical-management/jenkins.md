# Jenkins

The Jenkins dashboards are available from the **Technical Management** drop-down list, and represents a set of metrics that show overview analysis of Jenkins data. Following are the various dashboards of Jenkins:

* [Overview](jenkins.md#overview)
* [Jobs](jenkins.md#jobs)
* Job Categories
* [Nodes](jenkins.md#nodes)
* Build data

Click ![](../../../../.gitbook/assets/share-icon.png) to share the path of respective dashboards.

## Overview

Overview shows an overview of Jenkins build and job data over time.

**Summary** shows the number of builds, jobs, nodes, and average time of build duration in minute for a project.

**Builds Over Time** shows a bar graph that represents the total number of builds per day over time.

**Build Results Percentage** shows a stacked bar graph that represents the percentage of build results—Success and Failures— per day over time. The build results are color coded. Mouse over a color to see the percentage of build result for a day.

**Build Results By Categories** shows a doughnut chart that represents the total number of builds in the project by status: SUCCESS, FAILURE, UNSTABLE, ABORTED. Mouse over a color in the chart to see the status, total number of builds for the status, and the percentage of the project's builds for that status.

**Active Nodes Over Time** shows a bar graph that represents the  number of active nodes per day over time. Mouse over a color to see the number of active nodes for a day.

**Nodes** shows a table that lists name of node, number of builds, median or 50th percentile of duration in minute,  and total duration in minute per node.

**Builds** shows a table that lets you sort values by build date and time, job name with build number \(job\_build\), URLs for build and job, type of result, node on which the job is built, and time taken in minutes to execute the build.

## Jobs

Jobs shows data about Jenkins jobs such as duration, successes, and failures over time.

**Summary** shows the number of success count, failure count, aborted count, and unstable count of builds.

**Results** shows a doughnut chart that represents the total number of jobs in the project by status: SUCCESS, FAILURE, UNSTABLE, ABORTED. Mouse over a color in the chart to see the status, total number of jobs for the status, and the percentage of the project's jobs for that status.

**Jobs Per Branch** shows a doughnut chart that represents the total number of jobs per branch. Mouse over a color to see the branch name, total number of jobs per branch, and percentage of jobs out of total jobs in project.

**Jobs** shows a bar graph that represents the number of jobs per day over time. Mouse over a color to see the total number of jobs per day.

**Duration Trend** shows the time in minutes for the total number of jobs per day over time and a trend line to show an increase, decrease, or stability in the job time.

**Avg. Build Duration Over Time Per Job** shows a stacked bar graph that represents the average time in minutes taken for the execution of a job per day. Mouse over a color to see the job names per day and average time taken for a job .

**Jobs** shows a table that lets you sort values by job name, number of builds per job, 50th percentile of build duration in minutes, total build duration in minutes, number of success and failure results.

## Job Categories

Job Categories shows data about Jenkins jobs that are grouped into certain categories in a project.

**Summary** shows number of builds, jobs, nodes, and job categories for a project.

**Jobs Evolution** shows number of builds executed per day.

**Categories** shows a table that lists name of categories the jobs are grouped to, total number of jobs and builds per category, and number of build results per success and failures.

**Results Across Top Categories** shows number of builds per category by status: SUCCESS, FAILURE, UNSTABLE, ABORTED. Top categories are listed based on the total number of builds per category.

## Nodes

Nodes shows an overview of Jenkins build and job data over time.

**Summary** shows the number of builds, jobs, nodes, and average build duration in minutes.

**Results** shows a doughnut chart that represents the total number of builds in the project by status: SUCCESS, FAILURE, UNSTABLE, ABORTED. Mouse over a color in the chart to see the status, total number of builds for the status, and the percentage of the project's builds for that status.

**Jobs** shows a bar graph that represents the total number of job per day over a timeline.

**Duration Trend** shows the time in minutes for the total number of jobs per day over time and a trend line to show an increase, decrease, or stability in the job time.

**Success/Failures in percentage** shows a bar graph with each value as a percentage of the total count of jobs per day over time. Mouse over Success or Failures to show the corresponding data in the graph.

**Nodes** show a table of nodes, which are machines that are part of your Jenkins environment. For each node, the table shows the node name, number of builds on the node, the 50th percentile of builds duration in minutes, and builds duration in minutes.

## Build Data

Build Data shows an overview of Jenkins build data over time

**Builds** shows a table that lets you sort values by build name, build result such as Success, Failure, and so on per build, node where the build happened, time taken in minutes for the build to be executed, and date and time when the build happened.

