# Understand Jenkins Jobs and Builds

{% hint style="info" %}
Role: Technical Manager

Where: Jenkins dashboards are available from the **CI/CD** drop-down list.
{% endhint %}

As a technical manager of a project, you have concerns about aspects of your Jenkins jobs and builds. You want to understand what jobs and their corresponding builds have long duration times or high percentages of failures or instabilities so your team can work to increase efficiency. You may also want to know how quickly the builds are getting fixed, or if some test cases are permanently failing and either need updating or reviewing.

**Do these steps:**

1. Click a **project name** of interest.
2. From the **CI/CD** drop-down list, select **Jenkins** &gt; **Overview**. A dashboard show Jenkins overview data. For details, see [Jenkins &gt; Overview](../view-dashboard-catalog-of-a-project/ci-cd/jenkins.md#overview).
3. Use the visualizations to understand various build aspects of the project. For example, each new build must go through a series of steps including compilation, testing, and validation. You want these steps to be optimized to ensure that changes are delivered quickly. The longer the build process takes, the longer it takes for changes to make their way into production. The **Builds** table shows the total time to complete a build \(in seconds\). By seeing the build time for a particular job, you can understand the build process and monitor it for abnormalities. If a build ends too quickly or takes too long, it could indicate a problem with the build server or the build pipeline.
4. From the **CI/CD** drop-down list, select **Jenkins** &gt; **Jobs**. A dashboard show Jenkins job data. For details, see [Jenkins &gt; Jobs](../view-dashboard-catalog-of-a-project/ci-cd/jenkins.md#jobs).
5. Use the visualizations to understand various job aspects of the project. **Success/Failures in percentage** is useful because it shows the ratio of successful jobs to unsuccessful jobs, and how healthy your jobs are in builds. You can see the build and job health as a total and see how it has changed over time.

