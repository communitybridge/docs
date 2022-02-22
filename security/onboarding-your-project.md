# Onboarding your Project

You have to onboard your project from GitHub to use LFX Security services. First you need to onboard your project to start scanning for vulnerabilities detection, code secrets and non inclusive language.

Onboarding projects into LFX Security is done from the PCC (Project Control Center). As part of this onboarding a Security Bot is installed on GitHub Organizations of the project.

{% hint style="info" %}
You need to raise a ticket if you do not have access to PCC. Use this [link ](https://jira.linuxfoundation.org/plugins/servlet/theme/portal/4/create/358)to raise a support ticket to access PCC.

If you want to know more about PCC, please visit [PCC ](https://lfx.linuxfoundation.org/tools/project-control-center)website. You can refer [PCC documentation](https://docs.linuxfoundation.org/lfx/project-control-center-pre-release) for more information.

For more information on Security related activities that can be configured using PCC, refer [Security PCC Documentation](https://docs.linuxfoundation.org/lfx/project-control-center-pre-release/tools/security).&#x20;
{% endhint %}

## Security Bot Installation <a href="#security-bot-installation" id="security-bot-installation"></a>

Onboarding projects into LFX Security is done from the PCC (Project Control Center). As part of this onboarding a Security Bot is installed on GitHub Organizations of the project.

To setup the Security service using PCC, perform the following steps:

1.Login into [PCC](https://projectadmin.lfx.linuxfoundation.org).

2\. Search for the required project. The Project dashboard appears. Click **Security** from the **TOOLS STATUS** tab.

{% hint style="info" %}
You can also navigate to Security from the Vertical Sidebar navigation menu. Click **Tools** and then select **Security**.
{% endhint %}

![Security](https://gblobscdn.gitbook.com/assets%2F-MCG-Km6\_RcGyUVKsLIx%2F-Md\_ivAMZ2h7xOPMQ1bm%2F-Md\_mIFlNU7OimypntPn%2FDash.png?alt=media\&token=9330c513-4ef2-44ef-bb59-a4bd0970f8d3)

3.The Security page appears. From the **GitHub Onboarding** tab, click the ![](<../.gitbook/assets/Icon (1).png>) icon available next to **Connect**.

![GitHub Onboarding](../.gitbook/assets/GitHub.png)

4.Enter the GitHub organization name in the **Organization Name** and click **Connect**.

{% hint style="info" %}
Make sure that you logged into the GitHub.
{% endhint %}

![GitHub Organization](https://gblobscdn.gitbook.com/assets%2F-MCG-Km6\_RcGyUVKsLIx%2F-Md\_mOyIwS7BfDv1FdCc%2F-Md\_yXHWG4O7-HtqIzz5%2FConn.png?alt=media\&token=78832048-9ba6-45d4-979c-aa1d453aac7a)

5.The Install Security Bot on GitHub.org instructions page appears. You can read the instructions on how to install the Security Bot from this page. Click **Install Security Bot** button.

![Installing Security Bot](https://gblobscdn.gitbook.com/assets%2F-MCG-Km6\_RcGyUVKsLIx%2F-Md\_mOyIwS7BfDv1FdCc%2F-Md\_zFZbK923mmbZQJB0%2FInstructions%20.png?alt=media\&token=60735f71-3f39-4d22-8583-1a64f7835d80)

6\. A list of GitHub organization associated with the login account are listed and displayed. Select the required organization for which you want to install the Security bot.

![GitHub Organizations](https://gblobscdn.gitbook.com/assets%2F-MCG-Km6\_RcGyUVKsLIx%2F-Md\_mOyIwS7BfDv1FdCc%2F-Mda-O7Icw1gTvpJ6KPN%2FList.png?alt=media\&token=607604ff-a16b-43d2-a849-6600b42a55df)

7.The Install & Authorize LFx Security GitHub App page appears. This page provides the following information:

* Information on the permission requested for the selected repositories. The LFX Security requests the following permissions from the GitHub:
  * **Read** access to administer, code, check commit status, lookup members, and other metadata.
  * **Read** and **write** access to organization hooks, pull requests, and repository hooks.
  * Installing and authorizing LFX Security GitHub App grants these permissions on your account:
  * **Read** access to emails
* Access to the repositories. You can either provide access to all the repositories or selected repositories within the GitHub Organization.

Click **Install & Authorize** to install the LFX Security GitHub App.

![Installation Permissions](https://gblobscdn.gitbook.com/assets%2F-MCG-Km6\_RcGyUVKsLIx%2F-Mda-VDpqAUlhN8R8l0O%2F-Mda0Y05c0Cd9uERFvr\_%2FInstall.png?alt=media\&token=f96cedc0-9617-4673-8b23-edf297039fc5)

8.The LFX Security Service GitHub app is installed successfully. You can see the installation success message.

![Installation Complete](https://gblobscdn.gitbook.com/assets%2F-MCG-Km6\_RcGyUVKsLIx%2F-Mb54\_KofyumI-UB7Wl7%2F-Mb57cBro\_UemLOIw-T9%2FSuccess.png?alt=media\&token=852f8d1c-1abf-40c3-9a87-cfd27b4772ee)

{% hint style="info" %}
You will also receive an email after successful installation of the LFX Security GitHub App.
{% endhint %}

9.In the PCC page, you need to click **I'm Done Installing the Security Bot** after completing the installation process.

![Security Bot Installation Complete](https://gblobscdn.gitbook.com/assets%2F-MCG-Km6\_RcGyUVKsLIx%2F-Mda1J-8wCyl01h8FL5W%2F-Mda1pvwhmetx23dDFqg%2FDone.png?alt=media\&token=0ed8c719-b2b7-4ddb-929a-21ff7b7f30aa)

10.You can see the list of GitHub organizations along with the repositories for which the Security bot has been successfully configured.

{% hint style="info" %}
A green dot present with the GitHub organization name indicates that the Security bot is successfully installed.
{% endhint %}

![GitHub Organization](https://gblobscdn.gitbook.com/assets%2F-MCG-Km6\_RcGyUVKsLIx%2F-Mda1J-8wCyl01h8FL5W%2F-Mda314iwtsBVKz0r-dW%2FGithub%20-%20Copy.png?alt=media\&token=fa8bd9e0-71b0-4c9a-aea9-5584ac639dbd)

## Security Bot Uninstallation <a href="#security-bot-uninstallation" id="security-bot-uninstallation"></a>

You can uninstall the security bot at any point of time from the PCC. When you uninstall the security bot, the security scanning for the GitHub organization is discontinued. You cannot see the vulnerabilities associated with your GitHub organizations.

To uninstall Security service from PCC, perform the following steps:

1.Login into [PCC](https://projectadmin.lfx.linuxfoundation.org).

2\. Search for the required project. The Project dashboard appears. Click **Security** from the **TOOLS STATUS** tab. The GitHub organizations are listed, select the settings ![](https://firebasestorage.googleapis.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-MCG-Km6\_RcGyUVKsLIx%2F-Mda365nvB-pYuIRy-C-%2F-Mda6J3cFJ46Jm-7DZGL%2FSetting%20.png?alt=media\&token=31867e54-5c98-4262-94fa-b1938c2972fd) icon and click **Disassociate GitHub Org**.

![Disassociate GitHub Org](https://gblobscdn.gitbook.com/assets%2F-MCG-Km6\_RcGyUVKsLIx%2F-Mda365nvB-pYuIRy-C-%2F-Mda6YqKDezwn0S201M0%2FUninstall.png?alt=media\&token=63d471ca-dd3b-4a5c-9627-117a08e7cec0)

3.The Uninstall Security Bot on GitHub.org instructions page appears. You can read the instructions on how to uninstall the Security Bot from this page. Click **Uninstall Security Bot** button.

![Uninstalling Security Bot](https://gblobscdn.gitbook.com/assets%2F-MCG-Km6\_RcGyUVKsLIx%2F-Mda365nvB-pYuIRy-C-%2F-Mda7C8dm1PC7eQpYypM%2FUninstall%20Instructions%20.png?alt=media\&token=8ffdef7f-443c-4729-a72d-b8d63469bd17)

4.The LFx Security GitHub App opens in a new tab. Click **Uninstall** from the Danger Zone.

{% hint style="info" %}
You can uninstall the Security bot from all the repositories associated with your GitHub organization by selecting **All Repositories** or select specific repositories for which you want to uninstall the Security bot by selecting **Only Select Repositories**.
{% endhint %}

![Uninstallation Process](https://gblobscdn.gitbook.com/assets%2F-MCG-Km6\_RcGyUVKsLIx%2F-Mda365nvB-pYuIRy-C-%2F-Mda8yYyOkeakZiTQBbw%2FUninstall%20Process.png?alt=media\&token=db38475e-c3a4-4e85-a81c-b467f099fa69)

5\. A pop message appears informing that the Security bot will be uninstalled for the selected repositories. Click **OK** to continue with the uninstallation process.

![Dialog Box](https://gblobscdn.gitbook.com/assets%2F-MCG-Km6\_RcGyUVKsLIx%2F-Mda365nvB-pYuIRy-C-%2F-Mda9c2h\_NFtiXZbQZnV%2FDialog%20.png?alt=media\&token=73499c42-994c-4cac-9250-d6432041ebbb)

6.In the PCC page, you need to click **I'm Done Uninstalling the Security Bot** after completing the uninstallation process.

![Uninstallation of Security Bot](https://gblobscdn.gitbook.com/assets%2F-MCG-Km6\_RcGyUVKsLIx%2F-Mda365nvB-pYuIRy-C-%2F-MdaAU0-V1hR1xBVSuoO%2FDone%20unistallation.png?alt=media\&token=08d524b0-f241-4150-9844-8f64cf60d5d3)

7.The GitHub repositories will be removed from the Security dashboard. But, you can see the GitHub organization name in the Security dashboard.

{% hint style="info" %}
A red dot present with the GitHub organization name indicates that the Security bot is successfully uninstalled.
{% endhint %}

![](https://gblobscdn.gitbook.com/assets%2F-MCG-Km6\_RcGyUVKsLIx%2F-MdaFPJcXjqEQwnynKZe%2F-MdaGXG0vEiuFgg7zy4q%2FDisaa.png?alt=media\&token=fbe479b1-b132-4eaf-a8b5-8b1e2c51fe1e)

8.If you want to remove the GitHub organization completely from the Security dashboard, click **Disassociate Organization**.

![Disassociation Organization](https://gblobscdn.gitbook.com/assets%2F-MCG-Km6\_RcGyUVKsLIx%2F-MdaFPJcXjqEQwnynKZe%2F-MdaHjpokpWvFrsnCRn6%2FDisaa1.png?alt=media\&token=092d6bf3-5281-498a-a734-7684abe0a148)

9.A pop message appears informing that the GitHub organization will be disassociated. Click **Disassociate** to continue with the disassociation process.

![Dialog Box](https://gblobscdn.gitbook.com/assets%2F-MCG-Km6\_RcGyUVKsLIx%2F-MdaFPJcXjqEQwnynKZe%2F-MdaHyRNc2eJqvR49-5m%2FDiss%20Dial.png?alt=media\&token=0a3eba88-dd48-4f75-b55a-7b5bdc9d468b)

## Suspending Security Service <a href="#suspending-security-service" id="suspending-security-service"></a>

You have an option to suspend the Security service scanning without uninstalling the Security bot. When you suspend the Security service, the bot will not be uninstalled. You can revoke the suspension at any point of time by Unsuspending.

To suspend the Security service, perform the following steps:

1.Login into [PCC](https://projectadmin.lfx.linuxfoundation.org).

2\. Search for the required project. The Project dashboard appears. Click **Security** from the **TOOLS STATUS** tab. The GitHub organizations are listed, select the settings ![](https://firebasestorage.googleapis.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-MCG-Km6\_RcGyUVKsLIx%2F-Mda365nvB-pYuIRy-C-%2F-Mda6J3cFJ46Jm-7DZGL%2FSetting%20.png?alt=media\&token=31867e54-5c98-4262-94fa-b1938c2972fd) icon and click **Configure Security Bot**.

![Configure Security Bot](https://gblobscdn.gitbook.com/assets%2F-MCG-Km6\_RcGyUVKsLIx%2F-Mdw7VO3TEQTCP-g3IBS%2F-MdwAAWR5sehaVt4iyyb%2FCng.png?alt=media\&token=fe706d44-44ec-4b46-bd22-98b69abccd88)

3.The LFx Security GitHub App opens in a new tab. Click **Suspend** from the Danger Zone.

![Suspend](https://gblobscdn.gitbook.com/assets%2F-MCG-Km6\_RcGyUVKsLIx%2F-Mdw7VO3TEQTCP-g3IBS%2F-MdwA\_xq6S3gHfNE0GZ6%2FSuspend.png?alt=media\&token=8c47c8d3-8d92-426b-b522-b655efa24b52)

4.A pop message appears informing that the Security bot will be suspended. Click **OK** to continue with the suspension process.

![Dialog Box](https://gblobscdn.gitbook.com/assets%2F-MCG-Km6\_RcGyUVKsLIx%2F-Mdw7VO3TEQTCP-g3IBS%2F-MdwB0m5fT4bW017P0Mb%2FSus\_dailog.png?alt=media\&token=ecc1c0b7-caee-40e6-b883-fa691373fd67)

5.The GitHub repositories are suspended from the Security dashboard.

{% hint style="info" %}
A orange dot present with the GitHub organization name indicates that the Security bot is suspended.
{% endhint %}

![Security Service Suspension](https://gblobscdn.gitbook.com/assets%2F-MCG-Km6\_RcGyUVKsLIx%2F-Mdw7VO3TEQTCP-g3IBS%2F-MdwBk1mbPFfwWLx5Fpi%2FSuspened\_dash.png?alt=media\&token=143bab57-7328-42f4-a685-bcfccc363a92)

{% hint style="info" %}
To revoke the suspended Security service, click settings ![](https://firebasestorage.googleapis.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-MCG-Km6\_RcGyUVKsLIx%2F-Mda365nvB-pYuIRy-C-%2F-Mda6J3cFJ46Jm-7DZGL%2FSetting%20.png?alt=media\&token=31867e54-5c98-4262-94fa-b1938c2972fd) icon and click **Configure Security Bot** and click **Unsuspend** from the Danger Zone.
{% endhint %}

![Unsuspend](https://gblobscdn.gitbook.com/assets%2F-MCG-Km6\_RcGyUVKsLIx%2F-MdwC24qZowncgFnTF9D%2F-MdwDBXMoede-dDXiOX0%2FUnsuspend.png?alt=media\&token=f41d5533-57c8-4c00-818d-7d0a8f81f643)
