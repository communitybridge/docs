# Supported Data Sources

Data sources are the collaboration tools or the remote servers that are used to drive the development of a project. LFX Insights accesses such data sources, collects data for a project, segregates them to different sections, such as source control for code related data, issue management for issues statuses, documentation for confluence and wiki pages, CI/CD for Jenkins, and so on.

* [Currently Supported](supported-data-sources.md#currently-supported-data-sources)
* [In Progress](supported-data-sources.md#in-progress)
* [Coming Soon](supported-data-sources.md#coming-soon)

## Currently Supported Data Sources

Insights supports the following data sources based on their categories:

* [Source Control Systems](supported-data-sources.md#source-control-systems)
* [Issue Tracking Systems](supported-data-sources.md#issue-tracking-systems)
* [Build Systems](supported-data-sources.md#build-systems)
* [Email Systems](supported-data-sources.md#email-systems)
* [Chat Room](supported-data-sources.md#chat-room)
* [Documentation](supported-data-sources.md#documentation)
* [Social Media](supported-data-sources.md#social-media-1)
* [Earned Media](supported-data-sources.md#earned-media)
* [Registry](supported-data-sources.md#registry)

#### Source Control Systems

Insights supports Git, GitHub, and Gerrit for tracking and visualizing project's source code analytics. For details, see [Source Control](technical-metrics/source-control/).

#### Issue Tracking Systems

Following are the various issue tracking system data sources currently supported by Insights:

* [GitHub](technical-metrics/project-management/github-issues.md)
* [Bugzilla](technical-metrics/project-management/bugzilla.md)
* [Jira](technical-metrics/project-management/jira.md)

#### Build Systems

Insights supports [Jenkins](technical-metrics/ci-cd/jenkins.md) and [CircleCI](technical-metrics/ci-cd/circle-ci.md) as two of the popular build system data sources.

#### Email Systems

Insights supports [Pipermail](collaboration-metrics/mailing-list/pipermail.md), [Groups.io](collaboration-metrics/mailing-list/groupsio.md), and [Google Groups](collaboration-metrics/mailing-list/google-groups.md) as email systems to visualize project related communication activities.

#### Chat Room

Insights supports chat room platforms, such as [Slack](collaboration-metrics/chat-room/slack.md) and [Rocket Chat](collaboration-metrics/chat-room/rocket-chat.md) to analyze the project related communication activities.

#### Documentation

Insights supports Confluence for tracking and visualizing project's documentation. For details, see [Confluence](collaboration-metrics/documentation/confluence.md).

#### Social Media

Insights supports [Twitter](social-media-metrics.md#overview) as social media platform to visualize project's **** high-level insights from the project's twitter account.

#### &#x20;Earned Media

Insights supports _Cision_ to track and analyze the health of project's audience engagement, such as how frequently project is talked about in social media channels, how many times the project and the project relevant content is searched, and so on. For details, see [Earned Media](earned-media/).

#### Registry

Insights supports [DockerHub](technical-metrics/registry/dockerhub.md) to track container images.&#x20;

## In Progress

The Linux Foundation is developing Insights tool to support the following data sources in the next release:

#### Social Media

The Linux Foundation is releasing soon the support for social media platforms, such as Facebook and LinkedIn.

## Coming Soon

The Linux Foundation is working towards supporting the following data sources very soon:

#### Build Systems

The Linux Foundation is releasing soon the support for some more popular build system data sources, such as **Travis CI (**Continuous Integration**)**, **Gitlab CI**, **GitHub Actions**, to name a few.

#### Chat Room

The Linux Foundation is developing Insights tool to support **GitHub Team Discussions**.
