# Source Control

Source Control allows you to track and manage updates to your code. It gives you the control to manage the right version of the code. PCC allows your to setup Source Control to your projects.

For compliance reasons, the Linux Foundation platform needs to have access to each GitHub organization you use to host your code. Your governance body and authorized community members will still be responsible and accountable for day-to-day administration of repositories, teams, and users, unless covered by a specific managed-services-agreement with the Linux Foundation.

You can setup the following Source Controls tools to your projects:

* GitHub
* GitLab

## Setting up GitHub <a href="setting-up-github" id="setting-up-github"></a>

You can use GitHub as a source control tool to manage your project.

To setup the GitHub account to your project, perform the following steps:

1.Login into PCC.

2\. Search for the required project. The Project dashboard appears. Click **Source Control **from the **IT SERVICES STATUS **tab.

{% hint style="info" %}
You can also navigate to Source Control from the Vertical Sidebar navigation menu. Click **IT Services** and then select **Source Control**.
{% endhint %}

3.The Source Control page appears. Click **GitHub** and click the![](https://firebasestorage.googleapis.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-MEMVgDuxi7j4ZpeENUY%2F-MM6s2eHhjQ_tQZBLg-r%2F-MM6sWbUBHCbO-u3210L%2FIcon.png?alt=media\&token=5797d8be-df9f-4f97-bb25-6c699e9d6253) icon available in front of **Connect**.

![GitHub](https://gblobscdn.gitbook.com/assets%2F-MEMVgDuxi7j4ZpeENUY%2F-MMBvrEsjsliBZECYf7t%2F-MMByCcDTjZ9B5Zxy5DQ%2FConnect.png?alt=media\&token=0891165d-b8cb-48a3-9253-6880ae5511dd)

4.The Connect GitHub Organization dialog box appears. Enter the **Organization Name** and click **Connect**.

{% hint style="info" %}
Make sure to enter a valid GitHub organization name. 
{% endhint %}

{% hint style="info" %}
* For more information on how to create an organization, refer [Create an Organization](https://docs.github.com/en/github/setting-up-and-managing-organizations-and-teams/creating-a-new-organization-from-scratch).
* For more information on how to transfer a repository, refer [Transfer a Repository](https://docs.github.com/en/github/administering-a-repository/transferring-a-repository).
{% endhint %}

5.Once the connection is setup, you can see the status of GitHub project and its repositories.

![GitHub Status](https://gblobscdn.gitbook.com/assets%2F-MEMVgDuxi7j4ZpeENUY%2F-MMBvrEsjsliBZECYf7t%2F-MMBzrTuxMl6EmxWkMKU%2FStatus.png?alt=media\&token=0e6568b7-142b-4b7b-b899-50119dd69a8f)

{% hint style="danger" %}
If the Organization name is changed in the GitHub, you need to connect the renamed organization again. The renamed organization wont be automatically connected even though the organization with the old name was connected. 
{% endhint %}

## Invite users to your Organization  <a href="invite-users-to-organization" id="invite-users-to-organization"></a>

Your project should have its own GitHub organization, separate from your company's GitHub organization, and which is not shared with other, non-Linux-Foundation projects. If you need to, create a new GitHub organization for this project, and have a user who is an owner in both organizations transfer each project repository to this organization.

Then, invite the user “thelinuxfoundation” as an owner at the organization level (not per repository) to the GitHub organization, and connect them in Project Control Center.

{% hint style="info" %}
* For more information on how to invite users to join organization, refer [Invite Users to an Organization](https://docs.github.com/en/github/setting-up-and-managing-organizations-and-teams/inviting-users-to-join-your-organization).
* For more information on how to transfer a repository, refer [Transfer a Repository](https://docs.github.com/en/github/administering-a-repository/transferring-a-repository).
{% endhint %}

## Deleting a GitHub Organization  <a href="deleting-github-organization" id="deleting-github-organization"></a>

You can delete the added GitHub organization from the PCC. 

To delete the GitHub organization that is added in the PCC, perform the following:

1.Login into PCC. 

2.Click the **Source Control**. 

3.Under **GitHub**, click on the required GitHub organization that you want to delete. 

4.Click the ![](broken-reference)  icon and click **Disassociate**. 

5.The Confirm Disassociation dialog box appears, click **Delete **to delete the GitHub Organization. 

## Setting up GitLab

You can use GitLab as a source control tool to manage your project.

To setup the GitLab account to your project, perform the following steps:

1.Login into PCC.

2\. Search for the required project. The Project dashboard appears. Click **Source Control **from the **IT SERVICES STATUS **tab.

{% hint style="info" %}
You can also navigate to Source Control from the Vertical Sidebar navigation menu. Click **IT Services** and then select **Source Control**.
{% endhint %}

3.The Source Control page appears. Click **GitLab** and click the![](https://firebasestorage.googleapis.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-MEMVgDuxi7j4ZpeENUY%2F-MM6s2eHhjQ_tQZBLg-r%2F-MM6sWbUBHCbO-u3210L%2FIcon.png?alt=media\&token=5797d8be-df9f-4f97-bb25-6c699e9d6253) icon available in front of **Connect**.

![GitLab](https://gblobscdn.gitbook.com/assets%2F-MEMVgDuxi7j4ZpeENUY%2F-MMBzyPEWoumUhMMbi3v%2F-MMC0CxSwdrHEJorgf-y%2FGitlab.png?alt=media\&token=4cec0390-4573-4d2e-9c84-4aa8e5e4b99a)

4.The Connect GitLab Group dialog box appears. Enter the **Group Name** and click **Connect**.

5.Once the connection is setup, you can see the status of GitLab project and its repositories.

![GitLab Status](https://gblobscdn.gitbook.com/assets%2F-MEMVgDuxi7j4ZpeENUY%2F-MMBzyPEWoumUhMMbi3v%2F-MMC1IC5alHrzKrM8PIg%2FLab_Status.png?alt=media\&token=2b0ce2d2-76bf-4cfe-a1bb-1c3f0372d003)

##  <a href="setting-up-gerrit" id="setting-up-gerrit"></a>

​

​

​
