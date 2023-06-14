# LOC Added and LOC Deleted

### LOC Added

The dashboard displays a bar that shows a periodic increase or decrease in the number of lines of code added across all unique commits during the selected time period.&#x20;

Line-of-code data is obtained from the GitHub repositories, where you can see a list of all the contributors to the repositories and how many lines they have added and removed.

{% hint style="info" %}
For the current release, GitHub and Git are the two data sources used to calculate commits and pull requests. GitHub is the data source to calculate LOCs.&#x20;
{% endhint %}

The annotation block displays:

* The average number of lines of code added across all unique commits (calculated based on a unique ID (which is "SHA" or "hash") that allows you to keep a record of the specific changes committed along with when and who made those changes.
* The rate of change (in percentage) in the number of LOC added from the previous time period to the current (selected) time period.

### LOC Deleted

The dashboard displays a bar that shows a periodic increase or decrease in the number of lines of code deleted across all unique commits during the selected time period.&#x20;

* The average number of lines of code deleted across all unique commits (calculated based on a unique ID (which is "SHA" or "hash") that allows you to keep a record of the specific changes committed along with when and who made those changes.
* The rate of change (in percentage) in the number of LOC deleted from the previous time period to the current (selected) time period.

