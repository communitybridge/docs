# LFX Security V2.0.29 Release

Release Date:18/March/2022

## LFX Security Overview&#x20;

LFX Security provides a strong security for you open source code. LFX provides a clear view into the security of a given project and enables developers to identify and resolve vulnerabilities quickly and easily.

Some of the prominent features for LFX Security are:

* Automated vulnerability scanning
* License compliance management&#x20;
* Centralized project security dashboard
* Fix Recommendations
* Contextual vulnerability reporting
* Detailed Dependency Tree
* Neutral to Source Control Systems
* Release Version Contextualization
* Code secrets detection&#x20;
* Identification of Non Inclusive language in the code

## New Features and Bug Fixes

This sections provides you with list of new features and bug fixes for this release.&#x20;

### New Features&#x20;

The following list provides you an overview of new features implemented in this release:

* BluBracket API Refactor - separated the vendor APIs and the datalake APIs into separate folders
* Implemented LFXSEC-1828:Datalake Integration - API to Query Datalake Dependencies
* Added Additional Project Statistics Checks
* Added Markdown Scheduler Output Format for printing pending jobs/scheduled tags CLI

### Bug Fixes

The following list provides you the bug fixes that are applied in this release:

* BluBracket Org Lookup Fix - resolve an issue when a child project code secrets are queried and the organization information is stored with the parent. Added logic to cross-check the parent's org information
* Fixed Snyk Projects not Found and Datalake fetch all dependencies Issues
* Updated Project Stats CLI - cleaned up command-line flags and usage
* Resolved Bug in the Vulnerabilities DL query related to the repository ID - now use the DL repo ID hashing function
* Update code\_secrets\_details of Project statistics of project and parent projects
* Resolved \[#LFXSEC-1896] Feature/Datalake Integration
* Resolved Project Stats - Code Secrets Details Encoding Error
* Resolved Publish Stats Empty Message Issue
* Resolved Additional Nil References After Service Composition Refactor, Resolved CSV Nil Pointer Issue

## Known Issues

**NA**

## **Support Information**&#x20;

You can visit the following links for more information on LFX Security:

* [LFX Security Website](https://lfx.linuxfoundation.org/tools/security/)
* [LFX Security Documentation](https://docs.linuxfoundation.org/lfx/security)&#x20;
* [Support Forum](https://community.lfx.dev)
* [General Discussions](https://community.lfx.dev/c/lfx-general-discussion/72)
* [LFX Tool Help](https://community.lfx.dev/c/help/62)
* [Content & Articles](https://community.lfx.dev/c/content-articles/58)
* [Suggestions & Requests](https://community.lfx.dev/c/suggestion-box/70)
