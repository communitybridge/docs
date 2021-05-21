# Release Notes

Release notes for the EasyCLA backend and APIs can be found at [https://github.com/communitybridge/easycla/releases](https://github.com/communitybridge/easycla/releases).

Release notes for the EasyCLA Contributor Console can be found at [https://github.com/communitybridge/easycla-contributor-console/releases](https://github.com/communitybridge/easycla-contributor-console/releases)

## Known Issues

The following issues are known to be present in the v2.0.0 release of EasyCLA:

### Two-Level Project Hierarchies

EasyCLA v2.0.0 supports projects with a parent-child model of at most two hierarchy levels. The following is an example:

* Parent Project
  * Child Project

Some projects may have deeper nesting of subprojects. Future releases will support nested project relationships.

### Auto-Branch Protection

Auto-Branch Protection only protects a repo's default git branch. Non-default branches are not currently auto-configured for EasyCLA protection. Currently, GitHub organization owners must manually set up branch protection rules for non-default branches.

### Organization Association

Currently, user roles in EasyCLA can only be associated with a single company or organization at a time.

