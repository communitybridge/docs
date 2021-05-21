# Release Notes

Release notes for the EasyCLA backend and APIs can be found at [https://github.com/communitybridge/easycla/releases](https://github.com/communitybridge/easycla/releases).

Release notes for the EasyCLA Contributor Console can be found at [https://github.com/communitybridge/easycla-contributor-console/releases](https://github.com/communitybridge/easycla-contributor-console/releases)

## Known Issues

The following issues are known to be present in the v2.0.0 release of EasyCLA:

* [Two-Level Project Hierarchies](release-notes.md#two-level-project-hierarchies)
* [Auto-Branch Protection](release-notes.md#auto-branch-protection)
* [Organization Association](release-notes.md#organization-association)

### Two-Level Project Hierarchies

EasyCLA v2.0.0 supports projects with a parent-child model of at most two hierarchy levels. The following is an example:

* Parent Project
  * Child Project

Some projects may have deeper nesting of subprojects. Future releases will support nested project relationships.

### Auto-Branch Protection

Auto-Branch Protection only protects a repo's default git branch. Non-default branches are not currently auto-configured for EasyCLA protection. Currently, GitHub organization owners must manually set up branch protection rules for non-default branches.

### Organization Association

Currently, user roles in EasyCLA can only be associated with a single company or organization at a time.



EasyCLA sends email notification to Project Managers regarding any changes to the repositories. EasyCLA takes the following actions for different events, and sends email notifications to project managers regarding the respective actions:

* **Repository Renamed:** EasyCLA updates GitHub repository table entry to match the new GitHub repository name.
* **Repository Archived:** EasyCLA takes no action, however notifies the project manager that the repository is archived.
* **Repository Deleted:** EasyCLA ****disables the repository.
* **Repository Moved to a Different Organization:** 
  * If ****an EasyCLA enabled repository is moved from one organization to another within the same CLA Group, EasyCLA simply notifies the project manager about the action.
  * If ****a repository is moved from one organization to another where EasyCLA is NOT configured or the CLA Group is different, EasyCLA disables the repository.

