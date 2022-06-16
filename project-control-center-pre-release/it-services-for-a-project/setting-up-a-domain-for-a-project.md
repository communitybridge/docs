# Setting up a Domain for a Project

A domain name provides a unique identity for your project. You can set up a unique domain name that will allow you to have a administrative autonomy as well as control within the internet world.

To setup a domain for the project, perform the following steps:

1.Login into PCC.

2\. Search for the required project. The Project dashboard appears. Click **Domains** from the **IT SERVICES STATUS** tab.

{% hint style="info" %}
You can also navigate to Domains from the Vertical Sidebar navigation menu. Click **IT Services** and then select **Domains**.
{% endhint %}

![Domain](../../.gitbook/assets/Domain.png)

3.The Domains page appears. Click **+ Add Domain** to add a domain for your project.

{% hint style="warning" %}
You cannot change the primary domain for the project, if you want to change the primary domain, you need to raise a support ticket.
{% endhint %}

{% hint style="info" %}
You can update the details of the domain by click of the edit ![](../../.gitbook/assets/Edit\_Icon.png) icon.
{% endhint %}

![Add Domain](../../.gitbook/assets/Add\_Domains.png)

4.The Add Domain dialog box appears. Enter the **Domain Name** and click the **Check Availability** button.

![Domain Name](<../../.gitbook/assets/Add\_d (1) (1) (1) (1) (1).png>)

5.The domain will be searched and checked against the following points:

* The domain is already owned by the project that's being setup
* The domain is already owned but by another project (when the project name unknown)
* The domain is already owned but by another known project.

6.If the domain name is available, a green tick mark is displayed next to the **Domain Name**. Click the **Register Domain** button to register the domain. Refer Register Domain for more details.

