# Best Practices Checks

### Analytics <a href="#analytics" id="analytics"></a>

**ID**: `analytics`

Project websites provide some web analytics.

This check passes if:

* A Google Analytics 3 (Universal Analytics) **Tracking ID** is found in the source of the website configured in GitHub. Regexps used:

```
"UA-[0-9]+-[0-9]+"
```

* A Google Analytics 4 **Measurement ID** is found in the source of the website configured in Github. Regexps used:

```
"G-[A-Z0-9]+"
```

* The HubSpot **tracking code** is found in the source of the website configured in Github. Regexps used:

```
"//js.hs-scripts.com/.+\.js"
```

### Artifact Hub badge

**ID**: `artifacthub_badge`

Projects can list their content on Artifact Hub to improve their discoverability.

This check passes if:

* An `Artifact Hub` badge is found in the repository’s `README` file. Regexps used:

```
"https://artifacthub.io/badge/repository/.*
```

### Contributor license agreement

**ID**: `cla`

The CLA defines the conditions under which intellectual property is contributed to a business or project.

This check passes if:

* A CLA check is found in the latest merged PR on GitHub. Regexps used:

```
"(?i)cncf-cla"
"(?i)cla/linuxfoundation"
"(?i)easycla"
"(?i)license/cla"
"(?i)cla/google"
```

{% hint style="info" %}
This check will be automatically marked as exempt if the DCO check passes but this one does not.
{% endhint %}

### Community meeting <a href="#community-meeting" id="community-meeting"></a>

**ID**: `community_meeting`

Community meetings are often held to engage community members, hear more voices, and get more viewpoints.

This check passes if:

* A _reference_ to the community meeting is found in the repository’s `README` file. Regexps used:

```
"(?i)(community|developer|development) \[?(call|event|meeting|session)"
"(?i)(weekly|biweekly|monthly) \[?meeting"
"(?i)meeting minutes"
```

### Developer Certificate of Origin <a href="#developer-certificate-of-origin" id="developer-certificate-of-origin"></a>

**ID**: `dco`

Mechanism for contributors to certify that they wrote or have the right to submit the code they are contributing.

This check passes if:

* The last commits in the repository have the DCO signature (_Signed-off-by_). Merge pull request and merge branch commits are ignored for this check.
* A DCO check is found in the latest merged PR on GitHub. Regexps used:

```
"(?i)dco"
```

{% hint style="info" %}
This check will be automatically marked as exempt if the CLA check passes, but this one does not.
{% endhint %}

### GitHub discussions <a href="#github-discussions" id="github-discussions"></a>

**ID**: `github_discussions`

Projects should enable GitHub discussions in their repositories.

This check passes if:

* A discussion that is less than one year old is found on GitHub.

### OpenSSF badge <a href="#openssf-badge" id="openssf-badge"></a>

**ID**: `openssf_badge`

The Open Source Security Foundation (OpenSSF) Best Practices badge is a way for Free/Libre and Open Source Software (FLOSS) projects to show that they follow best practices.

This check passes if:

* An `OpenSSF` (CII) badge is found in the repository’s `README` file. Regexps used:

```
"https://bestpractices.coreinfrastructure.org/projects/\d+"
```

### Recent release <a href="#recent-release" id="recent-release"></a>

**ID**: `recent_release`

The project should have released at least one version in the last year.

This check passes if:

* A release that is less than one year old is found on GitHub.

### Slack presence <a href="#slack-presence" id="slack-presence"></a>

**ID**: `slack_presence`

Projects should have presence in the CNCF Slack or Kubernetes Slack.

This check passes if:

* A _reference_ to the CNCF Slack or Kubernetes Slack is found in the repository’s `README` file. Regexps used:

```
"(?i)https?://cloud-native.slack.com"
"(?i)https?://slack.cncf.io"
"(?i)https?://kubernetes.slack.com"
"(?i)https?://slack.k8s.io"

```
