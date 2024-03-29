# Commits

{% hint style="info" %}
By default, Empty Commits (Commits with Zero value) and Bots are filtered, however, you can include these filter values by navigating to the filter section of dashboard. For details, see [Add and Manage Data Filters](../../filter-data/add-and-manage-data-filters.md).
{% endhint %}

The Commits dashboard represents a set of metrics that shows high level information, such as total number of commits, authors, repositories, and so on for  all repositories of the project.

## **Overview** <a href="#gitrepositories-gitrepositories-greater-than-overview" id="gitrepositories-gitrepositories-greater-than-overview"></a>

Overview shows information about commits in Git repositories. For each commit, Git stores information about who and when authored the commit (author), and about the organization that included the commit in the repository.

**Filter** lets you filter the dashboard data by author name, organization name, and repository. Select values from the respective drop-down lists, and click **Apply changes** to filter the dashboard as per selection.

**Summary** shows the number of Commits, Authors, and Repositories of the project.

**Commits Percentage By Organization** shows a doughnut chart that represents the total number of commits by organization for the project. Mouse over a color in the chart to see the total number of commits by the organization, and the percentage of commits out of the total commits for the project.

**Lines Changed Percentage By Organization** shows a doughnut chart that represents the total number of lines of code changed by an organization for the project. Mouse over a color in the chart to see the total number of lines of code changed by the organization, and the percentage out of the total lines of code that are changed for the project.

**Active Contributors** shows  a bar graph that represents the number of contributors per day over time. Mouse over a color in the graph to see the total number of contributors for a date.

**Commits** shows a bar graph that represents the number of commits per day for the project over time. Mouse over a color in the graph to see the total number of commits for a date.

**Commits by Time Zone** shows a bar graph with a count of commits per Coordinated Universal Time (UTC) time zone. Dates and times (author time, committer time) in Git use the time zone of the computer where the contributor performed the action. This data is used to display time zone information. Mouse over a color in the graph to see the total number of commits for each time zone.

**Commits By Organization** shows  a bar graph that represents the number of commits by an organization per day over time. Mouse over a color in the graph to see the total number of contributors of an organization including organization's name for a date.

**Lines of Code Changed By Organization** shows  a bar graph that represents the number of lines of code changed by an organization per day over time. Mouse over a color in the graph to see the organization's name, date, and total number of lines of code changed by the organization.

**Authors** shows a table that lists author name, number of commits by the author, number of projects the author has committed code to, number of lines the author has added and removed codes, and the average number of files the author has worked over time.

**Organizations** shows a table that lists:

* **Organization:** name of organization
* **Commits:** number of commits made by the organization
* **Authors:** number of authors of the organization who made commits
* **Touched Files:** number of files the organization has contributed towards
* **Added Lines:** number of added lines to the code base
* **Removed Lines:** number of removed lines from the code base
* **Projects:** number of projects the organization is contributing towards
* **Repositories:** number of repositories of the project the organization is contributing towards, and
* **Avg Lines/Commit:** average number of lines added or commits made by the organization over time

**Repositories** shows a table that lists repository name with links, number of commits made to the repository, number of authors contributed to the repository, number of organizations contributed to the repository, number of lined added and removed to/from the code base of the repository, average number of files touched or commits made to the repository over time.

**Projects** shows a table that lists project names, number of commits, authors, repositories, number of added lines, removed lines, average number of lines committed, and average number of files committed per project.

**Organization Commits** shows a table that lets you sort values by commit hash, organization name, repository URL, author name, and date.
