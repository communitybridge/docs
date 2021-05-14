# Summary

{% hint style="info" %}
By default, Bot commit is filtered, and can't be included for Summary dashboard.
{% endhint %}

Summary provides a high-level metrics about each data source for which the project is configured. Following are activities for quick navigation: 

\*\*\*\*[**Technical Trends**](summary.md#technical-trends)**:**

* [Source Control](summary.md#source-control)
* [Pull Requests / Changesets](summary.md#pull-requests-changeset)
* [Issue Management](summary.md#issue-management)
* [CI/CD](summary.md#ci-cd)
* [Registry](summary.md#registry)

\*\*\*\*[**Ecosystem Trends**](summary.md#ecosystem-trends)**:**

* [Chat Room](summary.md#chat-room)
* [Mailing List](summary.md#mailing-list)
* [Documentation](summary.md#documentation)
* [Earned Media](summary.md#earned-media)

## **Technical Trends**

Following dashboards are displayed under Technical Trends:

### **Source Control**

[Source Control](source-control/) shows analytic overview of git commits for a selected time range. Default time range is **Last 90 Days**. You can [select a time range](../../filter-data/select-time-range.md) to view  data for the selected time range.

* Clicking **Go To Overview** and **View All** takes you to the respective dashboard of [Commits &gt; Overview](source-control/git.md) page.

![Source Control](../../../.gitbook/assets/source-control%20%281%29.png)

**Commits** shows the following information:

* **Lines Of Code Changed** represents total number of lines changed—added, updated, and deleted—for a selected time range.
* **Commits** represents total number of commits for a selected time range.
* **Contributors** represents the number of contributors for the project
* **No Of Sub Projects** represents total number of sub projects \(added git repositories\) under a project.
* **Repositories** represents total number of repositories of the project. This includes the number of repositories of sub projects.

**Top 10 Contributors By Commits** lists the top ten individuals—that contribute most to the project— by name, total number of lines of codes changed that includes lines of codes added and modified, number and percentage of commits. Click **View All** to navigate to the [Commits &gt; Overview](source-control/git.md) page.

**Top 10 Companies By Commits** shows a doughnut chart that represents ****top ten companies that contribute most to the project.

Mouse over a color in the chart to view company name and number of commits made by the company. Click a company name to exclude company data. Click again to add the company data. Following is an example:  
 ![](../../../.gitbook/assets/show-and-exclude-company-data.png) 

{% hint style="info" %}
* **Unknown** as a company name shows number/percentage of codes submitted by those contributors who are not affiliated with any organization.
* **Others** represents a group that combines all other companies that come after top nine companies that contributes more.
{% endhint %}

### **Pull Requests /** Changeset

[Pull Requests/Changesets](pull-request-management/) shows analytic overview of pull request information of GitHub repositories and/or information about changesets and patchsets per changeset for Gerrit.

{% hint style="info" %}
Data is not available for a Git data source that is not configured for  Insights.
{% endhint %}

**Gerrit** shows total number of changesets \(both open and closed\), number of open changestes, average time in hours to merge changesets, average time in days for first review of changeset, and total number of approved changesets for a selected time range.

* Clicking **Go To Overview** and **View All** under **Gerrit** takes you to the respective table/graph/chart of [Gerrit Changesets &gt; Overview](pull-request-management/gerrit-changeset.md#overview) section.

![Gerrit Dashboard](../../../.gitbook/assets/gerrit-dashboard.png)

**GitHub** shows total number of pull requests \(both open and closed\), number of open pull requests, average time in hours to merge pull requests, and average time in hours pull requests were open for a selected time range.

* Clicking **Go To Overview** and **View All** under **Gerrit** takes you to the respective table/chart/graph of [GitHub PR &gt; Overview](project-management/github-issues.md#overview) section.

![Pull Requests GitHub](../../../.gitbook/assets/pull-requests-github.png)

**Top 10 Contributors By PRs** \(for GitHub\) ****or **Top 10 Contributors By Changesets** \(for Gerrit\) ****lists the top ten individuals—that contribute most to the project— by name, total number of pull requests or changestes, and percentage of commits out of the total number of commits by the community.

**Top 10 Companies By PRs** \(for GitHub\) ****or **Top 10 Companies By Changesets** \(for Gerrit\) ****shows a doughnut chart that represents ****top ten companies that contribute most to the project.

* Mouse over a color in the doughnut chart to view company name and number of commits made by the company. 
* Click a company name to exclude company data. Click again to add the company data. Following is an example:  ![](../../../.gitbook/assets/top-10-companies.png)

{% hint style="info" %}
* **Unknown** as a company name shows number/percentage of codes submitted by those contributors who are not affiliated with any organization.
* **Others** represents a group that combines all other companies that come after top nine companies that contributes more.
{% endhint %}

### **Issue Management**

[Issue Management](project-management/) shows analytic overview of issue management platforms used by a project, such as Jira, GitHub Issues, and Bugzilla.

**Jira** shows total number issues that includes both open and closed issues, total number of submitters, number of open issues, average time in days the issues are open, and time in days for which a stacked area chart compares the number of issues and unique contributors per calendar period.

* Clicking **Go To Overview** and **View All** under **Jira** takes you to the respective table/chart/graph of [Jira &gt; Overview](project-management/jira.md#overview) section.

**GitHub Issues** shows total number issues that includes both open and closed issues, total number of submitters, number of open issues, average time in days the issues are open and average time in days the issues took to be resolved.

* Clicking **Go To Overview** and **View All** under **Github Issues** takes you to the respective table/chart/graph of [GitHub Issues &gt; Overview](project-management/github-issues.md#overview) section.

**Bugzilla** shows total number issues that includes both open and closed issues, total number of submitters, number of open issues, total time in days the issues are open, and time in days issues took to be closed.

* Clicking **Go To Overview** and **View All** under **Bugzilla** takes you to the respective table/chart/graph of [Bugzilla &gt; Overview](project-management/bugzilla.md#Bugzilla-Bugzilla>Overview) section.

**Top 10 Contributors By Issues Submitted** lists the top ten individuals— that contribute most to the project— by name, total number of issues, and percentage of issues out of the total number of issues submitted by the community members.

**Top 10 Companies By Issues Submitted shows a doughnut chart that represents** top ten companies that contribute most to the project.

Mouse over a color in the doughnut chart to view company name and number of commits made by the company. Click a company name to exclude company data. Click again to add the company data. Following is an example:  
 ![](../../../.gitbook/assets/top-10-companies-github-issues.png) 

{% hint style="info" %}
* **Unknown** as a company name shows number/percentage of issues submitted by those contributors who are not affiliated with any organization.
* **Others** represents a group that combines all other companies that come after top nine companies that contributes more.
{% endhint %}

Following an example of Issue Management overview section for a project that uses Jira, GitHub Issues, and Bugzilla to manage issues:

![Issue Management](../../../.gitbook/assets/issue-management%20%281%29.png)

### **CI/CD**

[CI/CD](ci-cd/) ****shows an analytic overview of the number of total builds, jobs, failed builds, job categories, and average build duration in minutes. Clicking **Go To Overview** and **View All** under **CI/CD** takes you to the respective table/chart/graph of [Jenkins &gt; Overview](ci-cd/jenkins.md#overview) and [CircleCI &gt; Overview](ci-cd/circle-ci.md#overview) sections respectively.

**Top 10 Jobs** lists the top ten jobs by name, number, and percentage.

**Build Results** for Jenkins and **Jobs Results** for CircleCI shows a doughnut chart that represents total number of builds for all the build results, such as Success, Failure, Unstable, and Aborted. Click a result to exclude the data. Click again to include.

![Ci/Cd](../../../.gitbook/assets/ci-cd.png)

### **Registry**

[Registry](registry/) shows total number of median pulls, average stars for images, increase number in pull count, and star counts for DockerHub. Clicking **Go To Overview** and **View All** opens the respective table/chart/graph of [Docker &gt; Overview](registry/dockerhub.md#DockerHub-DockerHub>Overview) section.

**Top 10 images By Pull Count** lists the top ten pulls by name, number, and percentage.

**Top 10 images By Star Count** lists the top ten stars by name, number, and percentage.

![Registry](../../../.gitbook/assets/registry.png)

### **Ecosystem Trends**

Following dashboards are displayed under Technical Trends:

### **Chat Room**

[Chat Room](../ecosystem-trends/chat-room/) ****shows an analytic overview of Slack and RocketChat channels used by a project.

**Slack** shows total number of messages, channels, participants, replies, and reactions over time. Clicking **Go To Overview** and **View All** under **Slack** takes you to the respective table/chart/graph of [Slack &gt; Overview](../ecosystem-trends/chat-room/slack.md#overview) section.

**RocketChat** shows total number of messages, channels, participants, replies, and reactions over time. Clicking **Go To Overview** and **View All** under **RocketChat** takes you to the respective table/chart/graph of [RocketChat &gt; Overview](../ecosystem-trends/chat-room/rocket-chat.md#overview) section.

**Top 10 Message Senders** lists the top ten individuals—who communicate most in the project— by name, number of messages, and percentage of messages out of the total number of messages shared by the community.

**Top 10 Channels** lists the top ten slack channels where most amount of communication is happening. It shows the channel name, number of messages per channel, and percentage of messages per channel. Following is an example of chat room dashboard:

![Chat Room](../../../.gitbook/assets/chat-room%20%281%29.png)

### **Mailing List**

[Mailing List ](../ecosystem-trends/mailing-list/)shows an analytic overview of email communication channels, such as Groups.io or Pipermail:

**Groupsio** shows total number of emails, groups, companies, authors, and average number of messages communicated over time.

**Google Groups** shows a richer context around how frequently the community is interacting. ****Project community managers can use metrics like “Daily Active Users”, “Emails by Organization”, and even “Top Trending Topics” to better engage and acknowledge their community members. For detail metrics, see [Google Groups](../ecosystem-trends/mailing-list/google-groups.md).

**Piper Mail** shows total number of emails, mailing lists, companies, authors, and average number of messages communicated over time.

**Top 10 Email Senders** lists the top ten individuals—who communicate most in the project— by name, number of emails, and percentage of emails out of the total number of emails shared by the community.

**Top 10 Mailing Lists** lists the top ten email lists where most number of communication is happening. It shows the list name, number of emails per list, and percentage of emails per list. 

![Mailing List](../../../.gitbook/assets/mailing-list.png)

### **Documentation**

[Documentation](../ecosystem-trends/documentation/) shows an analytic overview of project's [confluence](../ecosystem-trends/documentation/confluence.md) pages for a selected time range. It shows total number of confluence pages created/edited, total number comments in the form of feedback or conversation on confluence pages, total number of editors who contributed to create/edit or provide feedback/comment on the confluence pages, and average number of editors per day.

**Top 10 Editors** lists the top ten individuals— who makes most number of edits/updates— by name, number of pages edited by the individual, and percentage of contribution out of the total document contribution by the community members.

**Top 10 Companies** lists the top ten companies— that contribute most to the project— by name, total number of editions, and percentage.

![Documentation](../../../.gitbook/assets/documentation.png)

### Earned Media

[Earned Media](../ecosystem-trends/earned-media/) shows analytic overview of how many times consumers \(unique users\) searched, mentioned, and shared project related articles or blogs  on different media platforms, such as facebook, linkedin, blog sites, news publishing websites, and so on. The data includes various metrics, such as geographical data, sentiment analysis, SEO metrics, social media sharing/mentions, publishers, and so on.

**Total Shares** shows how many times a project's search results are shared by consumers on different social media platforms. This also shows number of shares on individual social media platforms.

**Top 10 Publishers** lists top ten media houses and blog sites that mention most about the project in the form of articles and blog posts. It includes the number and percentage of mentions about your project.

**Key Messages** shows a doughnut chart that displays how many times the project and its competitors' search results are mentioned by consumers \(unique users\). Mouse over a color in the chart to see the number of mentions for a project out of the total mentions. For example, Linux Foundation is mentioned 4.88k times by consumers on different media platforms out of the total 6.52k times including its competitors' mentions as per the following data.

![Earned Media](../../../.gitbook/assets/earned-media.png)



