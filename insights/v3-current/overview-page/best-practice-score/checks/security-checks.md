# Security Checks

### Binary artifacts <a href="#binary-artifacts-from-openssf-scorecard" id="binary-artifacts-from-openssf-scorecard"></a>

This check determines whether the project has generated executable (binary) artifacts in the source repository. For more details, see the [check documentation.](https://github.com/ossf/scorecard/blob/main/docs/checks.md#binary-artifacts)

### Code review  <a href="#code-review-from-openssf-scorecard" id="code-review-from-openssf-scorecard"></a>

**ID**: `code_review`

This check determines whether the project requires code review before pull requests (merge requests) are merged. For more details, see the [check documentation.](https://github.com/ossf/scorecard/blob/main/docs/checks.md#code-review)

### Dangerous workflow  <a href="#dangerous-workflow-from-openssf-scorecard" id="dangerous-workflow-from-openssf-scorecard"></a>

**ID**: `dangerous_workflow`

This check determines whether the project’s GitHub Action workflows has dangerous code patterns. For more details, see the [check documentation](https://github.com/ossf/scorecard/blob/main/docs/checks.md#dangerous-workflow)_._

### Dependency update tool  <a href="#dependency-update-tool-from-openssf-scorecard" id="dependency-update-tool-from-openssf-scorecard"></a>

**ID**: `dependency_update_tool`

This check tries to determine if the project uses a dependency update tool, specifically [dependabot](https://docs.github.com/en/code-security/supply-chain-security/keeping-your-dependencies-updated-automatically/configuration-options-for-dependency-updates) or [renovatebot](https://docs.renovatebot.com/configuration-options/). For more details, see the [check documentation.](https://github.com/ossf/scorecard/blob/main/docs/checks.md#dependency-update-tool)

#### Maintained (from OpenSSF Scorecard) <a href="#maintained-from-openssf-scorecard" id="maintained-from-openssf-scorecard"></a>

**ID**: `maintained`

This check determines whether the project is actively maintained. For more details, see the [check documentation.](https://github.com/ossf/scorecard/blob/main/docs/checks.md#maintained)

### Software bill of materials (SBOM) <a href="#software-bill-of-materials-sbom" id="software-bill-of-materials-sbom"></a>

**ID**: `sbom`

List of components in a piece of software, including licenses, versions, etc.

This check passes if:

* The latest release on Github includes an asset which name contains _sbom_. Regexps used:

```
"(?i)sbom"
```

* The repository’s `README` file contains a _SBOM_ section that explains where they are published to, format used, etc. Regexps used to locate the _title header_:

```
"(?im)^#+.*sbom.*$"
"(?im)^#+.*software bill of materials.*$"
"(?im)^sbom$"
"(?im)^software bill of materials$"
```

#### Security policy <a href="#security-policy" id="security-policy"></a>

**ID**: `security_policy`

Clearly documented security processes explaining how to report security issues to the project.

This check passes if:

* A security policy _file_ is found in the repository. Globs used:

```
"security*"
".github/security*"
"docs/security*"

CASE SENSITIVE: false
```

* A security policy _reference_ is found in the repository’s `README` file. This can be in the form of a **title header** or a link. Regexps used:

```
"(?im)^#+.*security.*$"
"(?im)^security$"
"(?i)\[.*security.*\]\(.*\)"
```

* A security policy _file_ is found in the[ default community health files repository.](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file)

### Signed releases <a href="#signed-releases-from-openssf-scorecard" id="signed-releases-from-openssf-scorecard"></a>

**ID**: `signed_releases`

This check tries to determine if the project cryptographically signs release artifacts. For more details, see the [check documentation.](https://github.com/ossf/scorecard/blob/main/docs/checks.md#signed-releases)

### Token permissions  <a href="#token-permissions-from-openssf-scorecard" id="token-permissions-from-openssf-scorecard"></a>

**ID**: `token_permissions`

This check determines whether the project’s automated workflows tokens are set to read-only by default. For more details, see the [check documentation.](https://github.com/ossf/scorecard/blob/main/docs/checks.md#token-permissions)
