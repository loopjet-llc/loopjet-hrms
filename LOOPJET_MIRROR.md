# Loopjet upstream mirror

This repository tracks [frappe/hrms](https://github.com/frappe/hrms) on the `version-16` branch.

Do not make Loopjet business customizations in this repository. Put extension code in
`loopjet-llc/loopjet-frappe-custom`. Core patches are permitted only when the Frappe
extension APIs cannot implement a requirement; such patches must be isolated on a
`loopjet/*` branch and documented with an upstream issue or pull request.

The scheduled GitHub Actions workflow fast-forwards the product branch daily. Reviewed
bootstrap release tags are retained here, while deployment upgrades pin authoritative
release tags from the official Frappe repositories. This avoids storing a personal token
with permission to rewrite upstream workflow references.
