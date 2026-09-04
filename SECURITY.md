# Security Policy

## Supported versions

Only the latest published release of Smallbird is supported. The app checks for and installs
updates automatically, so most users are already on the latest version. If you're unsure, check
your version under **Account → Settings** in the app, or compare it against the
[latest release](https://github.com/aniruddhkadam7/SmallBird-releases/releases/latest).

## Reporting a vulnerability

If you believe you've found a security vulnerability in Smallbird — the desktop app, its
auto-update mechanism, the release/signing process, or smallbird.in — please report it privately
rather than opening a public issue.

**Email:** [support@smallbird.in](mailto:support@smallbird.in)

Please include:

- A description of the issue and its potential impact
- Steps to reproduce (or a proof of concept, if applicable)
- The Smallbird version and operating system you tested on

We'll acknowledge reports as soon as we can and keep you updated as we investigate and address the
issue. Please give us a reasonable amount of time to address a report before any public
disclosure.

## Release integrity

Every Smallbird release published to this repository is cryptographically signed, and the desktop
app verifies that signature before applying an update. If you notice a release asset that looks
tampered with, unsigned, or inconsistent with the signature in its accompanying `latest.json`,
please report it using the contact above immediately.

## Scope

This repository contains only release binaries and metadata — it does not contain application
source code. If your report relates to something you found by inspecting the installed
application or its network traffic rather than this repository's contents, that's still in scope;
just note that in your report.
