# Contributor Growth & Retention

The dashboard shows the following metrics:

1. **Total:** It displays:
   * The total number of unique contributors (calculated based on their unique LF ID) who performed code activity, such as commit PRs, submitted or reviewed or commented on a PR or changeset, created or commented or closed an issue during the selected time period.
   * The rate of change (in percentage) in the number of unique contributors during the selected time period compared to the preceding time period.
2. **Active:** Active contributors are the code contributors who are actively performing code activity during the selected time period. for example, if the selected time period is last 1 year, active code performance is calculated if they have performed code activity during last six months of the selected time period. This section displays:
   * Total number of active contributors who are performing code activity during the selected time period.
   * Rate of change (in percentage) in the number of active contributors from the previous time period to the selected time period.
3. **Drifting Away:**&#x20;
   * Number of active contributors who have been active in the last one year, but didn't perform any code activity in the last 6 months from any point of time within the given time period.
   * Rate of change (in percentage) in the number of drifting-away contributors from the previous time period to the selected time period.
4. **Churn Rate:** Churn rate is calculated as :`Total Active Contributors recorded at the start of the selected time period + Total New Contributors who joined during the selected time period)- Active contributors at the end of the time period/(Active Contributors recorded at the start of the selected time period + Total New Contributors who joined during the selected time period)`