![Register Domain](https://gblobscdn.gitbook.com/assets%2F-MEMVgDuxi7j4ZpeENUY%2F-MKV83M2RA5cwHGboqCZ%2F-MKV9Lcayqjh66ZZqTZF%2FRegister\_Domain.png?alt=media\&token=90354b3d-75a2-4e5c-a06f-e85c9334b549)

7.If the domain is already taken by an another project, you have the option to bid for that domain.

{% hint style="danger" %}
You should have the primary domain setup for a project in order to setup other IT Services such as Mailing List, Wiki, Issue Tracking, and Email Forwarding services.
{% endhint %}

## Setting up Primary Domain

You can setup a primary domain for a project within the available and registered domains for a project. A primary domain is usually a main domain which is selected to represent the address for your company or project. Primary domain is the main domain which is also associated with the web hosting for your company or project.

To setup a primary domain for a project, perform the following:

1.Go to the Domains page for the required project. The domain page appears with the list of domains registered with the project.

2.Place the cursor in the **Search Domain** box, select the required domain and click the **Set As Primary Domain** button.

![Primary Domain](../../.gitbook/assets/PD.png)

3.The domain will be selected and listed as Primary Domain.

![Primary Domain](../../.gitbook/assets/PD1.png)

## Redirecting a Domain

You can redirect a domain from one domain to another. Redirects are a way to forward visitors and search engines to a different URL than the one they requested. You can use redirects when you’re moving content around and you want the content to retain its value.

To redirect a domain from one domain to another domain, perform the following:

1.Go to the Domains page for the required project. The domain page appears with the list of domains registered with the project.

2.Click ![](../../.gitbook/assets/Edit\_Icon.png) icon available under Manage pane.

![Manage](../../.gitbook/assets/PD2.png)

3.The Edit Domain dialog box appears. Click **Redirects**, enter the redirect domain under **To** box and click **Add**.

![Redirect](../../.gitbook/assets/Redirect.png)

4.The redirected domain is listed under **Existing Redirects** list.

![Existing Redirect](<../../.gitbook/assets/Redirect list.png>)

{% hint style="info" %}
If you want to update the redirect domain, click the edit ![](../../.gitbook/assets/Edit.png) icon.

If you want to delete the redirect domain, click the delete ![](../../.gitbook/assets/delete\_icon.png) icon.
{% endhint %}

## Adding a Service Record

You can add service record such as Pantheon, Netlify and GitHub pages for your domain.

To setup service record, perform the following steps:

1.Go to the Domains page for the required project. The domain page appears with the list of domains registered with the project.

2.Click ![](../../.gitbook/assets/Edit\_Icon.png) icon available under Manage pane.

![Domain Edit](../../.gitbook/assets/PD2.png)

3.The Edit Domain dialog box appears. Click **Services**, select the required Service from the list and click **Add**.

![Services](../../.gitbook/assets/Service.png)

4.The service records are listed under **Existing Service Records** list.

## Disable Auto Renew

By default, when a domain is added to your project; the domain is set to auto renew. Administrator can disable the auto renew.

To disable the auto renew of the domain, perform the following:

1.Click the ![](../../.gitbook/assets/Dot\_Icon.png) icon and select **Disable auto-renew**.

![Auto Renew](<../../.gitbook/assets/Auto renew.png>)

2.The Disable auto renew dialog box appears. Click Yes to cancel the auto renewal of the domain.

![Cancel Auto Renewal](../../.gitbook/assets/Disabled.png)

3\. A flyer message appears informing that the auto renewal of the domain is disabled. You can also see ![](<../../.gitbook/assets/Cross (1) (1) (1) (1).png>) icon under Auto Renew column.

![Disabled Status](../../.gitbook/assets/Disabled\_Success.png)

## Transfer Domain

As a administrator, you can transfer the domains which are owned outside your project. You can transfer such domains to your projects.

To transfer a domain, perform the following:

1.Click **+ Add Domain**.

![Add Domain](<../../.gitbook/assets/Add\_Domain (2) (1).png>)

2.The Add Domain dialog box appears. Enter the name of the domain that you want to transfer to your project and click **Check Availability**.

![Check Availability](<../../.gitbook/assets/Add\_d (1) (1) (1).png>)

3.You can see the Domain Taken message. Click **Yes; Transfer Domain**.

![Transfer Domain](../../.gitbook/assets/Domain\_Taken.png)

4.One more message appears that informs you whether Linux Foundation should manage your DNS. Select Yes or No.

![Manage DNS](../../.gitbook/assets/Manage.png)

5.You can import the DNS Zone file or skip it, if you do not have it. Click **Save and Continue**.

![Import DNS](<../../.gitbook/assets/DNS Skip.png>)

6.The Domain will be listed in your project with status **Transfer Code Needed**.

![Transfer Code Needed](../../.gitbook/assets/Domain\_Not.png)

{% hint style="info" %}
You have to provide the transfer code in order to complete the domain transfer. To provide the transfer code, click ![](../../.gitbook/assets/Dot\_Icon.png) icon and select **Continue Transfer** and enter the transfer code that you will receive from the registrar of your domain. Select My Domain is unlocked and My DNS Service is not hosted and click **Begin Transfer**.
{% endhint %}

![](../../.gitbook/assets/Transfer.gif)

## Delegate DNS

Domain Name System (DNS) is the hierarchical and decentralized naming system used to identify computers, services, and other resources reachable through the internet or other internet protocol networks. DNS converts human readable domain names to machine readable IP addresses.

DNS Delegation is nothing but providing rights from one resource to another resource. Delegations allows the servers in one zone to refer clients to servers in other zones.

Administrator can delegate the DNS for the managed DNS.

To delegate the DNS through PCC, perform the following:

1.Go to the Domains list and click the ![](../../.gitbook/assets/Dot\_Icon.png) icon and click **Delegate DNS (no managed DNS)**.

![Delegate DNS](../../.gitbook/assets/DNS.png)

2.The Delegate DNS server pop box appears. Provide the required **Name Servers** and select the **I Understand** statement and click **Delegate**.

{% hint style="info" %}
You can provide the details of the six name servers.
{% endhint %}

![Name Servers](../../.gitbook/assets/Name\_Servers.png)

3.A flyer message appears informing that the DNS delegation is success and under DNS Hosting, the managed status changes to **Delegated**.

![Delegated](../../.gitbook/assets/Delegated.png)

{% hint style="info" %}
Administrator can stop the delegation of the DNS, click ![](../../.gitbook/assets/Dot\_Icon.png)icon and select **Stop Delegating DNS ( use Managed DNS)**. A confirmation message appears, click **Yes**.
{% endhint %}

![Stop Delegation](../../.gitbook/assets/Stop.gif)
