# Troubleshooting

Troubleshooting helps you solve problematic symptoms in your INSIGHTS implementation.

## Insights Data Scan Problems <a href="#devanalyticstroubleshooting-devanalyticsdatascanproblems" id="devanalyticstroubleshooting-devanalyticsdatascanproblems"></a>

### Issue: <a href="#devanalyticstroubleshooting-symptom" id="devanalyticstroubleshooting-symptom"></a>

Insights scans do not occur automatically and/or general errors occur.

### Solution: <a href="#devanalyticstroubleshooting-solution" id="devanalyticstroubleshooting-solution"></a>

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

### Slack Data Fetch Issue:

**Issue 1 :** If the slack application named `insights-bot-service` is uninstalled from the workspace.\
**Resolution 1 :** Install `insights-bot-service bot` on the workspace. If the tokens are changed, provide tokens to the LFX Insights team.

**Issue 2:** If the events for the `insights-bot-service` slack application are turned off.\
**Resolution 2:** Turn on the events, notify the LFX Insights team to ensure that the events are received and processed for the project.

**Issue 3:** If the `insights-bot-service` bot is removed from the channel.\
**Resolution 3:** Add the bot back to the channel.
