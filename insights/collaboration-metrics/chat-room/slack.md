# Slack

{% hint style="info" %}
By default, Severe Activity and Bot Commits are filtered, however, you can include these filter values by navigating to the filter section of dashboard. For details, see [Add and Manage Data Filters](../../filter-data/add-and-manage-data-filters.md).
{% endhint %}

### Issues when LFX Insights cannot fetch Slack data:

{% hint style="warning" %}
**Important:**

Following are the issues when LFX Insights cannot fetch Slack data and the resolutions for them:

* **Issue:** If the slack application named `insights-bot-service` is uninstalled from the workspace.\
  **Resolution:** Install `insights-bot-service bot` on the workspace. If the tokens are changed, provide tokens to the LFX Insights team.
* **Issue:** If the events for the `insights-bot-service` slack application are turned off.\
  **Resolution:** Turn on the events, notify the LFX Insights team to ensure that the events are received and processed for the project.
* **Issue:** If the `insights-bot-service` bot is removed from the channel.\
  **Resolution:** Add the bot back to the channel.
{% endhint %}

The slack dashboard is available from the **Chat Room** drop-down list, and represents a set of metrics that shows information about the slack communication channel.

## Overview

Overview shows high-level information about how developers use Slack. For example, you can see the channels in which people send the most messages. You can sort channels by the number of messages, participants, replies, and other values.

**Filter** lets you filter the dashboard data by author name and organization name. Select values from the respective drop-down lists, and click **Apply changes** to filter the dashboard as per selection.

**Summary** shows the total number of Channels, Messages, Participants, Replies, Reactions, and Attachments of the project over time.

**Trending Reactions** shows a doughnut chart that represents the total number of reactions in the project per reaction value. Mouse over a color in the chart to see the total number of reactions for each reaction, and their percentage of the project's total reactions.

**Top Trending Terms** shows a term cloud of the top 20 terms that participants used. Click a **term** to show the corresponding data in the dashboard.

**Messages by Time Zone** shows a bar graph with a count of messages per Coordinated Universal Time (UTC) time zone. Mouse over a color in the graph to see the total number of messages for each time zone.

**Messages** shows a bar graph that represents the number of messages per day over time. Mouse over a color in the graph to see the total number of messages for a date.

**Messages By Organization** shows a doughnut chart that represents the total number of messages in the project per organization. Mouse over a color in the chart to see the total number of messages for each organization, and their percentage of the project's total messages.

**Top Participating Organizations** shows a table that lets you sort values by organization name, number of channels, messages, and participants of an organization.

**Top Participants** shows a table that lets you sort values by Participants, Avatar, Messages, Channels, date and time for first and last comments.

**Active Participants** shows a bar graph that represents the number of participants per day over time. Mouse over a color in the graph to see the total number of participants for a date.

**Channels** shows a table that lets you sort values by Channel, Topic, Purpose, Messages, Participants, Members, Replies, General, Starred, and Archived.
