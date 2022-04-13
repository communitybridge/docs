# Create New CLA Group

{% hint style="info" %}
A CLA Group defines:

* What CLA types your project requires for pull requests or push submissions — corporate CLA (CCLA), individual CLA (ICLA), or both, What CLA templates are used for the CCLA and/or ICLA, What GitHub repositories, Gerrit instances, or GitLab groups are enforced for CLA mechanism
{% endhint %}

A single CLA Group includes a pair of CCLA and ICLA templates, if both types are enabled for that CLA Group.

## To Create a project's CLA Group: <a href="#to-create-a-projects-cla-group" id="to-create-a-projects-cla-group"></a>

1\. ​Sign in to the [Project Control Center](https://projectadmin.lfx.linuxfoundation.org).

2\. Under My Projects, click a project or search the project from the search bar for which you want to create a CLA group.

3\. From left-side navigation, Navigate to **Tools >** **EasyCLA**.

![](<../../../.gitbook/assets/tools status tab (1).png>)

4\. Click **+Add New CLA Group**.

**Note**: For the current v2 release, a single project can have only one CLA Group. If you have already created a CLA Group for that project, or for a parent of that project, the +Add New CLA Group button will be disabled and you will not be able to create another CLA group for that project.

![Add New CLA Group](https://files.gitbook.com/v0/b/gitbook-legacy-files/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-MYL76gRXl7OC0uMczgL%2F-MYL9ZY5RyYNN3Ob-lmt%2Fadd%20new%20cla%20group.png?alt=media\&token=9176f3b2-6688-42e9-aed5-6217e3fad393)

5\. Under CLA Group Name tab, provide a CLA group name and a brief description in the respective fields.

**Note:** Click the help icons (?) to know more about a field or check box.

![](https://files.gitbook.com/v0/b/gitbook-legacy-files/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-MFF3NJccWCBBW7digJF%2F-MFFWZikCY6DvtHwYHMf%2Fcla%20group%20name.png?alt=media\&token=1c51f264-a246-4a30-ad26-ee05a172e9ca)

6\. Select the check boxes as applicable to the contributors of a project, and click **Next**.

{% hint style="info" %}
* A warning message appears if you select only one. Most projects will enable contributions under a CCLA as well as an ICLA.
* If you only select Corporate CLA, then only corporate employees can sign and contribute to your project.
* If you only select Individual CLA, then only individuals can sign and contribute to your project.
{% endhint %}

7\.  Under **Edit/Review Template** tab, review the project name, project full entity name. If these are not correct, stop and do not proceed. Check the Project object database settings and contact the LF legal team at legal@linuxfoundation.org if you have questions.

8\. Then, select a template from **Template** drop-down. and provide appropriate point of contact in the **Email Address of Person Managing Project** field. This will be filled into the CLA templates as the email address for contributors to submit signed CLAs if they want to sign them manually, rather than via DocuSign.

{% hint style="info" %}
Note:

* If you want to use a different template than the ones listed, [create a support ticket](https://jira.linuxfoundation.org/plugins/servlet/theme/portal/4/create/143) with the correct CCLA and ICLA templates that your project will use.
* Both the available templates are standard CCLA / ICLA pairs that are used by several projects on EasyCLA. These templates are derived from the Apache Software Foundation's CLAs and Academy Software Foundation's CLAs, but are not identical to either of them.
{% endhint %}

9\. Review the generated CCLA and ICLA templates. If the filled-in values or other contents of the template do not look correct, stop and do not proceed. Contact the EasyCLA support team by [filing a support ticket](https://jira.linuxfoundation.org/plugins/servlet/theme/portal/4/create/143) if you need assistance.

![Edit and Review Template](https://files.gitbook.com/v0/b/gitbook-legacy-files/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-McSaJy\_3W3NgkLpAr5s%2F-McSjta9Z-88O5b0XWD6%2Fedit-review-template.png?alt=media\&token=35c03702-876a-4b80-a6a8-2bc8a9869987)

10\. If the Project for which you are creating the CLA Group has no subprojects, then click **Finish** and skip the next step.

11\. If the Project for which you are creating the CLA Group does have subprojects, then click **Next**. Under the **Select Projects** tab, select the projects that you want to enroll under the CLA group, and click **Finish**.

{% hint style="info" %}
**Note**: As mentioned above, for the initial v2 release, a single project can only have one CLA Group. If you have already created a CLA Group for that project, or for a parent of that project, the **+Add New CLA Group** button will be disabled and you will not be able to create another CLA group for that project.
{% endhint %}

![](https://files.gitbook.com/v0/b/gitbook-legacy-files/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-MYL76gRXl7OC0uMczgL%2F-MYLAq\_x4OegnUUpOhAQ%2Fcreating%20CLA%20group%20at%20project-group%20level.png?alt=media\&token=88f0f38f-527f-4cbb-a019-d84aabc16c97)
