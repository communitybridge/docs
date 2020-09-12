# Summary

{% hint style="info" %}
By default, Bot commit is filtered, and can't be included for Summary dashboard.
{% endhint %}

Summary provides a high-level metrics about each data source for which the project is configured. Following are activities for quick navigation:

* Click Copy Short URL ![](../../../.gitbook/assets/copy-short-url.png) to copy the link of summary dashboard for a project.
* Select a value from Source Control drop down to quickly navigate to the respective section.  ![](../../../.gitbook/assets/source-control-drop-down%20%282%29.png) 
* Clicking sparklines ![](../../../.gitbook/assets/sparkly-lines.png)  opens a stacked bar graph that represents relevant data per calendar period.  ![](../../../.gitbook/assets/sparkly-line.png) 
* Clicking numbers on a data card opens the respective dashboard.  ![](../../../.gitbook/assets/click-for-dashboard.png) 

### **SOURCE CONTROL**

**Source Control** shows overview analytics of git commits for a selected time range. Default time range is **Last 90 Days**. You can [select a time range](../filtering-data/select-time-range.md) to view  data for the selected time range.

* Clicking **Go To Overview** and **View All** takes you to the [Commits &gt; Overview](source-control/git.md) page.

![Source Control](../../../.gitbook/assets/source-control%20%281%29.png)

**Commits** shows the following information:

* **Lines Of Code Changed** represents total number of lines changed—added, updated, and deleted—for a selected time range.
* **Commits** represents total number of commits for a selected time range.
* **Contributors** represents the number of contributors for the project
* **No Of Sub Projects** represents total number of sub projects \(added git repositories\) under a project.
* **Repositories** represents total number of repositories of the project. This includes the number of repositories of sub projects.

**Top 10 Contributors** lists the top ten individuals—that contribute most to the project— by name, total number of lines of codes changed that includes lines of codes added plus modified, number of commits, and percentage of commits out of the total number of commits by the community. Click **View All** to navigate to the [Commits &gt; Overview](source-control/git.md) page.

**Top 10 Companies**  lists the top ten companies—that contribute most to the project— by name, total number of lines of codes changed that includes lines of codes added plus modified, number of commits, and percentage of commits out of the total number of commits by the community.

Mouse over a color in the doughnut chart to view company name and number of commits made by the company. Click a company name to exclude company data. Click again to add the company data. Following is an example:  
 ![](../../../.gitbook/assets/show-and-exclude-company-data.png) 

{% hint style="info" %}
* **Unknown** as a company name shows number/percentage of codes submitted by those contributors who are not affiliated with any organization.
* **Others** represents a group that combines all other companies that come after top nine companies that contributes more.
{% endhint %}

### **PULL REQUESTS /** CHANGESETS

Pull Requests/Changesets shows analytics of pull request information of GitHub repositories and/or information about changesets and patchsets per changeset for Gerrit.

{% hint style="info" %}
Data is not available for a Git data source that is not configured for CommunityBridge Insights.
{% endhint %}

**Gerrit** shows total number of changesets \(both open and closed\), number of open changestes, average time in hours to merge changesets, average time in days for first review of changeset, and total number of approved changesets for a selected time range.

* Clicking **Go To Overview** and **View All** under **Gerrit** takes you to the [Commits &gt; Overview](source-control/git.md) page.

**GitHub** shows total number of pull requests \(both open and closed\), number of open pull requests, average time in hours to merge pull requests, and average time in hours pull requests were open for a selected time range.



Changesets shows total number of changesets

### **ISSUE MANAGEMENT**

**Issue Management** shows analytics of issue management platforms, such as Jira, GitHub Issues, and Bugzilla.

**Issues** shows total number issues that includes both open and closed issues, total number of submitters, number of open issues, average time in days for which a stacked area chart that compares the number of issues and unique contributors per calendar period. The number of issues and unique contributors for the project during each period are color-coded. Hover mouse over the graph to see the numbers for a particular date. Click **Contributors \(unique\)** or **Issues** to eliminate the corresponding data, for example![](../../../.gitbook/assets/18088222.png). Click the caption again to include the data.

**Top 10 Submitters** lists the top ten individuals— that contribute most to the project— by name, total number of issues, and percentage of issues out of the total number of issues submitted by the community members.

**Top 10 Companies** lists the top ten companies— that contribute most to the project— by name, total number of issues, and percentage of issues out of the total number of issues submitted by the community.

Mouse over a color in the doughnut chart to view company name and number of commits made by the company. Click a company name to exclude company data. Click again to add the company data. Following is an example:  
 ![](../../../.gitbook/assets/show-and-exclude-company-data.png) 

