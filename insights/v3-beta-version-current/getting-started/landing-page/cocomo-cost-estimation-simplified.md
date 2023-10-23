---
description: Constructive Cost Model
---

# COCOMO: Cost Estimation Simplified

The COCOMO (Constructive Cost Model) is a widely used model that estimates the effort, time, and cost associated with software development projects.

The model takes into account factors such as project size, complexity, team experience, and development environment.

{% hint style="info" %}
#### The following tool is used to generate COCOMO Score: [https://github.com/boyter/scc](https://github.com/boyter/scc)
{% endhint %}

The COCOMO model consists of three different levels or modes:

1. Basic COCOMO: This mode is used for early-stage project estimates and focuses on estimating effort based on lines of code (LOC). It uses a simple formula to calculate the effort required for a project, taking into account the project size in KLOC (thousands of lines of code).

{% hint style="info" %}
Insights V3 uses the basic model to calculate the software estimates for the selected open source projects.&#x20;
{% endhint %}

<details>

<summary>Basic COCOMO calculation Formula:</summary>

The model uses a formula to calculate the development effort based on the estimated size.&#x20;

```mathml
Effort (in person-months) = a * (Size in KLOC)^b
```

Where 'a' and 'b' are coefficients specific to the type of software project being estimated. These coefficients can be derived from the table.

</details>

<details>

<summary>Example (Sample Calculation):</summary>

Let's assume you have a small open source project with a codebase size of 10`,000` lines of code (LOC). The coefficients for the type of software project being estimated are `a = 2.4` and `b = 1.05`.

```
Effort (in person-months)= 2.4 * (KLOC)^1.05
Effort = 2.4 * (10)^1.05
Effort = 2.4 * 10.47
Effort ≈ 25.13 person-months
```

</details>

<details>

<summary>Cost Estimation:</summary>

To estimate the cost of the project, you need to consider the cost per person-month, which represents the average cost of one person working on the project for a month.&#x20;

Example: Let's assume the cost per person-month is $6,000.

```
Cost = Effort * Cost per person-month (Store in DB)
Cost = 190.56 person-months * $6,000/person-month
Cost ≈ $1,143,360 (rounded to the nearest dollar)
```

</details>

Constants based on Software Project Types (stored in the DB):

<figure><img src="../../../../.gitbook/assets/image (37).png" alt=""><figcaption></figcaption></figure>

For more information, see:

{% embed url="https://www.geeksforgeeks.org/software-engineering-cocomo-model/" %}
