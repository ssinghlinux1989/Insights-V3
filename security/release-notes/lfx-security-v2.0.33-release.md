# LFX Security V2.0.33 Release

Release Date 08/April/2022

## New Features and Bug Fixes

This sections provides you with list of new features and bug fixes for this release.

* Added Datalake Provider Interface - Abstracted Vendor vs Datalake queries
* Updated BB Vendor Repo Scan Status Queries -> migrated from GET to POST with payload to support larger queries
* Updated GitHub Webhook validation logic - tested/validated webhook secrets
* Added Redis Caching on a number of API calls to increase query performance (local, vendor, and datalake sources). Added cache invalidation logic
* Added Query Logic support for Global query on the v2 UX (search by project, CVE, CWE, GHSA, Language)
* Expanded queries on the vulnerabilities page to support filtering for issue type/title, severity, CVE, CWE, GHSA, state (fixed/not fixed)
* Updated API for BB non-inclusive language notifications (added logic to work with vendor and datalake, track notifications locally)

## Bug Fixes

NA

## Known Issues&#x20;

**NA**

