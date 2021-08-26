# View Connection Status of Git Organizations and Repositories

After you [add a GitHub](./#add-github-organization) or [Gerrit organization](./#add-gerrit-organization), the organizations are displayed with different colors referring to their connection statuses. The following is an example:

![GitHub Organization Connection Status](../../../.gitbook/assets/github-organization-connection-status.png)

* ![](../../../.gitbook/assets/connected-green-color.png) indicates full connection: all the repositories of the organization are connected.
* ![](../../../.gitbook/assets/orange-partial-connection.png) indicates partial connection: some repositories of the organization are connected.
* ![](../../../.gitbook/assets/grey-no-connection.png) indicates no connection: the organization is added, but is not [configured](enforce-or-remove-cla.md#configure-github-repositories) for EasyCLA. 
* ![](../../../.gitbook/assets/red-connection-failure.png) indicates connection failure: for a connected organization, either the EasyCLA configuration is uninstalled or the organization is deleted from GitHub.

A repository with a cross mark next to it indicates connection failure. It means the repository was EasyCLA enabled, but it is deleted from the organization.

