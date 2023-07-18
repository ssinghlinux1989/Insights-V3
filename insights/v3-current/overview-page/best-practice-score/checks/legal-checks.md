# Legal Checks

### &#x20;<a href="#trademark-disclaimer" id="trademark-disclaimer"></a>

### Trademark disclaimer <a href="#trademark-disclaimer" id="trademark-disclaimer"></a>

**ID**: `trademark_disclaimer`

Project sites should have the Linux Foundation trademark disclaimer.

This check passes if:

* The Linux Foundation trademark disclaimer is found in the content of the website configured in Github. Regexps used:

```
"https://(?:w{3}\.)?linuxfoundation.org/trademark-usage"
"The Linux Foundation.* has registered trademarks and uses trademarks"
```
