# Troubleshooting

Troubleshooting helps you solve problematic symptoms in your INSIGHTS implementation.

### Insights Data Scan Problems <a href="#devanalyticstroubleshooting-devanalyticsdatascanproblems" id="devanalyticstroubleshooting-devanalyticsdatascanproblems"></a>

#### Issue: <a href="#devanalyticstroubleshooting-symptom" id="devanalyticstroubleshooting-symptom"></a>

Insights scans do not occur automatically and/or general errors occur.

#### Solution: <a href="#devanalyticstroubleshooting-solution" id="devanalyticstroubleshooting-solution"></a>

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

If you notice that the slack data for your project is not getting updated or reporting stale data, it might be due to the following reasons:

**Issue 1 :** If the slack application named `insights-bot-service` is uninstalled from the workspace.\
**Resolution 1 :** Contact your project's slack-workspace administrator to ensure that the app `insights-bot-service` is installed. If not then, search for the app on the slack market place and get it installed. Once the app is installed, please contact the LFX support desk so that the new token can be updated at our end as well.

**Issue 2:** If the events for the `insights-bot-service` slack application are turned off.\
**Resolution 2:** Contact the slack workspace administrator to _turn on_ the events reported by the `insights-bot-service` as that is the only way the data is fetched into LFX Insights platform.

**Issue 3:** If the `insights-bot-service` bot is removed from the channel.\
**Resolution 3:** Workspace administrators must add the bot back to the channel.
