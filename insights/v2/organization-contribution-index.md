# Organization Contribution Index

An organization that meets the criteria to be an active organization is one that is linked to an active contributor. If a contributor has multiple affiliations, each organization will qualify as a contributing organization.

The **Organization Contribution Index** page provides analytics of organizational performance for different open-source projects hosted by the Linux Foundation. You can view the following insights:

* How many technical contributors are actively contributing to the open-source projects of the organization?
* How active or inactive an organization is in contributing code to the projects?
* The organizations that are contributing more to the open source community and many other details.

It helps the community to track the organizations that are most actively engaged with different projects of the Linux Foundation in contributing code and participating in chats and emails.

{% hint style="info" %}


For the current release, GitHub and Git are the two data sources supported across all monitored repositories during the selected time period.

The analysis is done based on the following parameters:

* The organization's; name, ID, logo, industry type, and the total number of employees.
* Technical contributor ID, commit SHAs, email IDs, message IDs, etc.
* Project IDs and the number of projects selected from the repositories.
{% endhint %}

The following are the various performance-related components displayed on the O**rganization Contribution Index** page:

### Organization Leaderboard

It displays a table that shows a paginated list of organizations that contribute code and participate in emails and chat during the selected time period across all the projects onboarded to LFX Insights. The maximum number of organizations displayed on a single page is 10. The following are the different components of the table:

{% hint style="info" %}
By default, the table is filtered by the number of _commits,_ and industry type as _All._
{% endhint %}

1. **Search Organizations:** you can search by the organization name across all the organizations that are contributing during the selected time period.
2. **Industry:** you can filter the table by different industries from the drop-down list: communication equipment, Diversified Financial Services, and Education Services. The default value is _All_.
3. **Order By:** This lets you filter the table by commits and technical contributors. The default value is commits.
4. **Organization Name:** Displays the name of the organization that contributes code across all projects onboarded by the Linux Foundation. Expand the organization name to view the following information:&#x20;
   * **Projects Engaged:** The total number of projects the organization has been engaged in, by contributing towards code, documentation, or participating in email and chat conversations, from the time the organization joined the Linux Foundation.
   * **Size of the Organization:** Displays the total number of employees of the organization.
   * **Technical Contributions:**&#x20;
     * **Total Contributors:** This metric displays the aggregated count of the [technical contributors](broken-reference) across all projects and for all time. It also shows the rate of change (in percentage) in the total number of contributors from the start of the selected time period to the end of the selected time period.&#x20;
     * **Active Contributors:** This metric displays the total number of [active technical contributors](broken-reference) for the selected time period. It also shows the percentage change in the active contributor count (of an organization) for the selected time period compared to the preceding time period.
     * **Commits:** Number of unique commits (calculated based on unique hashes associated with a commit). It also shows the percentage change reflects the change in the number of commits during the selected time period compared to the preceding period.
     * **PRs:** Sum of PRs submitted, reviewed, merged, and commented on across all PR activities during the selected time period. The percentage change reflects the change in the sum of PR activities compared to the preceding period.
     * **Issues:** Sum of issues reported, commented on, and resolved across all issue activities during the selected time period. The percentage change reflects the change in the issue activities compared to the preceding period.
5. **Organization Logo:** Displays a unique logo of the organization to quickly identify the organization.
6. **Industry:** The industry type that the organization belongs to.
7. **Technical Contributors:** The total number of unique individuals (based on their UUID) within the organization who participate in performing code-related activities.&#x20;
8. **Commits:** The total number of unique commits (calculated based on unique hashes associated with a commit) made by the organization.

### Active Organization by Industry

{% hint style="info" %}
**Note:** An organization is considered **Active** if it is affiliated with an active contributor. If an active contributor has multiple organization affiliations, each organization is considered a contributing organization.
{% endhint %}

This metric shows a doughnut chart that displays:

* The top 10 technology sectors that active organizations are associated with. Hover over a color to view the number of organizations associated with the technology.
* The total number of active organizations during the selected time period.
* Increment or decrement rate (in percentage) of active organizations in the selected time period compared to the preceding time period.

### Active Organization by Size

The total number of active organizations is analyzed by different cohorts according to the size of the organizations as defined by the total number of employees.

{% hint style="info" %}
**Note:** Size refers to the number of employees in the organization.
{% endhint %}



###

