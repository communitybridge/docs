# Data Affiliation

Affiliation is a close association or connection to an organization, company, and so on. An example of affiliation is being a contributor to a community organization. Or, a contributor could belong to two or more companies that are related through common ownership but are treated as one. In this case, a single contributor might have multiple identities such as two different company emails. Data affiliation connects or associates these identities.

Dev Analytics uses _Affiliation Management_ to handle data affiliations as follows:

## Data Sources and Tools <a id="DataAffiliation-DataSourcesandTools"></a>

Open source projects rely on a variety of data sources and tools to support and coordinate development activities, for example:

* Git repositories or GitHub projects
* Issue trackers such as Jira or Bugzilla
* Messaging tools such as Slack or mailing lists
* Build tools such as Jenkins

Project contributors can access the tools using different identities, for example: email, username. In Dev Analytics, each contributor has a _profile_. A profile has personal details and can include multiple identities and organization affiliations. 

## Identities <a id="DataAffiliation-Identities"></a>

An identity can be a combination of email address, full name, or username. Examples of identities are "commit signatures" \(that is, full names and email addresses\) of committers and authors in Git repositories. However, the identities used by the same profile \(contributor\) may diﬀer across the tools used in the project. A project profile might use more than one identity for the same tool \(for example, in version control systems and mailing lists\). In addition, an identity can be shared by project profiles, such as during pair programming \(that is, the same email address for both profiles\).

Dev Analytics manages identities across sources allowing identities to be affiliated, for example, a company and organization affiliation. In a database, identity and affiliation data is stored across domains. Dev Analytics evaluates individual contributions to open source projects by tracking the unique identities of profiles and their related information such as country and organization. Projects then produce meaningful statistics about their communities, because individual contributions are not underestimated.

## Analysis <a id="DataAffiliation-Analysis"></a>

An analysis of the enriched information \(identities, affiliation, bot status, and so on\) allows for a correct count of developers and others in software development. Dev Analytics retrieves the data, stores it in databases, analyzes it, and produces dashboards for visualizing the resulting information. The results let you measure any project as a whole using aggregated data of more than one type.

