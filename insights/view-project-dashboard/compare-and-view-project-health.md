# Compare and View Project Health

You can anytime view the overall metrics of a project for a given time period. Project Health Dashboard lets you visualize the overall code commits, pull requests, changesets, issues, and related data source statistics for a given project, and also provides the ability to compare the project statistics between two or more projects. Following are the data sources currently supported by LFX Insights for viewing the overall project health:

* Git
* Github Pull Requests
* Github Issues
* Gerrit 
* Jira
* Bugzilla / Bugzilla Rest

**To View Project Health Dashboard:**

 1. Go to[ https://insights.lfx.linuxfoundation.org/](https://insights.lfx.linuxfoundation.org/)

2. From the top left corner, click Compare Project Health.  


![Compare Project Health](https://lh5.googleusercontent.com/jkn4-dxyPJSXTkbZKrpvsv56tnE8v0Alhsfc5_1Ok_P8MHuD-hMPhVx8Q_nw8U42RgIDJrooQ1n6SmODF4VcYIGbfCJXxFHN_i1yc8X4-acn0fgHRxRz3zAXbCMbp33ekFlul0i2)

3. Type and select a project in the **Search Projects** field.

4. Click **+Project** to add a new field to select and compare projects.   
**Note:** Default time range is “All”. Select a time range from the available options to change the metrics for the time period.

5. Following are the list of statistics displayed for different data sources:

1. **Commits**: Commits show git commit status, such as last commit date, total number of commits, total number of contributors, percentage of commits from top organizations including the affiliated contributors, and so on.
2. **Pull Requests**: Pull Requests show total number of open, closed, and merged PRs, total number of PRs rejected, total number of contributors reviewing PRs, percentage of PRs merged from top organizations, and so on.
3. **Changesets**: Changesets show total number of open/closed/approved/merged changesets, percentage of changesets merged from top organizations, percentage of contributors merging the changesets, and so on.
4. **Jira/Bugzilla Issues**: Each section shows total number of issues, submitters, assignees, issues in open state, total number of reopened issues, total number of issues in closed, complete state, percentage of issues submitted by top organizations, percentage of submitters from top organizations, and so on.

![Compare Project Health](../../.gitbook/assets/compare-project-health.png)



