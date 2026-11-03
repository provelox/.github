# Security policy

Provelox runs on servers that hold other people's apps and data, so we take security reports seriously.

## Reporting a vulnerability

**Please do not open a public issue.** Report it privately instead:

1. Go to the **Security** tab of the affected repository (for the platform: [provelox/provelox](https://github.com/provelox/provelox)).
2. Choose **Report a vulnerability** and describe what you found: what is affected, how to reproduce it, and what an
   attacker could do.

We will acknowledge the report, keep you informed while we work on a fix, and credit you in the release notes if you
wish. Please give us a reasonable time to fix the problem before you share details publicly.

## Supported versions

Only the latest release receives security fixes. Provelox updates move forward only, so keeping up to date is the way
to stay safe: see the project's security guide for how to run it safely.

## What is in scope

The Provelox platform (the API, the web console and the installer) and the container image
`ghcr.io/provelox/provelox`. Vulnerabilities in the apps you deploy with it, or in Docker itself, are out of scope.
