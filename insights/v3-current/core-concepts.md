# Core Concepts

To see the detailed definition, click > to expand.

<details>

<summary>Identity</summary>

Identity is coming from connectors and is a kind of user account in a specific data source.

This can be for example somebody's GitHub profile, git identity, Slack account, etc.

Identity can be claimed by a [user](core-concepts.md#user). A single [user](core-concepts.md#user) can have multiple identities in different data sources or even multiple identities of the same data source type.

Identity is unclaimed if it is not yet assigned to any user.

Identity can be marked as bot.

Identity has a data source type and the following properties:

* Data source.
* Is a bot flag.
* Email address (optional).
* Name (optional).
* User name (optional).
* Avatar URL (optional).

</details>

<details>

<summary>User</summary>

The user is an LFX profile. The user will have an LFID and can claim [identities](core-concepts.md#identity).

</details>

<details>

<summary>Contributor</summary>

A contributor is defined as someone who makes a [contribution](core-concepts.md#contributions).

A contributor is either an unclaimed [identity ](core-concepts.md#identity)or a set of claimed identities (under a single [user](core-concepts.md#user)).

</details>

<details>

<summary>Contributions</summary>

Contribution is a kind of activity depending on the data source type.

We only consider activities on repositories that are not disabled and have Insights enabled.

Currently, the contribution is defined as any of the following:

* Authoring, Co-Authoring, or committing a git commit.
* Creating/editing confluence page or attachment.
* Approving/Reviewing a Gerrit changeset/approval.
* Creating/Closing/Merging/Editing a Gerrit changeset.
* Adding/Editing a Gerrit comment.
* Creating/Committing a gerrit patchset.
* Creating/Closing/Editing a Github/Jira/Bugzilla issue.
* Commenting on a Gerrit/Jira/Bugzilla issue.
* GitHub/Jira/Buzzilla assignment.
* Creating/Closing/Merging/Editing a GitHub pull request.
* GitHub pull request assignment.
* Commenting on a GitHub pull request.
* Editing/Deleting a GitHub comment.
* Reviewing/Approving/Rejecting/Requesting changes on a GitHub pull request.
* Being requested a GitHub pull request reviewer.
* Pusher
* Watcher

**Note:** Various reaction types such as GitHub reaction to comment/Issue/PR as contributions are not counted.

</details>

<details>

<summary>Contribution role</summary>



</details>

<details>

<summary>New Contributor</summary>

A new contributor is someone who contributes the first [contribution](https://github.com/LF-Engineering/lfx-insights-ui/blob/main/DEFINITIONS.md#contribution) in a specific time range and can also be in a particular project.

This means that a given [contributor](https://github.com/LF-Engineering/lfx-insights-ui/blob/main/DEFINITIONS.md#contributor) should not have any [contributions](https://github.com/LF-Engineering/lfx-insights-ui/blob/main/DEFINITIONS.md#contribution) before the current time range start date (for a specific project, we consider a given project's new contributors).

</details>

<details>

<summary>User company affiliation</summary>

Users can have multiple company affiliations. Each affiliation has:

* Date range affiliation starts on a given date and ends on a given date. Both the start and end dates can be unlimited.
* Project affiliations are specific to a project, so users can have different company affiliations for different projects.
* Organization.

User affiliations are defined at the user level, so they apply to all claimed identities of users.

</details>

<details>

<summary>Virtual affiliation</summary>

Virtual affiliations are defined only for unclaimed non-bot identities, so an identity cannot be a bot and cannot be linked to a user.

An identity is virtually affiliated with a company when the [identity](https://github.com/LF-Engineering/lfx-insights-ui/blob/main/DEFINITIONS.md#identity)'s email address domain matches the organization domain defined in a special _org\_domain_ table.

Those _virtual affiliations_ are not project specific and have no time ranges.

They are just helpers to allow finding more company affiliations.

</details>

<details>

<summary>Repository</summary>



</details>
