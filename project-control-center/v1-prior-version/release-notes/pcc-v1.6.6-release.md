# PCC V1.6.6 Release

Release Date: 27/March/2023

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

* Committees - Updated table to allow the user to click the member's name to view and edit committee members to reduce clicks
* Committees - Updated committee members table to allow users to set numbers of rows loaded per page
* Committees - Added ability to manage committee mailing lists directly from the committee's page
* Meeting Management - Updated UI/UX for managing a meeting where the meeting details and participants are now on a single page

### Updates

The following list provides new updates to the existing features:&#x20;

* Cloud Providers - Updated text describing AWS billing reflect that costs will be charged for the current month's costs up to today.
* PCC - Fixed a bug where searching for projects was showing archived projects while the archive toggle was turned off
* Mailing Lists - Updated error handling when adding a new mailing list and it fails due to primary domain being a delegated domain

### Bug Fixes

The following list provides you the bug fixes that are applied in this release:

* PCC - Fixed a bug where our issue where our in-memory cache for the BFF was not working properly in production\
  Meetings - Fixed query for getting past meetings where recordings were not visible for past meetings
* Meetings - Fixed recurring dropdown options on manage meeting with custom selection and you the user changes the start date
* Mailing Lists - Fixed column separator alignment of the secondary subscribed email per user in the mailing list
* Mailing Lists - Fixed a bug causing specific lists to not load due to a member missing user\_id field
* Project Details - Fixed description text UI overflowing into next element
* EasyCLA - Fixed issue where grandchild projects are allowed to enroll in foundation CLA group

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
