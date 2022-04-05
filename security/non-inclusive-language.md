# Non Inclusive Language

LFX Security in collaboration with BluBracket scans for non inclusive language. Non inclusive language that depict people unfairly in an insulting manner and exclude people based on their ethnicity, gender or color. Usage of these words or language is not expected use in the open source code.

LFX Security will scan for the non inclusive language which might have been added by the developers unintentionally without their knowledge. Some of the generic non inclusive words that are used in the code are blacklist, whitelist, slave, master.

To view non inclusive language, perform the following steps:

1.Login to [LFX Security](https://security.lfx.linuxfoundation.org), select the required project and click click **View Dashboard**.

![View Dashboard](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-M2DCN9UgoRgMEkgnLyP-887967055%2Fuploads%2FrhdmsDSWqvMIsRau6CFg%2FView\_Dashboard.png?alt=media\&token=58db8f2d-414b-4e0c-95c0-e5b71e0e3f7c)

2.Select **NON-INCLUSIVE LANGAUGE** from the top menu.

![Non Inclusive Language](<../.gitbook/assets/Non Ilcu2.png>)

3.The list provides the following details related to the non inclusive language:

* **Detected On** - Date and time when the code is scanned
* **Description** - Non inclusive language used in the code
* **Repository** - Name of the GitHub repository which contains the code from where the non inclusive language has been detected
* **Developer** - Name of the developer who has checked in the code in the repository
* **Notify** - Notification button which can be used to notify the developer

{% hint style="info" %}
When you click on the **Description** of the non inclusive language, you will be taken to the line of the code where non inclusive language has been used.
{% endhint %}

## Notifying Developer <a href="#notifying-developer" id="notifying-developer"></a>

You have an option to notify the developer who has added non inclusive language in their code. This notification feature will allow the developer to remove or replace the non inclusive language.

{% hint style="warning" %}
You should have the necessary permission to take action related to notifying a developer for non inclusive language. With out necessary permissions, the **Notify** button will not be available to take action on non inclusive language.
{% endhint %}

To notify a developer on usage of non inclusive language, perform the following steps:

1.Select **NON-INCLUSIVE LANGAUGE** from the top menu.

2.Under Notify tab, click **Send Reminder**. A confirmation dialog box appears informing that a notification will be send to developer. A notification email is delivered to developer who has added the non inclusive language.

{% hint style="info" %}
You can see **Notified** along with a green tick mark when a notification is sent to the developer.
{% endhint %}

{% hint style="warning" %}
You cannot send a reminder to developer, if the developers email is marked as private.
{% endhint %}

![Reminder](../.gitbook/assets/Notify\_Non.png)

3.A confirmation dialog box appears informing that a notification will be sent to developer. Click **Send Notification** to confirm.

![Confirmation Message](<../.gitbook/assets/Non\_Conf (1).png>)

3.You can also send a reminder notification to the developer if the developer has not replaced the non inclusive language even after a notification. Click **Remind Developer** to send a reminder notification.

### Categorization of Non Inclusive Words <a href="#categorization-of-code-secrets" id="categorization-of-code-secrets"></a>

LFX Security allows you to categorize the non inclusive words using various parameters. Following are few of the categories available to filter or categorize non inclusive words:

* Description Filters
* Repository Filters
* Developer Filters
* Notify Filters

To add filter, perform the following:

1.Click **Add Filters +** and select the required filters and click **Apply Filters**.

![Filters](../.gitbook/assets/Non\_Filters.gif)

​

​
