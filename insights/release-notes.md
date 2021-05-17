# Release Notes

## May 2021

The LFX Insights, May 2021 Release delivers support for new data sources and metrics— GitHub Reviews, Changeset Reviews metrics as source control systems, Circle CI as build system, and Google Groups as Email system to visualize project related communication activities. Gerrit Changeset Approval and GitHub PR Efficiency dashboards are enhanced for better clarity on data.

* [Added Features](release-notes.md#added-features)

## Added Features

Following are the newly added features for May 2021 release:

* [GitHub – Reviews Dashboard & Efficiency Metrics](release-notes.md#github-reviews-dashboard-and-efficiency-metrics)
* [Google Groups and Circle CI](release-notes.md#google-groups-and-circleci-support)
* Gerrit Changesets Reviews and Approval Dashboards

### **GitHub – Reviews Dashboard & Efficiency Metrics**

New GitHub Reviews Dashboard and an improved GitHub Efficiency Dashboard provide more clarity around pull request merge times.

Following key metrics are added as new visualizations:

* **Average Time to First Review**: The average time it takes for the first review to be completed on a pull request. Community maintainers can use this metric to track reviewer activity and help avoid burnout.
* **Time to First Approve**: The time it takes to get the first approval on a pull request. Spikes in this metric could indicate that submitted PRs aren’t adhering to the contributor guidelines established by the project.
* **Pull Requests Merged Without Approvals:** The number of pull requests merged without passing through a review and approval process. While it’s common practice to only merge code that’s passed through the PR review process, there can be exceptions. This metric gives maintainers visibility into these instances so you can avoid surprises.
* **Improved GitHub Efficiency Dashboard:** We’ve completely redesigned the GitHub Efficiency Dashboard to help project maintainers set goals around PR merge times, a helpful metric in understanding and optimizing project efficiency. The dashboard now includes new metrics like Median Time to Merge, 95th Percentile of Time to Merge, Submitters, Organizations, Total PRs Merged, and more. The new Time to Merge trends-over-time table will be especially useful in tracking healthy merge times.

### **Google Groups & CircleCI Support**

**Google Groups:** This data source addition expands Insights email coverage to include Google Groups mailing lists, which already supports Groups.io and Pipermail. In addition to the dedicated Overview Dashboard, Google Groups is also integrated with the Trends Dashboard. This provides richer context around what the community is talking about. Project community managers can use metrics like “Daily Active Users”, “Emails by Organization”, and even “Top Trending Topics” to better engage and acknowledge their community members.

**Circle CI Dashboards:** LFX Insights supports CircleCI, providing various builds related-metrics right on the Insights dashboard for your project, helping you monitor your project’s build pipeline and improve workflow efficiency.

Following key metrics are added as new visualizations:

* **Jobs By Status:** Detailed analysis on jobs by their status, paired against the repositories that triggered them.
* **Workflow Duration Trend:** Workflow completion time trend analysis. Project maintainers can use this metric to help identify the effects of major code updates on the build pipeline, or to track against a goal of reducing build duration time.

{% hint style="info" %}
**Note:** You can view some visualizations on different data sources, such as Gerrit Changesets' approval and reviews dashboards are renamed, changed, or completely enhanced for better user understanding and more clarity in data retrieval. Consider the current visualizations as the most recent and updated.
{% endhint %}



