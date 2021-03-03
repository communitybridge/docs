# Create New CLA Group

A CLA Group defines:

* What CLA types your project requires for pull requests or push submissions — corporate CLA \(CCLA\), individual CLA \(ICLA\), or both
* What CLA templates are used for the CCLA and/or ICLA
* What GitHub repositories, Gerrit instances, or both are enforced for CLA monitoring

A single CLA Group includes a pair of CCLA and ICLA templates, if both types are enabled for that CLA Group.

## To Create a project's CLA Group:

1. [Sign in](sign-in-to-project-control-center.md) to the Project Control Center.
2. Under My Projects, click a project or search the project from the search bar for which you want to create a CLA group.
3. From **Tools** tab, click **CLA**.

![](../../.gitbook/assets/tools-tab.png)

1. Click **+Add New CLA Group**.  

   **Note:** For the initial v2 release, a single project can only have one CLA Group. If you have already created a CLA Group for that project, _or for a parent of that project_, the **+Add New CLA Group** button will be disabled and you will not be able to create another CLA group for that project.

![Add New CLA Group](../../.gitbook/assets/add-new-cla-group%20%281%29.png)

1. Under **CLA Group Name** tab, provide a CLA group name and a brief description in the respective fields.  

   **Note:** Click the help icons \(**?**\) to know more about a field or check box.

![](../../.gitbook/assets/cla-group-name%20%281%29.png)

1. Select the check boxes as applicable to the contributors of a project, and click **Next**.

{% hint style="info" %}
* A warning message appears if you select only one. Most projects will enable contributions under a CCLA as well as an ICLA.
* If you only select **Corporate CLA**, then only corporate employees can sign and contribute to your project.
* If you only select **Individual CLA**, then only individuals can sign and contribute to your project.
{% endhint %}

1. Under **Edit/Review Template** tab, carefully review the CCLA and/or ICLA template settings:
2. The default template available is for a standard CCLA / ICLA pair that is used by several projects on EasyCLA. These templates are derived from the Apache Software Foundation's CLAs, but are _not_ identical and should not be described as "Apache CLAs."
   * If your project will be using a different CLA template, _stop and do not proceed_. Contact the EasyCLA support team by [filing a support ticket](https://jira.linuxfoundation.org/plugins/servlet/theme/portal/4/create/143) with the correct CCLA and ICLA templates that your project will use.
3. Closely review the Project Name and Project Full Entity Name fields. These are being pulled from the Project object database backend. These should reflect the project name and the entity that is receiving the contributions for the _technical project_. If these are not correct, _stop and do not proceed_. Check the Project object database settings and contact the LF legal team at legal@linuxfoundation.org if you have questions.
4. Enter the appropriate point of contact in the **Email Address of Person Managing Project** field. This will be filled into the CLA templates as the email address for contributors to submit signed CLAs if they want to sign them manually, rather than via DocuSign.
5. Carefully review the generated CCLA and ICLA templates. If the filled-in values or other contents of the template do not look correct, _stop and do not proceed_. Contact the EasyCLA support team by [filing a support ticket](https://jira.linuxfoundation.org/plugins/servlet/theme/portal/4/create/143) if you need assistance.
6. If the Project for which you are creating the CLA Group has no subprojects, then click **Finish** and skip the next step.
7. If the Project for which you are creating the CLA Group _does_ have subprojects, then click **Next**. Under the **Select Projects** tab, select the projects that you want to enroll under the CLA group, and click **Finish**.

{% hint style="info" %}
**Note:**

As mentioned above, for the initial v2 release, a single project can only have one CLA Group. If you have already created a CLA Group for that project, _or for a parent of that project_, the **+Add New CLA Group** button will be disabled and you will not be able to create another CLA group for that project.
{% endhint %}

![Creating CLA group at project-group level](../../.gitbook/assets/select-projects.png)

