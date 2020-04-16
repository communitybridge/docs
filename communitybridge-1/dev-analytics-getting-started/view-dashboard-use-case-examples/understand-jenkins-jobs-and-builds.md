# Understand Jenkins Jobs and Builds

{% hint style="info" %}
Role: Technical Manager

Where: Jenkins dashboards are available from the **Technical Management** drop-down list.
{% endhint %}

As a technical manager of a project, you have concerns about aspects of your Jenkins jobs and builds. You want to understand what jobs and their corresponding builds have long duration times or high percentages of failures or instabilities so your team can work to increase efficiency. You may also want to know how quickly the builds are getting fixed, or if some test cases are permanently failing and either need updating or reviewing.

**Do these steps:**

1. Click a **project name** of interest.
2. From the **Technical Management** drop-down list, select **Jenkins** &gt;**Overview**.  
   A dashboard show Jenkins overview data:  
   Jenkins &gt; Overview

   SUMMARY: Overview shows an overview of Jenkins build and job data over time.

   **Jenkin Overview** shows the number of servers, jobs, and builds  for a project.

   **Jenkin Builds** shows the total number of builds for a particular week by date. Mouse over a color to see the total number of builds for a week by date.

   **Jenkins - Avg. Build Duration Over Time Per Job** shows the time in minutes for the total number of jobs per day over time and a trend line to show an increase, decrease, or stability in the job time.

   **Jenkin Summary** shows a table that lets you sort values by Job Name, Total Builds, Last Build, and Last Build Timestamp.

   **Jenkin Results** shows a doughnut chart that represents the total number of builds in the project by status: SUCCESS, FAILURE, UNSTABLE, ABORTED. Mouse over a color in the chart to see the status, total number of builds for the status, and the percentage of the project's builds for that status.

3. Use the visualizations to understand various build aspects of the project. For example, each new build must go through a series of steps including compilation, testing, and validation. You want these steps to be optimized to ensure that changes are delivered quickly. The longer the build process takes, the longer it takes for changes to make their way into production. The **Builds** table shows the total time to complete a build \(in seconds\). By seeing the build time for a particular job, you can understand the build process and monitor it for abnormalities. If a build ends too quickly or takes too long, it could indicate a problem with the build server or the build pipeline.
4. From the **Technical Management** drop-down list, select **Jenkins** &gt; **Jobs**.  
   A dashboard show Jenkins job data:Jenkins &gt; Jobs

   SUMMARY: Jobs shows data about Jenkins jobs such as duration, successes, and failures over time.

   **Jenkins\_jobs\_result** shows the number of success count, failure count, aborted count, and unstable count of builds.

   **Jenkin Results** shows a doughnut chart that represents the total number of jobs in the project by status: SUCCESS, FAILURE, UNSTABLE, ABORTED. Mouse over a color in the chart to see the status, total number of jobs for the status, and the percentage of the project's jobs for that status.

   **Jenkins\_jobs\_builds\_chart** shows a bar graph that represents the number of jobs per day over time.

   **Jenkins - Avg. Build Duration Over Time Per Job** shows the time in minutes for the total number of jobs per day over time and a trend line to show an increase, decrease, or stability in the job time.

   **Jenkins\_jobs\_simple\_summary** shows a table that lets you sort values by Job Name, Builds, URL, and Last Build.

5. Use the visualizations to understand various job aspects of the project. **Success/Failures in percentage** is useful because it shows the ratio of successful jobs to unsuccessful jobs, and how healthy your jobs are in builds. You can see the build and job health as a total and see how it has changed over time.

