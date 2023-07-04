# Issues

The **Issue Metric** measures the number of issues reported and tracked within a specified period. It compares the number of issues opened, the number of issues closed, and the total commits for the selected time period.

The metric is based on the following activity types:

* `issues-closed`
* `issues-opened`

### Interact with the chart

The analytics tool employs a combined chart (a line chart and bar charts) on its dashboard to analyze the **Issue Metric**. The line on the chart connects the data points, allowing you to observe trends and patterns over time.

The dashboard shows the issues (opened `+` closed issues) in a snapshot and a detailed chart (open, closed, and the total issues).

1. On the **Overview** page, select the project and repositories (1) for which you want to see the data.
2. Select the specific time period using the filter option (2).
3. The high-level tile (3) shows you the total issues (open + closed) for the selected time range.
4. The detailed analysis chart shows you the open issues, closed issues, and the [cumulative](contributor.md#:\~:text=Cumulative%20chart%20description) count of total issues for the selected period. On the left side, the chart shows the chart trend summary (4). &#x20;

<figure><img src="../../../../.gitbook/assets/2023-06-27_16h34_14 (1).png" alt=""><figcaption></figcaption></figure>

5. Hover over chart (5) to see the open issues, closed issues, and total issues for the selected month.
6. This interactive download feature (6) enables you to download the chart in CSV and PNG file formats.

### Why is this metric important?

* **Issues Tracking and Management:** By visualizing the data on a line chart, it becomes easier to identify the increase or decrease in issue activity, allowing for effective resource allocation and prioritization.
* **Performance Evaluation:** The **Issue Metric** helps in evaluating the performance of the development team and the project as a whole. Changes in issue count over time indicate improvements in software quality, bug-fixing efficiency, or the impact of development efforts.
* **Community Engagement:** A higher number of reported issues indicates the active participation and involvement of the community in the open source project.

### FAQs

<details>

<summary>If an issue was opened and closed in the selected time frame, will it be counted twice?</summary>

It is a unique issue. however,  on the graph, it is shown as two data points, i.e. one on the 'opened' line and the other on the 'closed' line.

</details>

<details>

<summary>What if an issue was opened before the selected time period but closed outside the selected time period? </summary>

It is not counted on the number tile or on the detailed graph.

</details>

<details>

<summary>What if an issue was opened before the selected time period but closed within the selected time period?</summary>

It is shown in the number tile and the graph as well. On the graph, though it would show as one data point on the 'closed' line.

</details>
