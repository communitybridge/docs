# Dev Analytics Troubleshooting

Troubleshooting helps you solve problematic symptoms in your Dev Analytics implementation.

## Dev Analytics Data Scan Problems <a id="DevAnalyticsTroubleshooting-DevAnalyticsDataScanProblems"></a>

### Symptom: <a id="DevAnalyticsTroubleshooting-Symptom:"></a>

Dev Analytics scans do not occur automatically and/or general errors occur.

### Solution: <a id="DevAnalyticsTroubleshooting-Solution:"></a>

Do _not_ perform any of the following repository actions, which can impact Dev Analytics data scans negatively.

* **Delete** a repository—may cause general errors. The minimum impact is that the repository will no longer be scanned.
* **Create** a repository creation—the repository is not scanned automatically.
* **Update** a public repository to be a private repository—may cause general errors. The minimum impact is that the repository will no longer be scanned.
* **Update** a private repository to be public repository—the repository is not scanned automatically.

To achieve any of those actions, do these steps:

1. Go to the [Linux Foundation Help Center](https://jira.linuxfoundation.org/servicedesk/customer/portal/4).
2. Select **Get Help with CommunityBridge Dev Analytics**.
3. Complete the ticket form fields requesting the repository change that you want and click **Create**.

