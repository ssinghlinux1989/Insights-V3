# Checks

On a regular basis, a number of checks are performed on each repository listed in the database.&#x20;

Checks are grouped into `check sets.`One or more `check sets` are applied to a single repository, and each check set specifies the number of checks that will be performed on the repository.

The check’s file must declare the following information:

* `ID`: check identifier.
* `WEIGHT`: weight of this check, used to calculate scores.
* `CHECK_SETS`: check sets this new check belongs to.

### Reference

{% embed url="https://clomonitor.io/docs/topics/checks/#github-discussions" %}
