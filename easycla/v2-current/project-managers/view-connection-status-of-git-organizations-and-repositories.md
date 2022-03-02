# View Connection Status of Git Organizations and Repositories

After you add a GitHub or Gerrit organization or GitLab group, the organizations or groups are displayed with different colors referring to their connection statuses. The following is an example:

![Git Organization Connection Status](<../../../.gitbook/assets/github organization connection status.png>)

* ​![](<../../../.gitbook/assets/connected green color.png>) indicates _full connection_: all the repositories of the organization are connected.
* ​![](<../../../.gitbook/assets/orange partial connection.png>) indicates _partial connection_: some repositories of the organization are connected.
* ​![](<../../../.gitbook/assets/grey no connection.png>) indicates _no connection_: the organization is added, but its repositories are not [EasyCLA enforced](enforce-or-remove-cla-mechanism.md).
* ​![](<../../../.gitbook/assets/red connection failure.png>)indicates _connection failure_: for a connected organization, either the EasyCLA configuration is uninstalled or the organization is deleted from GitHub/Gerrit/GitLab.

A repository with a cross mark next to it indicates connection failure. It means the repository was EasyCLA enabled, but it is deleted from the organization.
