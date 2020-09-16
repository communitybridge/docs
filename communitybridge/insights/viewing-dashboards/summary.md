# Summary

{% hint style="info" %}
By default, Bot commit is filtered, and can't be included for Summary dashboard.
{% endhint %}

Summary provides a high-level metrics about each data source for which the project is configured. Following are examples of some data sources for a project:

### **Highlights**

**Highlights** shows the total number of repositories, contributors, and commits for the project for  a selected time range. Click any of the three to go to [Commits Overview](source-control/git.md#GitRepositories-GitRepositories>Overview) page.

Following is an example of Highlights section:

### **Source Control**

**Source Control** shows overview analytics of project's git repositories for a selected time range:

A heading shows total number of number of contributors and organizations associated with the project.

**COMMITS & CONTRIBUTORS** shows a stacked area chart that compares the number of commits and contributors per calendar period. The total number of commits and contributor values are color-coded. Hover mouse over the graph to see the numbers for a particular date. Click **Commits** or **Contributors** to eliminate the corresponding data, for example: ![](../../../.gitbook/assets/18088223.png). Click the caption again to include the data.

**Top 10 COMPANIES \(**CONTRIBUTORS**\)** lists the top ten companies—that contribute most to the project— by name, total number of lines of codes changed that includes lines of codes added plus modified, number of commits, and percentage of commits out of the total number of commits by the community.

{% hint style="info" %}
* **Unknown** as a company name shows number/percentage of codes submitted by those contributors who are not affiliated with any organization.
{% endhint %}

**TOP 10 INDIVIDUALS \(**CONTRIBUTORS**\)** lists the top ten individuals—that contribute most to the project— by name, total number of lines of codes changed that includes lines of codes added plus modified, number of commits, and percentage of commits out of the total number of commits by the community.

**TOP 10 Projects** lists top ten projects that receive more number of commits, and the total number of repositories for each project.

Click **VIEW MORE** to open [Commits &gt; Overview](source-control/git.md#GitRepositories-GitRepositories>Overview) to see metrics of project's repositories. 

Following is an example of source control overview section:

### **Issue Management**

**Issue Management** shows overview analytics of issue management platforms, such as Jira, GitHub Issues, and Bugzilla.

A heading shows total issues, submitters, and assignees for a selected time range.

**ISSUES & SUBMITTING CONTRIBUTORS** shows a stacked area chart that compares the number of issues and unique contributors per calendar period. The number of issues and unique contributors for the project during each period are color-coded. Hover mouse over the graph to see the numbers for a particular date. Click **Contributors \(unique\)** or **Issues** to eliminate the corresponding data, for example![](../../../.gitbook/assets/18088222.png). Click the caption again to include the data.

**TOP 10 COMPANIES \(**SUBMITTERS**\)** lists the top ten companies— that contribute most to the project— by name, total number of issues, and percentage of issues out of the total number of issues submitted by the community.

{% hint style="info" %}
* **Unknown** as a company name shows number/percentage of issues submitted by those contributors who are not affiliated with any organization.
{% endhint %}

**TOP 10 INDIVIDUALS \(**SUBMITTERS**\)** lists the top ten individuals— that contribute most to the project— by name, total number of issues, and percentage of issues out of the total number of issues submitted by the community members.

**STATUS\(**Issues Distributed By Status**\)** shows a table that summarizes the issues by status depending on the issue management tool. It shows the number and percentage of issues per status out of the total issues.

Click **VIEW MORE** to go to the respective dashboard to see metrics of the issue dashboard.

Following an example of Issue Management overview section for a project that uses GitHub Issues, Jira, and Bugzilla to manage issues:

### **Chat Room**

**Chat Room** shows an overview analytics of slack channel used by a project.

A heading shows the total number of slack messages and channels.

**MESSAGING\(**Messages And Active Contributors**\)** shows a stacked area chart that compares the number of messages and unique contributors per calendar period. Hover mouse over the graph to see the numbers for a particular date. The number of messages and unique contributors for the project during each period are color-coded. Click **Contributors \(unique\)** or **Messages** to eliminate the corresponding data, for example ![](../../../.gitbook/assets/messages.png) . Click the caption again to include the data.

**TOP 10 COMPANIES \(**CONTRIBUTORS**\)** lists the top ten companies— that communicate most in the project— by name, total number of messages, and percentage of messages out of the total number of messages shared by the community.

{% hint style="info" %}
* **Unknown** as a company name shows number/percentage of messages shared by those contributors who are not affiliated with any organization.
{% endhint %}

**TOP 10 INDIVIDUALS \(**CONTRIBUTORS**\)** lists the top ten individuals—that communicate most in the project— by name, total number of messages, and percentage of messages out of the total number of messages shared by the community.

**TOP 10 CHANNELS \(Top Channels by Activity\)** lists the top ten slack channels where most amount of communication is happening. It shows the channel name, number of messages per channel, and percentage of messages per channel.

Click **VIEW MORE** to go to [Slack Overview](chat-room/slack.md#Slack-Slack>Overview) dashboard to see metrics of slack channel.

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

### **CI/CD**

**CI/CD** shows an overview analytics of the number of servers, jobs, and build numbers of a project over time. Following is an example of Distribution overview section. Click **VIEW MORE** to view [Jenkins Overview](ci-cd/jenkins.md#overview) dashboard.

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

