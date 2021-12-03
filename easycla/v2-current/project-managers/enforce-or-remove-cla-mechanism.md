# Enforce or Remove CLA Mechanism

Before you enable Git repositories for CLA check or remove them from CLA mechanism, you must add the [GitHub](add-and-manage-github-organizations.md#add-github-organization) or [Gerrit](add-and-manage-gerrit-organizations.md#add-gerrit-organization) or [GitLab](add-and-manage-gitlab-groups.md#add-gitlab-groups) organizations. You can perform the following activities with EasyCLA:

1\. Sign in to the [Project Control Center](https://projectadmin.lfx.linuxfoundation.org).

2\. Click a **project** of interest.

3\. Scroll down to **Tools Status** section, and click **EasyCLA**.

![Tools Status](https://docs.linuxfoundation.org/\~/files/v0/b/gitbook-28427.appspot.com/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-MYL76gRXl7OC0uMczgL%2F-MYL8B6xQwTBjV-bvxBl%2Ftools%20status%20tab.png?alt=media\&token=c1fee7b7-6cf2-4e79-8796-d311043d987e)

4\. Select the CLA group to which you have added the project.5. Click **Manage** next to the project for which you want to manage repositories.

* ​[Enforce CLA for GitHub Repositories](enforce-or-remove-cla-mechanism.md#enforce-or-remove-cla-mechanism-from-github-repositories)​
* ​[Enforce CLA for Gerrit Repositories​](enforce-or-remove-cla-mechanism.md#enforce-cla-mechanism-for-gerrit-repositories)
* [​Enforce CLA for GitLab Projects​](enforce-or-remove-cla-mechanism.md#enforce-or-remove-cla-mechanism-from-gitlab-projects)

## Enforce or Remove CLA Mechanism from GitHub Repositories <a href="#enforce-or-remove-cla-mechanism-from-github-repositories" id="enforce-or-remove-cla-mechanism-from-github-repositories"></a>

1. Under GitHub, select the added organization for which you want to manage repositories.
2. Turn on or turn off the **Enforce CLA** toggle key to enforce or remove all the repositories from CLA mechanism at a time.
3. To enforce CLA for individual repositories, select the check box next to a repository, and click **Save**.

![Add or Remove Git Repositories](https://docs.linuxfoundation.org/\~/files/v0/b/gitbook-28427.appspot.com/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-MYOFDf7emdfValpgSIU%2F-MYOQrXeJFMwbgPdPWwu%2Fadd%20or%20remove%20git%20repositories.png?alt=media\&token=beaafa41-94ed-4bc7-8e3e-096d355f5944)

## Enforce CLA Mechanism for Gerrit Repositories <a href="#enforce-cla-mechanism-for-gerrit-repositories" id="enforce-cla-mechanism-for-gerrit-repositories"></a>

After you add a [Gerrit organization](add-and-manage-gerrit-organizations.md#add-gerrit-organization), by default all of its repositories are CLA enabled. You cannot disable CLA for an individual Gerrit repository. However, you can [disassociate the Gerrit organization](add-and-manage-gerrit-organizations.md#disassociate-gerrit-organization) to disable CLA for the organization and all of its repositories.

![Gerrit Instance showing all its repositories CLA enabled](https://docs.linuxfoundation.org/\~/files/v0/b/gitbook-28427.appspot.com/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-MHLgxt0yyY5C8JVm7Sh%2F-MHLi3TkO\_YVgD5b4YJ9%2Fgerrit%20instances.png?alt=media\&token=94d94daa-c824-407f-b604-3ca336b28aa2)

## Enforce or Remove CLA Mechanism from GitLab Projects <a href="#enforce-or-remove-cla-mechanism-from-gitlab-projects" id="enforce-or-remove-cla-mechanism-from-gitlab-projects"></a>

1. Under GitLab, select the added group for which you want to manage projects.
2. Turn on or turn off the **Enforce CLA** toggle key to enforce or remove all the projects from CLA mechanism at a time.
3. To enforce or remove CLA from individual projects, turn on the toggle key next to a project, and click **Yes**.

![Enforce or Remove CLA from GitLab Projects](https://docs.linuxfoundation.org/\~/files/v0/b/gitbook-28427.appspot.com/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-MitRJvK43ovpq45P2Tx%2F-Mitc3gRHMxyu\_fHtEaM%2Fenforce%20or%20remove%20CLA%20for%20GitLab.png?alt=media\&token=ee955a48-cf64-43b4-afcf-d34d45fbf742)
