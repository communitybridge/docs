# Enable or Disable Scanning for a Repository

From Settings tab, you can perform the following tasks:

* Enable or disable vulnerability and code secret scanning for a repository to refine scanning report of the project.
* Auto enabling repositories for scanning vulnerabilities and code secrets.
* Adding non inclusive words to scan from the code.

## **Enable/Disable a Repository for Vulnerability Scan**

You can enable or disable a repository for vulnerability scanning in the Settings tab. If you enable a repository for vulnerability scanning, the repository is scanned for the vulnerabilities. If you disable the vulnerability scanning for a repository, the scanning will be skipped for the selected repository and vulnerabilities will not be detected.  

To enable or disable a repository for vulnerability scan, perform the following steps:

1.Select **Settings** from the menu and click **Vulnerabilities**.  
All repositories of the project are listed in alphabetical order. 

![Vulnerabilities Settings](../.gitbook/assets/vul%20%281%29.png)

2.Under **Scan Vulnerabilities** tab, toggle **scan** button to enable or disable a repository from scanning. 

{% hint style="info" %}
You can also enable or disable scanning for all repositories by toggle of **Scan Vulnerabilities**. 
{% endhint %}

![Scan Repositories](../.gitbook/assets/settings%20%283%29.png)

3. Under **Last** **Scan Results** tab, you can see whether the repository scan has been successful or where there were any errors while scanning the repository.

When the scan of the repository is successful, it is displayed as **Successful** and if there are any errors, it will be displayed as **Error**.

{% hint style="info" %}
The error details for the repository is displayed when you click the ![](../.gitbook/assets/error.png) icon. 

An error will be displayed when the language used in the repository is not supported by Security scan.
{% endhint %}

![Last Scan Results](../.gitbook/assets/last_scan%20%282%29.png)

## Adding Non Inclusive Words

You can add the words which depict people unfairly in an insulting manner and exclude people based on their ethnicity, gender or color. LFX will scan for these non inclusive words in the code. You refer [Non Inclusive Languag](non-inclusive-language.md)e section for more information. 

To add non inclusive words, perform the following steps:

1.Select **Settings** from the menu and click **Vulnerabilities**.

![Non Inclusive Language Settings ](../.gitbook/assets/setting_nil.png)

2.Enter the non inclusive word in the **Add word** box and click **+Add**. The added non inclusive words are listed under NON-INCLUSIVE LANGUAGE. 

![Adding Non Inclusive Word](../.gitbook/assets/setting_nil_2.png)

## Auto Enable Scanning of Repositories for Vulnerabilities

You have an option to auto enable scanning of repositories for vulnerability scanning when a new repository is added in the GitHub project. When you select the Auto enable option, all the new repositories are scanned for the vulnerabilities. 

You can the **Auto Enable New Repositories** toggle button to set the auto scanning of the new repositories. This button is available in the **Settings tab** and under **** **Vulnerabilities**.

![Auto Enable ](../.gitbook/assets/enable_vul.png)











