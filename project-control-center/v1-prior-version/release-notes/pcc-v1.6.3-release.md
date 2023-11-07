# PCC V1.6.3 Release

Release Date: 24/January/2023

## PCC Overview

Project Control Center (PCC) is a platform that allows project administrators to set up the projects when they get associated with The Linux Foundation. You can set up the projects to use various services that are provided by The Linux Foundation.

PCC assists you in onboarding an open source project with great ease. Project Control Center helps you get started quickly by providing all the support that you need with self-service configuration for governance, membership, IT, developer and collaboration tools, documentation, and community roles. You can read more about PCC by visiting our [website](https://lfx.linuxfoundation.org/tools/project-control-center).

Some of the prominent features of PCC are listed in the following list:

* PCC Dashboard
* Creating Projects and Sub Projects
* Generic setup services
* IT services
* Tools Onboarding

## New Features, Updates and Bug Fixes

This sections provides you with list of new features, updates and bug fixes for this release.

### New Features

The following list provides you an overview of new features implemented in this release:

**NA**

### Updates

The following list provides new updates to the existing features:&#x20;

* Insights - Updated GitHub repositories to be sorted by repository name
* Committee - Added committee voting status on the committee table
* Cypress - Removed login requirement for end-to-end testing and stub remaining endpoints
* EasyCLA - Added ability to disassociate GitHub organization from EasyCLA
* EasyCLA - Removed GitLab project added under grandchild from CLA group
* Mailing List - Added ability to list mailing lists that are part of the current projects' subproject in the mailing lists table

### Bug Fixes

The following list provides you the bug fixes that are applied in this release:

* Committees - Fixed remaining committee routes that were not updated to reflect the new navigation structure
* Project Definition - Fixed issue where the parent project field was incorrectly being set to required in certain scenarios
* Project Details - Truncate project details website when text exceeds the allowed width
* Mailing List - Fixed issue where users were unable to navigate from the mailing lists page
* Mailing List - Fixed separator alignment issue on the mailing list table
* Mailing List - Fixed bug where Voting Status and Role columns were not displayed when committee voting was enabled
* Mailing List - Fixed remaining mailing lists routes that were not updated to reflect the new navigation structure
* Meeting Management - Fixed width issue with time picker on meeting management
* Meeting Management - Fixed issue where committee members were not filtered based on voting status while managing participants
* Meeting Management - Fixed issue where the current user is added to meetings was being duplicated in meeting participants
* Meeting Management - Fixed navigation bug where users were not able to view legacy Zoom users
* Source Control - Fixed refreshing of the page when a GitHub organization is added for the first time, or when it is removed
* EasyCLA - Fixed organization status colors based on the organization's connection status
* Insights - Fixed GitHub updated repositories visibility when viewing a filtered list

## Known Issues <a href="#lfxprojectcontrolcenter-pcc-releasenotes-knownissues" id="lfxprojectcontrolcenter-pcc-releasenotes-knownissues"></a>

**NA**

## Support Information <a href="#lfxprojectcontrolcenter-pcc-releasenotes-supportinformation" id="lfxprojectcontrolcenter-pcc-releasenotes-supportinformation"></a>

You can visit the following links for more information on PCC:

* [PCC Website](https://lfx.linuxfoundation.org/tools/project-control-center)
* [PCC Documentation](https://docs.linuxfoundation.org/lfx/project-control-center-pre-release)
* [Support Forum](https://community.lfx.dev)
* [General Discussions](https://community.lfx.dev/c/lfx-general-discussion/72)
* [LFX Tool Help](https://community.lfx.dev/c/help/62)
* [Content & Articles](https://community.lfx.dev/c/content-articles/58)
* [Suggestions & Requests](https://community.lfx.dev/c/suggestion-box/70)
