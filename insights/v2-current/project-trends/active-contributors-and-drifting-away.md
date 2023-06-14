# Active Contributors and Drifting Away

The dashboard shows the following two metrics:

If you want to go back to the dashboard from any other screen, simply click the tab on the **Dashboard** to toggle between dashboards.

{% hint style="info" %}
For the current release, GitHub and Git are the two data sources used to calculate contributors across all monitored repositories during the selected time period.
{% endhint %}

### Active Contributors

The bar chart shows the data of the active contributors who have actively contributed across all projects.

The annotation block shows the average count of active contributors in percent increase or decrease compared to the same metrics for the previous period.

The observations section shows the following information:

* The highest growth in the number of active contributors in the selected period.
* The percentage change as compared to the previous period.

### Drifting Away

The bar chart shows the data of the drifting away contributors who were active in the last year but did not contribute across commits, PRs, or issues in the last 6 months.

The annotation block shows the average count of drifting away contributors in percent increase or decrease compared to the same metrics for the previous period. The percentage increase or decrease is calculated for the same time period by comparing the drifting contributor count at the start and end of the selected time period.

{% hint style="info" %}
The analysis is done based on the following parameters:

* Distinct contributor ID counts as drifting away count selected from contribution type, contribution role, user id, identity id, contributor id, organization id, commit id, etc.
* Project IDs and subproject IDs are selected from the repositories.
{% endhint %}

For more information, see [People Analytics](../all-projects/community-analytics/people-analytics.md).
