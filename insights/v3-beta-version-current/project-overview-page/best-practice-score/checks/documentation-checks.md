# Documentation Checks

### Adopters

**ID: `adopters`**

List of organizations using this project in production or at stages of testing.

This check passes if:

* An adopters _file_ is found in the repository. Globs used:

```
"adopters*"
"users*"

CASE SENSITIVE: false
```

* An adopters _reference_ is found in the repository’s `README` file. This is in the form of a **title header** or a link. Regexps used:

```
"(?im)^#+.*adopters.*$"
"(?im)^adopters$"
"(?i)\[.*adopters.*\]\(.*\)"
```

### Changelog

**ID: `changelog`**

A curated, chronologically ordered list of notable changes for each version.

This check passes if:

* A changelog _file_ is found in the repository. Globs used:

```
"changelog*"

CASE SENSITIVE: false
```

* A changelog _reference_ is found in the repository’s `README` file. This can be in the form of a **title header** or a link. Regexps used:

```
"(?im)^#+.*changelog.*$"
"(?im)^changelog$"
"(?i)\[.*changelog.*\]\(.*\)"
```

* A changelog _reference_ is found in the last GitHub release content body. Regexps used:

```
"(?i)changelog"
"(?i)changes"
```

### Code of conduct

**ID:** `code_of_conduct`

Adopt a code of conduct to establish community standards, promote an inclusive and welcoming initiative, and outline procedures for handling abuse.

This check passes if:

* A code of conduct _file_ is found in the repository. Globs used:

```
"code*of*conduct*"
".github/code*of*conduct*"
"docs/code*of*conduct*"

CASE SENSITIVE: false
```

* A code of conduct _reference_ is found in the repository’s `README` file. This can be in the form of a **title header** or a link. Regexps used:

```
"(?im)^#+.*code of conduct.*$"
"(?im)^code of conduct$"
"(?i)\[.*code of conduct.*\]\(.*\)"
```

* A code of conduct _file_ is found in the [default community health files repository](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file), for example.

### Contributing

**ID**: `contributing`

A contributing file in your repository provides potential project contributors with a short guide to how they can help with your project.

This check passes if:

* A contributing _file_ is found in the repository. Globs used:

```
"contributing*"
".github/contributing*"
"docs/contributing*"

CASE SENSITIVE: false
```

* A contributing _reference_ is found in the repository’s `README` file. This can be in the form of a **title header** or a link. Regexps used:

```
"(?im)^#+.*contributing.*$"
"(?im)^contributing$"
"(?i)\[.*contributing.*\]\(.*\)"
```

* A contributing file is found in the [default community health files repository](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file).

### Governance

**ID**: `governance`

Document that explains how the governance and committer process works in the repository.

This check passes if:

* A governance _file_ is found in the repository. Globs used:

```
"governance*"
"docs/governance*"

CASE SENSITIVE: false
```

* A governance _reference_ is found in the repository’s `README` file. This can be in the form of a **title header** or a link. Regexps used:

```
"(?im)^#+.*governance.*$"
"(?im)^governance$"
"(?i)\[.*governance.*\]\(.*\)"
```

### Maintainers <a href="#maintainers" id="maintainers"></a>

The maintainers file contains a list of the current maintainers of the repository.

This check passes if:

* A maintainers _file_ is found in the repository. Globs used:

```
"maintainers*"
"docs/maintainers*"
"owners*"
"docs/owners*"
"codeowners*"
".github/codeowners*"
"docs/codeowners*"

CASE SENSITIVE: false
```

* A maintainers _reference_ is found in the repository’s `README` file. This can be in the form of a **title header** or a link. Regexps used:

```
"(?im)^#+.*maintainers.*$"
"(?im)^maintainers$"
"(?i)\[.*maintainers.*\]\(.*\)"
```

### Readme

**ID**: `readme`

The readme file introduces and explains a project. It contains information that is commonly required to understand what the project is about.

This check passes if:

* A readme _file_ is found in the repository. Globs used:

```
"README*"
".github/README*"
"docs/README*"

CASE SENSITIVE: true
```

### Roadmap

**ID**: `roadmap`

Defines a high-level overview of the project’s goals and deliverables ideally presented on a timeline.

This check passes if:

* A roadmap _file_ is found in the repository. Globs used:

```
"roadmap*"

CASE SENSITIVE: false
```

* A roadmap _reference_ is found in the repository’s `README` file. This can be in the form of a **title header** or a link. Regexps used:

```
"(?im)^#+.*roadmap.*$"
"(?im)^roadmap$"
"(?i)\[.*roadmap.*\]\(.*\)"
```

### Website

**ID**: `website`

A `url` that users can visit to learn more about your project.

This check passes if:

* A website _`url`_ is configured in the GitHub repository.

### &#x20;
