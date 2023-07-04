# Commit Contributors

The dashboard shows the total number of unique commit contributors across all monitored repositories during the selected time period. Commit contributors can author and co-author a commit that is visible on GitHub.

{% hint style="info" %}
For the current release, GitHub and Git are the two data sources used to calculate contributors across all monitored repositories during the selected time period.

The analysis is done based on the following parameters for the selected period:

* The impact by the contributors is calculated based on the number of commits in all the monitored repositories. Distinct SHAs are calculated as commit IDs.
* Project IDs and subproject IDs are selected from the repositories.
{% endhint %}

Commits will appear on the contributions graph if they meet all of the following conditions:

* The commits were made within the past year.
* The email address used for the commits is associated with your GitHub account.

The bar chart shows the total commit contributors and the rate of change percentage for the selected time period. Hover over the chart to see the commit contributors for that particular month.

<figure><img src="../../../../../../.gitbook/assets/Commit Contributors (1).png" alt=""><figcaption><p>Commit contributors</p></figcaption></figure>

To analyze the contributor dashboard, click CONTRIBUTOR LEADERSHIP at the bottom of the chart that takes you to the **Community Management > People** dashboard.
