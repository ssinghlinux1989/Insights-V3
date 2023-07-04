# Pipeline

The dashboard displays the complete commit to merge pipeline, showing the total count of the number of commits pushed, change requests created, change requests reviewed, approved, and finally merged.

The funnel view shows the total count of unique commits (pull requests or changesets) pushed, submitted, reviewed, approved and merged across all projects during the selected time range. This indicates how many commits are actually merged out of the total number of pushed commits, and how many are pending to be approved and merged.

The observation section shows the following data in each slide:

* The percentage of total changes that were merged without any approval during the selected time period.
* The percentage of total changes submitted for review that were approved during the selected time period.
* The percentage of risky changes that were caught in the review process and filtered from being merged during the selected time period.
* The percentage of change requests reviewed that were merged into the upstream branch during the selected time period.
* On an average, X number of  iterations were required to close change requests.

`An iteration is defined as the number of commits pushed for a single PR or the number of patchsets for a single changeset after the PR/changest has been created.`



For more information, see [Commits](../all-projects/community-analytics/people-analytics.md#commits).
