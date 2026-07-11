# Loopjet upstream mirror

This repository tracks [frappe/hrms](https://github.com/frappe/hrms) on the `version-16` branch.

Do not make Loopjet business customizations in this repository. Put extension code in
`loopjet-llc/loopjet-frappe-custom`. Core patches are permitted only when the Frappe
extension APIs cannot implement a requirement; such patches must be isolated on a
`loopjet/*` branch and documented with an upstream issue or pull request.

The scheduled GitHub Actions workflow merges upstream changes daily and mirrors tags.
Production deployments remain pinned to reviewed release tags and are not upgraded by
this synchronization job.
