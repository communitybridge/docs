# Release Notes

## Known Issues

Following are the known issues in v2.0.0 release of EasyCLA:

#### Two-Level Project Hierarchies

EasyCLA v2.0.0 supports projects with only two levels of hierarchies. Following is an example:

* Parent Project
  * Child Project

Future releases will support nested project relationships.

#### Auto-Branch Protection 

Auto-Branch Protection only protects the default git branch. Non-default branches are not auto-configured for EasyCLA protection. GitHub organization owners must manually setup branch protection rules for non-default branches.

#### Organization Association

Corporate users can only be associated with a single company.

