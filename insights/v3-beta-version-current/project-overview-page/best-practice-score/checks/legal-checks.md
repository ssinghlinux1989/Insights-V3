# Legal Checks

### Approved License

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

### License Scanning

License scanning software scans and automatically identifies, manages, and addresses open source licensing issues.

This check passes if:

* A `FOSSA` or `Snyk` link is found in the repository’s `README` file. Regexps used:

```
"(https://app.fossa.(?:io|com)/projects/[^"'\)]+)"
"(https://snyk.io/test/github/[^/]+/[^/"]+)"
```

* A _link_ pointing to the license scanning results is provided in the [.clomonitor.yml](https://github.com/cncf/clomonitor/blob/main/docs/metadata/.clomonitor.yml) metadata file.

### Apache-2.0



### Trademark disclaimer <a href="#trademark-disclaimer" id="trademark-disclaimer"></a>

**ID**: `trademark_disclaimer`

Project sites should have the Linux Foundation trademark disclaimer.

This check passes if:

* The Linux Foundation trademark disclaimer is found in the content of the website configured in Github. Regexps used:

```
"https://(?:w{3}\.)?linuxfoundation.org/trademark-usage"
"The Linux Foundation.* has registered trademarks and uses trademarks"
```
