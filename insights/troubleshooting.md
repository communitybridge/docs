# Troubleshooting

Troubleshooting helps you solve problematic symptoms in your INSIGHTS implementation.

## Insights Data Scan Problems <a id="DevAnalyticsTroubleshooting-DevAnalyticsDataScanProblems"></a>

### Symptom: <a id="DevAnalyticsTroubleshooting-Symptom:"></a>

Insights scans do not occur automatically and/or general errors occur.

### Solution: <a id="DevAnalyticsTroubleshooting-Solution:"></a>

1. Sign in to the [Linux Foundation Help Center](https://jira.linuxfoundation.org/servicedesk/customer/portal/4).
2. Select LFX Insights, and click a relevant option for your issue.
3. Complete the ticket form fields requesting the repository change that you want and click **Create**.

{% hint style="danger" %}
**Important:** Do not perform any of the following repository actions, which can impact Insights data scans negatively.
{% endhint %}

* **Delete** a repository—may cause general errors. The minimum impact is that the repository will no longer be scanned.
* **Create** a repository creation—the repository is not scanned automatically.
* **Update** a public repository to be a private repository—may cause general errors. The minimum impact is that the repository will no longer be scanned.
* **Update** a private repository to be public repository—the repository is not scanned automatically.

