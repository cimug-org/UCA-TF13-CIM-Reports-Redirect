# UCA-TF13-CIM-Reports-Redirect

Redirect placeholder for the retired `utf13-reports.ucaiug.io` subdomain.

Every request (root or deep link) is sent to the same path on
[utf13-releases.ucaiug.io](https://utf13-releases.ucaiug.io/), preserving the
path, query string and `#fragment`. GitHub Pages serves `404.html` for any
unknown path, so deep links are handled by the same script as the root.

Do not add content here; the live site is
[cimug-org/UCA-TF13-CIM-Releases](https://github.com/cimug-org/UCA-TF13-CIM-Releases).
