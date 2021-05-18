# Insights FAQs

### How does LFX Insights work?

LFX Insights collects data for a project, segregates them to different data sources, such as source control for code related data, issue management for issues statuses, documentation for confluence and wiki pages, CI/CD for build systems, and so on. It represents these data on different visualization dashboards, such as graphs, charts, and tables.

### What is a Data Source?

Data sources are the collaboration tools or the remote servers that are used by projects to drive the development of a project. For example, in a database management system, the primary data source is the database, which can be located in a disk or a remote server. The data source for a computer program can be a file, a data sheet, a spreadsheet, an XML file or even hard-coded data within the program.

### What are the Data Sources supported by The Linux Foundation?

The Linux Foundation supports various data sources string from source control systems to social media platforms to collect and visualize project's data. For details, see [Supported Data Sources](supported-data-sources.md).

### **Does Insights monitor forked repositories?**

No, Insights does not monitor forked repositories. A repository that is forked from another public repository contains commits from upstream projects and the current version of Insights cannot correctly differentiate between the contributions done on the forked repository and those coming from upstream. Hence, as a rule Insights does not monitor forked repositories.

### **What if a repository gets deleted on the Version Control System? Will the data thus collected be deleted too?**

In case if a repository that was being monitored**,** and later is deleted, then we will keep the data from the old repository as historical endpoints, and the data will be reflected on the dashboards when queried for the time period during which there were activities on that repository.

### **What are the changes added to Insights Github?**

With our latest upgrade to the github service, we are collecting more data than ever before**,** and producing many more metrics, such as detailed reviewer data and better efficiency statistics that were absent in the earlier versions. Since this upgrade affected the structure of the github data and the schema of the database, any github repository endpoint that can no longer be reached because they might have been deleted forever, and will not be included in our metrics reporting as we have no way to sync data for sync endpoints. If the repositories are renamed, then we can still process the data for the endpoint and there will be no loss in the data thus collected.

### **How does Insights collect Google Groups Mailing List Data?**

The Insights agents for google groups are designed to monitor the mailing lists by becoming a subscriber of those mailing lists, and reporting back to our servers all the emails that have been communicated. Once we have the raw emails, we enrich the data, and present them on the Insights dashboard for google groups. It involves two processes: Getting the archived data from project administrators, and syncing the email on a daily basis.

* **Getting the archived data for all the google groups mailing list:** In this step, project administrators must provide us a zipped archive \(attached to a support help desk ticket\) of the most recent emails for the mailing lists that we monitor in LFX Insights as our Insights agents cannot collect data from the past where our agent was not a part of the mailing list. If a new google group mailing list is created, the project administrator must inform the Insights team so that we can add our agent to the mailing list to monitor the activity.
* **Syncing emails everyday:** Once we receive the archives, we import all the emails, and from that time onwards, we regularly sync all the emails as by then our google group agent will be a part of the mailing lists.

### Who can see LFX Insights reports?

Anyone can see reports for projects that are on LFX platform. However, only project maintainers can see information related to affiliation management, and email ids of contributors.

### How does LFX Insights help?

It helps open source project maintainers monitor their project activity, total and individual contribution towards the project, active contributor lists, any unaffiliated contributors, and so on. This helps maintainers to solve problems effectively such as coding activity, code review backlog, performance, bottleneck identification, issue resolution, and so on.

### Does LFX Insights automatically create visualization reports?

Yes, if your project is set up on Linux Foundation's SFDC \(Sales Force Dot Com\) database, then LFX Insights automatically collects and visualizes data on graphs, charts, tables, and other customized dashboards.

### How are unaffiliated contributions calculated?

Unaffiliated contributions are not counted under any organization, and are grouped as **Unknown**. LFX highly recommends to affiliate top contributors of your project.

### Is affiliation data linked to one project?

No, affiliation data is linked to profiles, and profiles are visible across all the projects that they are part of. So, affiliation data for profiles are also visible across projects that they are part of.

### How are contributions calculated?

Insight calculates contribution data based on commit hash. So, if a pull request or changeset is submitted to two different branches with the same commit hash identification number, Insight counts it as a single contribution, eliminating duplication of data.

