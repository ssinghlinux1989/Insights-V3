# Pull Request Pipeline

Pull Request (PR) Pipeline provides various insights related to the PRs carried out for the open source project. Pull Request Pipeline provides various graphs that provides you information on PRs analysis.  There are various graphs such as:

* Pull Request History&#x20;
* Request Pipeline&#x20;
* Cycle Time&#x20;
* Pull Request Trends&#x20;
* Contributor Type&#x20;
* Active Submitters&#x20;
* Time to Merge&#x20;
* Time in Review&#x20;
* New Contributor Efficiency&#x20;
* Top 10 Contributors&#x20;
* Top 10 Organizations&#x20;

## Filter Data by Time Range

You can filter the data related to PR as per your desired date range. By default, time range is **Past 1 Year**. You can change the time range for a certain time period. For more information, refer [Date Range](https://docs.linuxfoundation.org/lfx/insights/v2-current/project-trends/filter-data-by-time-range).&#x20;

## Filters

You can filter the PRs using various other filter like:

* Filter by&#x20;
  * Repository&#x20;
  * Repository Tags
* Searching by various individual repositories &#x20;
* Sub Projects

{% hint style="info" %}
Every dashboard has a filter at the top of the dashboard to select either **Repositories or Repository Tags**. \
\
A Repository tag is a logical group created by clubbing two or more repositories under an org. One repository can belong to multiple repository groups. A repository tag is unique to a project.
{% endhint %}

<figure><img src="../../../../../.gitbook/assets/PR Filter.gif" alt=""><figcaption><p>PR Filter</p></figcaption></figure>

## Download of Charts&#x20;

You can download all the charts that are displayed in the PR Pipeline page by click of the download <img src="../../../../../.gitbook/assets/Dow Icon.png" alt="" data-size="line">icon that is provided on top of all the charts. The downloaded chart is saved on your local drive in the PNG format.&#x20;

## Total Number of Pull Requests

This line graph provides the count of the total number of PRs submitted and merged aggregated for all time over the selected time period.&#x20;

<figure><img src="../../../../../.gitbook/assets/PR History.png" alt=""><figcaption><p>Total Number of PR</p></figcaption></figure>

## Observations&#x20;

Observations window provides various observations carried out on the Pull Request Pipeline. Some of the observations that are displayed are listed in the following list:

* The total number of PRs submitted increased/decreased by X% during the ${selected time period}.
* An average of X PRs were merged during the ${selected time period}.
* The total number of PRs merged increased/decreased by X% during the ${selected time period}.
* **X**% of total changes were merged without any approval during the last ${selected time period}.

## Request Pipeline

This funnel chart provides you the total number of code change requests in the form of PRs or changesets submitted, reviewed, accepted and merged during the selected time period.

{% hint style="info" %}
GitHub's accepted/approved state configured differently for every repository. This "Approved" metric is counted based on at least one review with "Accepted state".

* **Submitted** - Number of PRs created/submitted during the given time range + the number of PRs still in open at the end of the time period.
* **Reviewed** - Number of PRs with at least one Review (comment or approval or requested changes). The review must be done during the selected time period.
* **Accepted** - Number of PRs with at least one approval. The approval must be done during the selected time period.
* **Merged** - Number of PRs merged (not rejected).
{% endhint %}

{% hint style="info" %}
For Gerrit:

* **Submitted** - Number of Changesets created/submitted the given time range + number of changesets still in open
* **Reviewed** - Number of chanegstes with at least one Review (comment or review value +1, +2, -1, -2)
* **Accepted** - Number of changesets with at least one approval (review value +1, +2)
* **Merged** - Number of changesets merged/closed (not -2)
{% endhint %}

<figure><img src="../../../../../.gitbook/assets/Request Pipeline.png" alt=""><figcaption><p>Request Pipeline </p></figcaption></figure>

## Cycle Time

This funnel chart provides you the sum of the average time it takes in each step of the PR/changeset cycle.&#x20;

The annotation block shows the total Average PR Cycle time i.e. the sum of the averages for each stage. It also shows the percentage change compared to previous period.

{% hint style="info" %}
* **Waiting for Review -** Shows the average of the time between a PR is submitted/created and time to get the first review\_comment or review\_approval or review\_requested\_chages for all PRs merged or closed during the selected time period.&#x20;
* **In Review** - Shows the average of the time a PR received its first review to the time a PR received its first approval for all the PRs merged or closed during the selected time period.
* **In Approval** - Shows the average of the time a PR received its first approval to the time a PR was merged or closed for all the PRs merged or closed during the selected time period.
{% endhint %}

<figure><img src="../../../../../.gitbook/assets/Cycle Time.png" alt=""><figcaption><p>Cycle Time </p></figcaption></figure>

## Pull Request Trends&#x20;

This bar graph provides the count of the total number of PRs submitted and merged during the selected time period.

<figure><img src="../../../../../.gitbook/assets/PR Trends.png" alt=""><figcaption><p>PR Trends</p></figcaption></figure>

## Contributor Type

This donut chart provides the analysis of code change request contributors by  reviewers and submitters.

{% hint style="info" %}
* **Total PR contributors** are unique identities who are PR submitters, PR reviewers (review\_comment, review\_requested\_changes, review\_approval) and PR mergers.
* **PR submitters** are strictly those who have submitted at least 1 PR during the selected time period.
* **PR reviewers** are strictly those (can be submitters as well) who have reviewed at least one PR during the selected time period.
{% endhint %}

<figure><img src="../../../../../.gitbook/assets/Cont type.png" alt=""><figcaption><p>Contributor Type </p></figcaption></figure>

## Active Submitters

This bar graph provides you the count of the total number of unique PR submitters analyzed by cohorts of existing and new submitters contributing during the selected time period.

{% hint style="info" %}
* New PR Submitters are also Active.
* New submitters are strictly those identities or profiles who have submitted PR for the first time for the project.
{% endhint %}

<figure><img src="../../../../../.gitbook/assets/Active Submitters.png" alt=""><figcaption><p>Active Submitters </p></figcaption></figure>

## Time To Merge

This line chart provides you the average time, in days, it takes for a PR to be merged during the selected time period.

<figure><img src="../../../../../.gitbook/assets/Time to .png" alt=""><figcaption><p>Time To Merge </p></figcaption></figure>

## Time In Review&#x20;

This line graph provides you the average time in days required for pull request to be reviewed during the selected time period.&#x20;

<figure><img src="../../../../../.gitbook/assets/Time  review.png" alt=""><figcaption><p>Time in Review</p></figcaption></figure>

## New Contributor Efficiency&#x20;

This line graph provides the average time it takes for the first PR submitted by a new contributor to be accepted and merged.

{% hint style="info" %}
The Lead time will either be higher or at least same as the time in Review
{% endhint %}

<figure><img src="../../../../../.gitbook/assets/New Cont Eff.png" alt=""><figcaption><p>New Contributor Efficiency </p></figcaption></figure>

## &#x20;Top 10 Contributors&#x20;

This list provides you the details of the top 10 contributors for the project in last one  year. The top contributor of the project is calculated based on the PRs submitted on the project.&#x20;

This list provides various details such as:

* Name&#x20;
* Identity&#x20;
* Organization&#x20;
* Last activity&#x20;
* PRs submitted&#x20;
* PRs reviewed
* PRs merged&#x20;
* PR comments &#x20;

{% hint style="info" %}
* You can order the list based on PRs submitted, reviewed, merged and comments.&#x20;
* On Click of **All Technical Contributors**, all the technical contributors of the project are listed. &#x20;
{% endhint %}

<figure><img src="../../../../../.gitbook/assets/Top 10 PRS.gif" alt=""><figcaption><p>Top 10 Contributors </p></figcaption></figure>

## Top 10 Organizations

This list provides you the details of the top 10 organizations that contributing to the  the project in last one year. The top organization of the project is calculated based on the PRs submitted on the project.&#x20;

This list provides various details such as:

* Organization name&#x20;
* Contributors&#x20;
* Last activity&#x20;
* PRs submitted&#x20;
* PRs reviewed
* PRs merged&#x20;
* PR comments &#x20;

{% hint style="info" %}
You can order the list based on PRs submitted, reviewed, merged and comments.&#x20;
{% endhint %}

<figure><img src="../../../../../.gitbook/assets/Top 10 org PRS.gif" alt=""><figcaption><p>Top 10 Organizations </p></figcaption></figure>