{% hint style="info" %}
* **Unknown** as a company name shows number/percentage of issues submitted by those contributors who are not affiliated with any organization.
* **Others** represents a group that combines all other companies that come after top nine companies that contributes more.
{% endhint %}

Following an example of Issue Management overview section for a project that uses Jira, GitHub Issues, and Bugzilla to manage issues:

![Issue Management](../../../.gitbook/assets/issue-management%20%281%29.png)

### **Chat Room**

**Chat Room** shows an overview analytics of slack and RocketChat channels used by a project.

**MESSAGING\(**Messages And Active Contributors**\)** shows a stacked area chart that compares the number of messages and unique contributors per calendar period. Hover mouse over the graph to see the numbers for a particular date. The number of messages and unique contributors for the project during each period are color-coded. Click **Contributors \(unique\)** or **Messages** to eliminate the corresponding data, for example ![](../../../.gitbook/assets/messages.png) . Click the caption again to include the data.

**TOP 10 COMPANIES \(**CONTRIBUTORS**\)** lists the top ten companies— that communicate most in the project— by name, total number of messages, and percentage of messages out of the total number of messages shared by the community.

{% hint style="info" %}
* **Unknown** as a company name shows number/percentage of messages shared by those contributors who are not affiliated with any organization.
{% endhint %}

**TOP 10 INDIVIDUALS \(**CONTRIBUTORS**\)** lists the top ten individuals—that communicate most in the project— by name, total number of messages, and percentage of messages out of the total number of messages shared by the community.

**TOP 10 CHANNELS \(Top Channels by Activity\)** lists the top ten slack channels where most amount of communication is happening. It shows the channel name, number of messages per channel, and percentage of messages per channel.

Click **VIEW MORE** to go to [Slack Overview](chat-room/slack.md#Slack-Slack>Overview) dashboard to see metrics of slack channel.

![Chat Room](../../../.gitbook/assets/chat-room%20%281%29.png)

### **Mailing List**

**Mailing List** shows an overview analytics of email communication channels, such as Groups.io or Pipermail:

A heading ****shows total number of emails shared by the community members, and  total number of e-mail lists created for communication.

**EMAILING \(**Emails And Active Contributors**\)** shows a stacked area chart that compares the number of emails and unique contributors per calendar period. Hover mouse over the graph to see the numbers for a particular date. The number of e-mails and unique contributors of the project during each period are color-coded. Click **Contributors \(unique\)** or **Emails** to eliminate the corresponding data, for example ![](../../../.gitbook/assets/emails.png) . Click the caption again to include the data.

**TOP 10 COMPANIES \(**CONTRIBUTORS**\)** lists the top ten companies— that communicate most in the project— by name, total number of messages, and percentage of messages out of the total number of messages shared by the community.

{% hint style="info" %}
* **Unknown** as a company name shows number/percentage of messages shared by those contributors who are not affiliated with any organization.
{% endhint %}

**TOP 10 INDIVIDUALS \(**CONTRIBUTORS**\)** lists the top ten individuals—that communicate most in the project— by name, total number of messages, and percentage of messages out of the total number of messages shared by the community.

**TOP 10 Lists \(Top Lists by Activity\)** lists the top ten email lists where most amount of communication is happening. It shows the list name, number of messages per list, and percentage of messages per list.

Click **VIEW MORE** to view metrics of the respective communication channel.

![Mailing List](../../../.gitbook/assets/mailing-list%20%281%29.png)

### **CI/CD**

**CI/CD** shows an overview analytics of the number of servers, jobs, and build numbers of a project over time. Following is an example of Distribution overview section. Click **VIEW MORE** to view [Jenkins Overview](ci-cd/jenkins.md#overview) dashboard.

![](../../../.gitbook/assets/ci-cd%20%281%29.png)

### **Registry**

**Registry** shows overview analytics of docker images of the project repository for a selected time range:

* A heading shows ****total number of docker images, 50th percentile of median stars and pulls by images.
* A table lists docker image links, total number of starts and pulls for an image.

Click **VIEW MORE** to see metrics of [docker overview](registry/dockerhub.md#DockerHub-DockerHub>Overview).

Following is an example of Registry overview section:

![Registry](../../../.gitbook/assets/registry%20%281%29.png)

### **Documentation**

**Documentation** shows an overview analytics of project's confluence pages for a selected time range. It shows total number of confluence pages created/edited, total number comments in the form of feedback or conversation on confluence pages, and total number of editors who contributed to create/edit or provide feedback/comment on the confluence pages.

Click **VIEW MORE** to see metrics of [confluence pages](documentation/confluence.md#Confluence-Confluence>Overview).

Following is an example of Documentation overview section:

![Documentation](../../../.gitbook/assets/documentation%20%281%29.png)

