# Insights FAQs

## How does LFX Insights work?

LFX Insights collects data for a project, segregates them to different data sources, such as source control for code related data, issue management for issues statuses, documentation for confluence and wiki pages, CI/CD for Jenkins, and so on. It represents these data on different visualization dashboards, such as graphs, charts, and tables.

## What is a Data Source?

Data sources are the collaboration tools or the remote servers that are used by projects to drive the development of a project. For example, in a database management system, the primary data source is the database, which can be located in a disk or a remote server. The data source for a computer program can be a file, a data sheet, a spreadsheet, an XML file or even hard-coded data within the program.

## What are the Data Sources supported by The Linux Foundation?

The Linux Foundation supports various data sources string from source control systems to social media platforms to collect and visualize project's data. For details, see [Supported Data Sources](supported-data-sources.md).

## Who can see LFX Insights reports?

Anyone can see reports for projects that are on LFX platform. However, only project maintainers can see information related to affiliation management, and email ids of contributors.

## How does LFX Insights help?

It helps open source project maintainers monitor their project activity, total and individual contribution towards the project, active contributor lists, any unaffiliated contributors, and so on. This helps maintainers to solve problems effectively such as coding activity, code review backlog, performance, bottleneck identification, issue resolution, and so on.

## Does LFX Insights automatically create visualization reports?

Yes, if your project is set up on Linux Foundation's SFDC \(Sales Force Dot Com\) database, then LFX Insights automatically collects and visualizes data on graphs, charts, tables, and other customized dashboards.

## How are unaffiliated contributions calculated?

Unaffiliated contributions are not counted under any organization, and are grouped as **Unknown**. LFX highly recommends to affiliate top contributors of your project.

## Is affiliation data linked to one project?

No, affiliation data is linked to profiles, and profiles are visible across all the projects that they are part of. So, affiliation data for profiles are also visible across projects that they are part of.

## How are contributions calculated?

Insight calculates contribution data based on commit hash. So, if a pull request or changeset is submitted to two different branches with the same commit hash identification number, Insight counts it as a single contribution, eliminating duplication of data.

