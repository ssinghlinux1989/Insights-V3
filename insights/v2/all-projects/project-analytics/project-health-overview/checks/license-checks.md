# License Checks

### Approved license <a href="#approved-license" id="approved-license"></a>

**ID**: `license_approved`

Whether the repository uses an approved license or not.

This check passes if:

* The license identified matches any of the following:

```
"Apache-2.0"
"BSD-2-Clause"
"BSD-2-Clause-FreeBSD"
"BSD-3-Clause"
"ISC"
"MIT"
"PostgreSQL"
"Python-2.0"
"X11"
"Zlib"
```

### License scanning <a href="#license-scanning" id="license-scanning"></a>

**ID**: `license_scanning`

License scanning software scans and automatically identifies, manages, and addresses open source licensing issues.

This check passes if:

* A `FOSSA` or `Snyk` link is found in the repository’s `README` file. Regexps used:

```
"(https://app.fossa.(?:io|com)/projects/[^"'\)]+)"
"(https://snyk.io/test/github/[^/]+/[^/"]+)"
```

{% hint style="info" %}
A _link_ pointing to the license scanning results is provided in the [.clomonitor.yml](https://github.com/cncf/clomonitor/blob/main/docs/metadata/.clomonitor.yml) metadata file.
{% endhint %}

### Apache-2.0



**ID**: `license_Apache_2.0`

Identifier extracted from the provided license file.

This check passes if:

* A license _file_ is found in the repository and we can detect the license used. Globs used:

```
"LICENSE*"
"COPYING*"

CASE SENSITIVE: true
```

* A license Apache-2.0 can be obtained from GitHub.
