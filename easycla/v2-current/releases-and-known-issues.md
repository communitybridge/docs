# Releases and Known Issues

## Known Issues

The following issues are known to be present in the v2.0.0 release of EasyCLA:

* [Auto-Branch Protection](releases-and-known-issues.md#auto-branch-protection)
* [Organization Association](releases-and-known-issues.md#organization-association)

### Auto-Branch Protection

Auto-Branch Protection only protects a repo's default git branch. Non-default branches are not currently auto-configured for EasyCLA protection. Currently, GitHub/GitLab organization owners must manually set up branch protection rules for non-default branches.

### Organization Association

Currently, user roles in EasyCLA can only be associated with a single company or organization at a time.

## Releases

Release notes for the EasyCLA backend and APIs can be found at [https://github.com/communitybridge/easycla/releases](https://github.com/communitybridge/easycla/releases).

Release notes for the EasyCLA Contributor Console can be found at [https://github.com/communitybridge/easycla-contributor-console/releases](https://github.com/communitybridge/easycla-contributor-console/releases)

EasyCLA V2.0 supports projects with a parent-child model of any number of hierarchy levels without any limit in the depth of the hierarchy. The following is an example:

* Parent Project
  * Child Project
    * Grand Child Project
      *   Great Grand Child Project

          * Great-Great Grand Child Project

          &#x20;       ….
