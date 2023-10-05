# Calculating Global Score

Calculating a global score for a best practice score in an open-source project involves evaluating various aspects of the project against predefined best practices and assigning weights to those aspects based on their importance. Let's understand this with the sample example.

Define the following set of best practices that are important for the success and quality of the open-source project. Each category should have a set of criteria that can be evaluated.

### Assign Weights

Assign weights to each category based on their relative importance. These weights should add up to 100%. The weights reflect how much each category contributes to the overall quality of the project.

<details>

<summary>Documentation (40%)</summary>

* Code of conduct: 10
* Governance: 10
* Maintainers: 10
* Website: 10

</details>

<details>

<summary>Standards (30%)</summary>

* Analytics: 10
* GitHub discussions: 10
* Community meetings: 10

</details>

<details>

<summary>Security (20%)</summary>

* Binary artifacts: 10
* Dangerous workflow: 10

</details>

<details>

<summary>Legal (10%)</summary>

Approved licences: 10

</details>

**Evaluate Each Criterion**

For each criterion within a category, evaluate the project and assign a score.

Use a numerical scale (0–10) or any other suitable scale.

#### Documentation

* Code of conduct: 8
* Governance: 9
* Maintainer: 8
* Website: 7

#### Standards

* Analytics: 9
* GitHub Discussion: 10
* Community meetings: 8

#### Security

* Binary Artifacts: 8
* Dangerous Workflow: 9

#### Legal

* Approved Licenses: 9

### Calculate category scores

It is calculated by the average score\* weights

* `Documentation : ((8+9+8+7)/4)*.4= 3.2`
* `Standards: ((9+10+8)/3)*.30= 2.7`
* `Security: ((8+9)/2)*.20= 1.7`
* `Legal: 9*.10= .9`

**Calculate Global Score**

Sum up the category scores to obtain the global score for the best practice score of the open-source project.

Documentation+ Standards+Security+Legal= 3.2+2.7+1.7+.9 = 15.58
