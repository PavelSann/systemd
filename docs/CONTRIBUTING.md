---
title: Contributing
category: Contributing
layout: default
SPDX-License-Identifier: LGPL-2.1-or-later
---

# Contributing

We welcome contributions from everyone. However, please follow the following guidelines when posting a GitHub Pull Request or filing a GitHub Issue on the systemd project:

## Filing Issues

* We use [GitHub Issues](https://github.com/systemd/systemd/issues) **exclusively** for tracking **bugs** and **feature** **requests** (RFEs) of systemd. If you are looking for help, please contact [systemd-devel mailing list](https://lists.freedesktop.org/mailman/listinfo/systemd-devel) instead.
* We only track bugs in the **two** **most** **recently** **released** (non-rc) **versions** of systemd in the GitHub Issue tracker. If you are using an older version of systemd, please contact your distribution's bug tracker instead (see below). See [GitHub Release Page](https://github.com/systemd/systemd/releases) for the list of most recent releases.
* When filing a feature request issue (RFE), please always check first if the newest upstream version of systemd already implements the feature, and whether there's already an issue filed for your feature by someone else.
* When filing an issue, specify the **systemd** **version** you are experiencing the issue with. Also, indicate which **distribution** you are using.
* Please include an explanation how to reproduce the issue you are pointing out.

Following these guidelines makes it easier for us to process your issue, and ensures we won't close your issue right-away for being misfiled.

### Older downstream versions
For older versions that are still supported by your distribution please use respective downstream tracker:
* **Fedora** - [bugzilla](https://bugzilla.redhat.com/enter_bug.cgi?product=Fedora&component=systemd)
* **RHEL/CentOS** - [bugzilla](https://bugzilla.redhat.com/) or [systemd-rhel github](https://github.com/systemd-rhel/)
* **Debian** - [bugs.debian.org](https://bugs.debian.org/cgi-bin/pkgreport.cgi?pkg=systemd)

## Security vulnerability reports

See [reporting of security vulnerabilities](SECURITY.md).

## Posting Pull Requests

* Make sure to post PRs only relative to a very recent git master.
* Follow our [Coding Style](CODING_STYLE.md) when contributing code. This is a requirement for all code we merge.
* Please make sure to test your change before submitting the PR. See the [Hacking guide](HACKING.md) for details on how to do this.
* Make sure to run the test suite locally, before posting your PR. We use a CI system, meaning we don't even look at your PR, if the build and tests don't pass.
* If you need to update the code in an existing PR, force-push into the same branch, overriding old commits with new versions.
* After you have pushed a new version, add a comment about the new version (no notification is sent just for the commits, so it's easy to miss the update without an explicit comment). If you are a member of the systemd project on GitHub, remove the `reviewed/needs-rework` label.
* If you are copying existing code from another source (eg: a compat header), please make sure the license is compatible with LGPL-2.1-or-later. If the license is not LGPL-2.1-or-later, please add a note to LICENSES/README.md.

## Final Words

We'd like to apologize in advance if we are not able to process and reply to your issue or PR right-away. We have a lot of work to do, but we are trying our best!

Thank you very much for your contributions!
