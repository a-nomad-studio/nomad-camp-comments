# Security Policy

## Scope

This repository is the public GitHub Discussions backend for comments on a-nomad.com. It does not contain the Website source code, authentication database, private notes, attachments, or production credentials.

## Do not report security issues publicly

Please do not create a public Discussion, Issue, pull request, or comment for a security vulnerability. Public disclosure may expose readers or the site to unnecessary risk.

Potential security issues may include:

- Authentication or authorization bypasses.
- Exposure of private notes, attachments, account data, or credentials.
- Cross-site scripting, injection, or malicious content handling problems.
- Unexpected access to private GitHub Discussions or repository settings.
- Leaked tokens, cookies, passwords, or other credentials.

## Private reporting

Report security concerns privately through the contact channel at [a-nomad.com/contact/](https://a-nomad.com/contact/). Include:

- A short description and severity assessment.
- The affected URL, repository location, or Discussion URL.
- Reproduction steps or a minimal proof of concept, when safe.
- The potential impact.
- A safe way to contact you if follow-up is needed.

Do not include live credentials, session cookies, private user data, or other secrets in the report. If a secret has been exposed, revoke or rotate it immediately where possible and mention only the type of secret that was exposed.

## Response expectations

The maintainer will acknowledge a report when practical, investigate it privately, and coordinate remediation or disclosure timing based on the risk. Please do not publish details until the issue has been reviewed and a mitigation or coordinated disclosure plan is agreed.

## Scope boundary

GitHub, Giscus, Cloudflare, and other external services have their own security reporting channels and policies. Use their official reporting process for a vulnerability in their infrastructure. For an issue caused by this site's configuration or public comment integration, use the private contact channel above.
