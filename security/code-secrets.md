# Code Secrets

LFX Security has collaborated with BluBracket to scan for valuable private information and non-inclusive words in open source code, we call this information “code secrets”. Unearthing code secrets has made the open source projects more secure and the code security is enhanced to a great extent by detecting and monitoring the risks thus improving the code.

In order to scan for code secrets, projects need to be onboarded to the BluBracket platform.

{% hint style="info" %}
LFX team will share the link with the project maintainer to install the LFX Security GitHub App to onboard the project. The project maintainer should install the LFX Security GitHub App.
{% endhint %}

## Installing LFX Security GitHub App <a id="installing-lfx-security-github-app"></a>

The project maintainer of the project will receive the LFx Security GitHub App link from the LFX team. The project maintainer should install the LFx Security GitHub App inorder to onboard the project.

To install the LFX Security GitHub App, perform the following steps:

1.Click the link that is shared in the email which is received from the LFX team.

2.You need to sign with the login credentials of your GitHub account. Enter the **Username**, **Password** and click **Sign in**.

![GitHub Login](https://gblobscdn.gitbook.com/assets%2F-MCG-Km6_RcGyUVKsLIx%2F-Mb4y1jbC3ddQdur3uGL%2F-Mb51hW0ZQ6XFT9VJdVZ%2FLOgin.png?alt=media&token=0565eb98-f0d2-41f7-82c9-071eb74a0a03)

3.List of GitHub organization associated with the login account are listed and displayed. Select the required organization.

![GitHub Organizations](https://gblobscdn.gitbook.com/assets%2F-MCG-Km6_RcGyUVKsLIx%2F-Mb53GByRd6PrIF_FSoA%2F-Mb54Utn5zoc-1SLci6l%2FList.png?alt=media&token=c7c9dde6-34d3-4b34-928b-200b0bf9e24c)

4.The Install & Authorize LFx Security GitHub App page appears. This page provides the following information:

* Information on the permission requested for the selected repositories. The LFX Security requests the following permissions:
  * **Read** access to administer, code, check commit status, lookup members, and other metadata.
  * **Read** and **write** access to organization hooks, pull requests, and repository hooks.
  *  Installing and authorizing LFX Security GitHub App immediately grants these permissions on your account:
  * **Read** access to emails
* Access to the repositories. You can either provide access to all the repositories or the for the selected repositories in the GitHub organization.

Click **Install & Authorize** to install the LFX Security GitHub App.

![Install Permissions](https://gblobscdn.gitbook.com/assets%2F-MCG-Km6_RcGyUVKsLIx%2F-Mb54_KofyumI-UB7Wl7%2F-Mb56smIJpdGbNLb5xJ4%2FPer1.png?alt=media&token=dd6bda9b-2dc3-4697-b992-7b4c814e8e0f)

5.The LFX Security Service GitHub app is installed successfully. You can see the installation success message.

![Installation Complete](https://gblobscdn.gitbook.com/assets%2F-MCG-Km6_RcGyUVKsLIx%2F-Mb54_KofyumI-UB7Wl7%2F-Mb57cBro_UemLOIw-T9%2FSuccess.png?alt=media&token=852f8d1c-1abf-40c3-9a87-cfd27b4772ee)

{% hint style="info" %}
You will also receive an email after successful installation of the LFX Security GitHub App.
{% endhint %}

## Scanning of Projects for Code Secrets  <a id="scanning-of-projects-for-code-secrets"></a>

After onboarding the projects, scanning of projects for code secrets is carried out by LFX Security platform. The LFX Security platform will scan the repositories and detect the code secrets and notifications for the selected organization or repository.

### Project Code Secrets  <a id="project-code-secrets"></a>

LFX Security will scan the repositories and organizations for code secrets such as passwords, JWT tokens, AWS access keys, terraform state file and non enterprise webhooks.

To access code secrets for a project or repository, perform the following steps:

1.Login to [LFX Security](https://security.lfx.linuxfoundation.org/) and select the required project and click **View Issues**.

![View Issues](https://gblobscdn.gitbook.com/assets%2F-MCG-Km6_RcGyUVKsLIx%2F-Mb5RSb-A-4jnWYaImnC%2F-Mb5SZp_Pi0WtRtUra38%2FView_Issues.png?alt=media&token=76736762-c185-4720-9ed5-ff7913ca8f2e)

2.Select **Code Secrets** from the top menu. The Code secrets are listed under the **CODE SECRETS REVEALED** tab.

![Code Secrets](https://gblobscdn.gitbook.com/assets%2F-MCG-Km6_RcGyUVKsLIx%2F-Mb5UDjbdgqhSQUB88Wv%2F-Mb5Uewb73gx4IUWy8ws%2FCS1.png?alt=media&token=4e9ea699-845d-445a-b795-3903b0d16b07)

3. The list provides the following details related to the code secrets:

* **Time** - Date and time when the code secret is detected
* **Description** - Type of code secret that is been detected
* **Repository** - Name of the repository which contains the code from where the code secret has been detected
* **Developer** - Name of the developer who has checked in the code in the repository
* ​![](https://firebasestorage.googleapis.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-MCG-Km6_RcGyUVKsLIx%2F-Mb5UzinhL1rphvrpQbh%2F-Mb5YXoFUUItEdR62hMl%2FIcon.png?alt=media&token=6afd855c-0fe9-4012-871c-adfec0b3ebe5) - Icon to minimize and maximize the code secret details.

### Code Secret Details  <a id="code-secret-details"></a>

The Code Secrets Revealed tab provides you the list of code secrets associated with the project or repository. You can check the details of the listed code secret with the help of the ![](https://firebasestorage.googleapis.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-MCG-Km6_RcGyUVKsLIx%2F-Mb5okTX9WyxMvmvw4OX%2F-Mb5rA5dKAUZkHuKrLNG%2FIcon.png?alt=media&token=6e24472a-da82-432c-9509-5ba3851582df) icon.

To check the details related to the listed code secrets, perform the following steps:

1.Select **Code Secrets** from the top menu. The Code secrets are listed under the **CODE SECRETS REVEALED** tab.

2. Click the ![](https://firebasestorage.googleapis.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-MCG-Km6_RcGyUVKsLIx%2F-Mb5okTX9WyxMvmvw4OX%2F-Mb5rA5dKAUZkHuKrLNG%2FIcon.png?alt=media&token=6e24472a-da82-432c-9509-5ba3851582df) icon listed in front of the code secret.

![Code Secret](https://gblobscdn.gitbook.com/assets%2F-MCG-Km6_RcGyUVKsLIx%2F-Mb5rPTGPlu3Goqb9UH6%2F-Mb5sIyQbygnTcIfhYss%2FCS2.png?alt=media&token=5ba909ea-5b55-4ea8-8e48-7598097d4373)

3. The code secret details box appears with a list of all the details related to the code secret. The following details are available for you to check out:

* File Details
  * Name - A hyperlink that will navigate you to the exact line of the code which is a potential threat or vulnerability.
  * Private Key - The code secret that was identified in the file. The value is masked such that it doesn’t show the exposed code secret value. To see the code secret, click on the filename or the commit ID.
  * Secret Hash - The hash ID value for the code secret.
* Repository Details
  * Organization - Name of the GitHub organization.
  * Provider - Name of the provider where the code is hosted.
  * Description - A short info on the organization.
* Commit Details
  * Commit ID - A hyperlink that will navigate you to the ID who has checked in the code.
  * Time - Date and time when the code is checked in.
  * Committed By - Name of the developer who has checked in the code.
  * Message - This is the message associated with the git commit when the code secret was introduced into the repository. This may provide a hint as to why the code secret was added or which bug fix or feature enhancement is associated with the change.

![Code Secret Details](https://gblobscdn.gitbook.com/assets%2F-MCG-Km6_RcGyUVKsLIx%2F-Mb5uHxLtTVlsOugmby3%2F-Mb5uNjtPUO9n2RhZf4I%2FCS4.png?alt=media&token=af98e5b5-616e-4fdb-a9be-f7a51e7a8826)

### Actions Performed on the Code Secrets  <a id="actions-performed-on-the-code-secrets"></a>

Project Maintainers can perform various actions on the code secrets. These actions will help to mitigate the vulnerabilities for the code and the project. The ![](https://firebasestorage.googleapis.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-MCG-Km6_RcGyUVKsLIx%2F-Mb5UzinhL1rphvrpQbh%2F-Mb5YXoFUUItEdR62hMl%2FIcon.png?alt=media&token=6afd855c-0fe9-4012-871c-adfec0b3ebe5) icon provides you all the required details related to the code secrets, based on the details available, you can perform certain actions on these code secrets.

To perform actions on the code secrets, perform the following steps:

1.Select **Code Secrets** from the top menu. The Code secrets are listed under the **CODE SECRETS REVEALED** tab.

2. Click the ![](https://firebasestorage.googleapis.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-MCG-Km6_RcGyUVKsLIx%2F-Mb5okTX9WyxMvmvw4OX%2F-Mb5rA5dKAUZkHuKrLNG%2FIcon.png?alt=media&token=6e24472a-da82-432c-9509-5ba3851582df) icon listed in front of the code secret.

![Code Secret](https://gblobscdn.gitbook.com/assets%2F-MCG-Km6_RcGyUVKsLIx%2F-Mb5rPTGPlu3Goqb9UH6%2F-Mb5sIyQbygnTcIfhYss%2FCS2.png?alt=media&token=5ba909ea-5b55-4ea8-8e48-7598097d4373)

3. The code secret details box appears with a list of all the details related to the code secret. Click **Actions** and select the required action to be performed for the listed code secret.

![Code Secrets Actions](https://gblobscdn.gitbook.com/assets%2F-MCG-Km6_RcGyUVKsLIx%2F-Mb5v70j_f9EW2-v4Tvp%2F-Mb6SM_LnS08KriLK0TJ%2FCS5.png?alt=media&token=fbf5cd8b-c63d-416f-818d-eb2b189cf6c0)

4.Under **Actions** drop-down, you can see the following actions:

* Resolve - Use this option to resolve the code secret
* Ignore - Use this option to ignore the code secret
* False Positive - Use this option if you think the mentioned code secret is not a code secret
* Dismiss - Use this option to dismiss the code secret

### Categorization of Code Secrets  <a id="categorization-of-code-secrets"></a>

LFX Security allows you to categorize the code secrets using various parameters. Following are few of the categories available to filter or categorize code secrets:

* Code Secret State
* Alert Type
* Repository
* Developer

#### Filter of Code Secrets through Code Secret Type  <a id="filter-of-code-secrets-through-code-secret-type"></a>

You can filter the code secrets based on the code secret type. Following are the different type of code secret types:

* Dismissed
* False Positive
* Active

![Code Secret Type Filter](https://gblobscdn.gitbook.com/assets%2F-MCG-Km6_RcGyUVKsLIx%2F-Mb6_Ng3_nEixegWwCQM%2F-Mb7O8YK7lKGWeoBTtbC%2FCS%20Type.png?alt=media&token=bc46ef8b-8bac-4e0d-8783-3fd38d93ee7b)

#### Filter of Code Secrets through Alert Type  <a id="filter-of-code-secrets-through-alert-type"></a>

You can filter the code secrets based on the alert type. Following are the different type of alert types:

* Repo Requires Insufficient Number of Reviewers
* Repo Scan Match
* User Edited In Repo
* Web Hook Url Non Enterprise

![Alert Type Filter](https://gblobscdn.gitbook.com/assets%2F-MCG-Km6_RcGyUVKsLIx%2F-Mb6_Ng3_nEixegWwCQM%2F-Mb7PjmRn_l00eXVUB-3%2FAlert_type.png?alt=media&token=ef674cbf-c70a-419c-b2fe-6ff3bc1d8390)

#### Filter of Code Secrets through Repository  <a id="filter-of-code-secrets-through-repository"></a>

You can filter the code secrets based on different repositories in the GitHub organization.

![Repository Filter](https://gblobscdn.gitbook.com/assets%2F-MCG-Km6_RcGyUVKsLIx%2F-Mb7PonEG0_f8xYsaIrU%2F-Mb7RD1MUoLdIq4xIIco%2FRepo.png?alt=media&token=e00ac199-20cb-4bf5-adf4-3361236a38e4)

#### Filter of Code Secrets through Developers  <a id="filter-of-code-secrets-through-developers"></a>

You can filter the code secrets based on individual developers who have checked in their code in the repositories.

![Developer Filter](https://gblobscdn.gitbook.com/assets%2F-MCG-Km6_RcGyUVKsLIx%2F-Mb7RL05v_Ra7PfCckMe%2F-Mb7S9_7d0EuvJTHOa8n%2FDevelopers.png?alt=media&token=4d6170f5-d16c-4e7d-9bfd-8dc235b82d91)

{% hint style="info" %}
You can use the **Reset** option to clear all the filters.
{% endhint %}

## Scanning of Projects for Notifications  <a id="scanning-of-projects-for-notifications"></a>

Code secrets will provide generic notifications related to the repositories. These notifications are generic notifications which are not fatal even if ignored. These notifications will provide information to the project maintainers on their projects and repositories.

Few of the notifications provided by code secrets are:

* Web hook URL non enterprise
* Repo forked
* Users edited in the repo

### Code Secret Notifications  <a id="code-secret-notifications"></a>

LFX Security will scan the repositories and organizations and provide various notifications related to them.

To access code secrets notifications for a project or repository, perform the following steps:

1.Login to [LFX Security](https://security.lfx.linuxfoundation.org/) and select the required project and click **View Issues**.

![View Issues](https://gblobscdn.gitbook.com/assets%2F-MCG-Km6_RcGyUVKsLIx%2F-Mb5RSb-A-4jnWYaImnC%2F-Mb5SZp_Pi0WtRtUra38%2FView_Issues.png?alt=media&token=76736762-c185-4720-9ed5-ff7913ca8f2e)

2.Select **Code Secrets** from the top menu. The Code secrets notifications are listed under the **NOTIFICATIONS** tab.

![Code Secret Notifications](https://gblobscdn.gitbook.com/assets%2F-MCG-Km6_RcGyUVKsLIx%2F-MbA5vRw2aO_vOeUKPm-%2F-MbA8vfiZ9RVm4oMS8bV%2FNoti.png?alt=media&token=4ac070a5-b8af-4f09-be31-5f18ab832b50)

3.The list provides the following details related to the code secrets notifications:

* **Time** - Date and time when the code secret notification is detected
* **Description** - Type of code secret notification that is been detected
* **Repository** - Name of the repository which contains the code from where the code secret notification has been detected
* **Developer** - Name of the developer who has checked in the code in the repository
* ​![](https://firebasestorage.googleapis.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-MCG-Km6_RcGyUVKsLIx%2F-Mb5UzinhL1rphvrpQbh%2F-Mb5YXoFUUItEdR62hMl%2FIcon.png?alt=media&token=6afd855c-0fe9-4012-871c-adfec0b3ebe5) - Icon to minimize and maximize the code secret details.

### Code Secret Notification Details  <a id="code-secret-notification-details"></a>

The Notifications tab provides you the list of notifications associated with the project or repository. You can check the details of the listed notification with the help of the ![](https://firebasestorage.googleapis.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-MCG-Km6_RcGyUVKsLIx%2F-Mb5okTX9WyxMvmvw4OX%2F-Mb5rA5dKAUZkHuKrLNG%2FIcon.png?alt=media&token=6e24472a-da82-432c-9509-5ba3851582df) icon.

To check the details related to the listed notification, perform the following steps:

1.Select **Code Secrets** from the top menu. The Code secret notifications are listed under the **NOTIFICATION** tab.

2. Click the ![](https://firebasestorage.googleapis.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-MCG-Km6_RcGyUVKsLIx%2F-Mb5okTX9WyxMvmvw4OX%2F-Mb5rA5dKAUZkHuKrLNG%2FIcon.png?alt=media&token=6e24472a-da82-432c-9509-5ba3851582df) icon listed in front of the notification.

![Notification](https://gblobscdn.gitbook.com/assets%2F-MCG-Km6_RcGyUVKsLIx%2F-MbA91XeaJOiw58ZP2jZ%2F-MbAAQpIZnPcsY5EsSr6%2FNoti2.png?alt=media&token=7628e9d2-9818-4609-8db0-4cf5e357c3d3)

3. The notification details box appears with a list of all the details related to the notification. The following details are available for you to check out:

* Repository - Name of the repository
* Repo URL - URL of the repository
* Source Repo URL - Source URL of the repository
* New file copies count - Number of new files
* New in file copies count - Number of in files
* New out file copies count - Number of out files

![Notifications Details](https://gblobscdn.gitbook.com/assets%2F-MCG-Km6_RcGyUVKsLIx%2F-MbA91XeaJOiw58ZP2jZ%2F-MbABSqBLmiBamRKCT27%2FNoti3.png?alt=media&token=1460cbb2-6f09-4500-aed3-71f7280f01c4)

### Filter of Notifications through Event Type  <a id="filter-of-notifications-through-event-type"></a>

You can filter the notifications based on the event types.

![Event Type Filter](https://gblobscdn.gitbook.com/assets%2F-MCG-Km6_RcGyUVKsLIx%2F-MbABXd2ZJsLWyT0-Wif%2F-MbADkVUnnOwiX2Y5BEJ%2FNoti4.png?alt=media&token=a3f9a8a9-bfe1-42f6-a79c-af551e73129d)

​

​

​

​

​

​

​

​

​

​

​

​

