# Circle CI

The CircleCI dashboards under CI/CD drop-down list represents a set of metrics that show overview analysis of CircleCI build system data. Following are the various dashboards of CircleCI:

* [Overview](circle-ci.md#overview)
* [Jobs](circle-ci.md#jobs)
* [Workflows](circle-ci.md#workflows)

## Overview

**Overview** shows total number of pipelines, workflows, and jobs for the project.

**Job status percentage** shows a doughnut chart that displays build jobs by status: success, failed and cancelled. Mouse over a color to view number and percentage of build jobs.

**Workflow** status percentage shows a doughnut chart that displays workflows of build jobs by status: success, failed, cancelled, and other. Other includes statuses such as running, not run, on hold, and so on. Mouse over a color to view number and percentage of workflows.

**Job status trend** shows line graphs that display total number of jobs per status on a timely basis. Mouse over the graph to view numbers.

**Workflow duration trend** shows line graphs that display minimum and maximum time \(in minutes\) taken to complete a workflow. It also displays the average time \(in minutes\) taken by 50% of the total number of workflows to be completed.

**Workflow Duration \(minutes\) 95th Percentile** shows a bar graph that displays time  taken in minutes to complete 95% of total build jobs created per day.

**Workflow status by author** shows a table that lists name of authors, total number of workflows \(by status\) created by the author: success, failed, cancelled, and approved.

**Workflow status by organization** shows a table that lists name of organizations the authors belong to, total number of workflows \(by status\) created by the authors of the organization: success, failed, and cancelled.

**Workflow status by origin repository** shows a table that lists origin repositories where the build job is created, target repository, number of build jobs by status: success, failed, and cancelled. 

**Job run count** shows table that lists the job number, related project name, and number of times the job was run to complete the workflow.

## Jobs

**Jobs Overview** shows total number of build jobs over time along with how many jobs are success, failed, and cancelled over time.

**Job Status** shows a doughnut chart that displays number and percentage of build jobs over time. Mouse over a color to view details.

**Job Status on a time series** shows a colored bar graph that displays timely total count of jobs along with the how many job numbers are success, failed, and cancelled over time.

**Jobs status trend** shows line graphs that represent gradual increase or decrease of the build jobs by status, such as how many jobs are success, failed or cancelled over time. Mouse over a point in the graph to view details.

**Job duration trend** shows line graphs that represent gradual increase or decrease in maximum and minimum time taken in minutes to complete the build jobs. It also shows average time taken in minutes to complete 50% of the total jobs created over time. Mouse over a point in the graph to view details.

**Job duration-Max, Median and Min** shows a colored bar graph that displays maximum and minimum time taken in minutes to complete the build jobs created over time. It also shows average time taken in minutes to complete 50% of the total jobs created over time. Mouse over a color in the graph to view details.

**Job executor type** shows a doughnut chart that displays number and percentage of jobs executed using a particular containerization technology, such as Docker. Mouse over a color to view details.

**Job executor instance size** shows a doughnut chart that displays number and percentage of completed jobs by size, such as large, medium, xlarge, and so on.

## Workflows

**Workflow Overview** shows total number of workflows over time along with how many workflows are success, failed, and cancelled over time.

**Workflow duration trend** shows line graphs that represent gradual increase or decrease in maximum and minimum time taken in minutes to complete the workflows. It also shows average time taken in minutes to complete 50% of the total workflows created over time. Mouse over a point in the graph to view details.

**Workflow Status on a time series** shows a colored bar graph that displays timely total count of workflows along with how many workflows are success, failed, and cancelled over time.

**Workflow status by orgs** shows a table that lists organization name, and how many workflows run by the organization are in success, failed, and cancelled states over time.

**Workflow by orgs** shows a colored doughnut chart that represents different organizations, and total number of workflows run by the organization irrespective of the workflow statuses. Mouse over a color to view details.

**Workflow status by circle maintainers** shows a table that lists workflow author names along with the how many workflows are success, failed, cancelled, and approved per author.

**Workflow status by repositories** shows a table that lists origin repository where the workflow is created, target repository along with the how many workflows are success, failed, and cancelled.

**MTTR in last 90 days by Workflow in Hours** shows a table that displays how much time \(in hours\) it took for a workflow to recover from the failed state. Mean Time To Recover \(MTTR\) displays data only for last 90 days.

