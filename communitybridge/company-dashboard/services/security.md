# Security

Only members of Linux Foundation can see security dashboard. The below screen appears if you are not a member of Linux Foundation or are not logged in as a member.

![](https://gblobscdn.gitbook.com/assets%2F-LuGl2w4LzPpYJ8jx5ae%2F-M4DxV-QOC4R5AUyKqjH%2F-M4E-_ZX7IeYOANIbvbM%2Fsecuiry%20non-member%20view.png?alt=media&token=31a56b8b-0cfe-46d7-b52c-db8e5f4f3c1a)

## SECURITY HIGHLIGHTS <a id="security-highlights"></a>

​

### UNIQUE LICENSE IN STACK <a id="unique-license-in-stack"></a>

Represents a doughnut chart that shows total number of licenses \(in the middle of the chart\), and name of individual licenses by percentage with respect to the license's usage in all projects. This chart shows the top 10 licenses by name, and all other licenses are grouped in **OTHERS** category.

The value in the middle of the doughnut chart shows the total number of licenses. Mouse over a color to see the license name, and its percentage of usage.

![Unique License in Stack](https://gblobscdn.gitbook.com/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-M5_geFCv5JS8dCTb63m%2F-M5_rMrWs8G_6eLbg5zp%2Funique%20license%20in%20stack.png?alt=media&token=caf5161f-bd76-4e12-9ff7-a8201a1fb7a7)

### REMEDIATION RATE

Shows a bar graph that represents total number of vulnerabilities count for all the projects from the time the projects were on-boarded to CommunityBridge Security for scanning.

* **Upstream** shows total number of vulnerabilities found in libraries code, and percentage wise breakup of total number of vulnerabilities into fixes recommended and not recommended categories.
* **Base** shows total number of vulnerabilities found in base code, and percentage wise breakup of total number of vulnerabilities into fixes recommended and not recommended categories.

Mouse over a color to see the total number of vulnerabilities for recommended or not recommended category.

![](https://gblobscdn.gitbook.com/assets%2F-LuGl2w4LzPpYJ8jx5ae%2F-M4O_5m174YFCZi5nfNQ%2F-M4Of0Pz0MVGGFuAMjhT%2Fremediation%20rate.png?alt=media&token=a67ccf10-a497-4948-9699-838a40a7b910)

Remediation Rate

### LANGUAGE DISTRIBUTION ACROSS PROJECTS <a id="language-distribution-across-projects"></a>

Represents a doughnut chart that shows total number of projects \(in the middle of the chart\), and name of individual programming languages by percentage with respect to the language's usage in all projects. This chart shows the top 10 licenses by name, and all other licenses are grouped in **OTHERS** category.

![](https://gblobscdn.gitbook.com/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-M5_geFCv5JS8dCTb63m%2F-M5_rC4ysd9SEO5yWR02%2Flanguage%20distribution%20across%20projects.png?alt=media&token=5abae338-96bd-48ce-85df-46436e8d9817)

Language Distribution Across Projects

The value in the middle of the doughnut chart shows the total number of projects. Mouse over a color to see the language name, and its percentage of usage.

### Transitive Dependencies <a id="transitive-dependencies"></a>

Represents a bar graph that groups all the projects based on their number of dependencies \(shown in X-axis\), and shows total number of projects in Y-axis. In the following is example, 16 represents the number of projects whose dependency count is between 0 to 50:

![](https://gblobscdn.gitbook.com/assets%2F-LuGl2w4LzPpYJ8jx5ae%2F-M4OVPboTRaYLtTdIdZU%2F-M4OYHvsjkv9fu_htHtq%2Ftransitive%20dependencies.png?alt=media&token=642266af-e2e6-4582-9904-c42a16793b80)

Transitive Dependencies

**Note:** Depending upon the dependency numbers for projects, the dependency range \(in X-axis\) varies for better representation. For example, the frequency buckets or dependency number might show 0-10, 11-20, 21-30, 31-40, and so on.

### TOTAL NO. OF PROJECTS ACROSS MAXIMUM STACK DEPTH <a id="total-no-of-projects-across-maximum-stack-depth"></a>

Shows colored bubbles that represents the total number of projects in each bubble based on the stack depth of the packages in the project's repositories.For example, projects whose packages have stack depth of 2 will be counted and grouped in the green bubble that shows 0-2 maximum stack depth, and so on.

![](https://gblobscdn.gitbook.com/assets%2F-LuGl2w4LzPpYJ8jx5ae%2F-M4OidvKHjvDlmNs2RpF%2F-M4OxXOgsYW6NAv38QEl%2Fpackage%20levels.png?alt=media&token=b4c10175-f6d4-444c-a13a-1886d323acd0)

package levels

![](https://gblobscdn.gitbook.com/assets%2F-LuGl2w4LzPpYJ8jx5ae%2F-M4OidvKHjvDlmNs2RpF%2F-M4OyXlo4I0e-XMX84cG%2Ftotal%20number%20of%20projects%20across%20maximum%20stack%20depth.png?alt=media&token=174f121e-8d1f-4ce7-92e4-f4cab42fe4c8)

total number of projects across maximum stack depth

### ACTIVITY LOG <a id="activity-log"></a>

Shows activities for your projects, such as project name, activity status for your project repositories, and date and time of activity. Click ![](https://firebasestorage.googleapis.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LuGl2w4LzPpYJ8jx5ae%2F-M3oihXxduPrX3NHZkqL%2F-M3ontG_VuUDGoBmGW2x%2Fall%20projects%20button.png?alt=media&token=08937bbb-648f-4102-a519-c83e7f9866e4) and select a project of interest from the drop-down list to view activities for the project.

### PROJECTS WITH VULNERABILITY DETECTION <a id="projects-with-vulnerability-detection"></a>

Shows list of projects that have vulnerabilities. By default, card view is shown. Click ![](https://firebasestorage.googleapis.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LuGl2w4LzPpYJ8jx5ae%2F-M3osOFppq0ebnkHwNMw%2F-M3otI3kSNulwXtaWgh2%2Ftoggle%20list%20view%20button.png?alt=media&token=3cb00a10-83aa-4426-8f2e-b46e8f81364d) for list view of your projects. Each project card shows the following details for a project:

* project name, logo, and description
* **Vulnerability Report:** shows number of issues based on severity level, fixable issues for each severity, total number of issues and total number of fixable issues.
* **Updated:** Date and time of last scan for the project repositories in MM DD YYYY format along with the timezone name.
* Click **View Details** to know more about [vulnerability details](https://docs.linuxfoundation.org/community-bridge/projects#security) of the project.
* Click **Show more** to view more project cards

​

