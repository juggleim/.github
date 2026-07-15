# JuggleIM Security Policy

JuggleIM takes the security of messaging infrastructure, client SDKs, applications, and user data seriously.

This is the default security policy for repositories in the JuggleIM organization. A repository-specific `SECURITY.md` takes precedence when present.

## Supported versions

Security fixes generally target the latest released version and the current default branch of the affected repository. Before reporting, verify the issue against an up-to-date release when it is safe to do so.

## Reporting a vulnerability

**Do not report a security vulnerability through a public issue, pull request, discussion, or community chat.**

Use GitHub private vulnerability reporting in the affected repository:

1. Open the repository's **Security** tab.
2. Select **Advisories**.
3. Select **Report a vulnerability**.

If private vulnerability reporting is unavailable, contact the project team through the [JuggleIM website](https://www.juggle.im/) and request a private security contact. Do not include exploit details or sensitive data in the initial public-facing message.

## What to include

Provide enough information for maintainers to reproduce and assess the issue safely:

- A clear description of the vulnerability and potential impact.
- The affected repository, component, version, commit, SDK platform, and deployment mode.
- Reproduction steps or a proof of concept.
- Required privileges, configuration, and environmental conditions.
- Relevant sanitized logs or traces.
- Possible mitigations or remediation ideas, if known.

Never include real credentials, app secrets, access tokens, private conversations, or personal data. Use synthetic test data and redact diagnostic output.

## Relevant security areas

Reports may include, but are not limited to:

- Authentication or authorization bypass.
- Cross-tenant or cross-user data access.
- Leakage of `app_secret`, tokens, message content, or user information.
- Protocol, transport, encryption, or signature weaknesses.
- Message spoofing, unauthorized message operations, or moderation bypass.
- Remote code execution, injection, path traversal, or unsafe file handling.
- Denial of service or remotely triggered resource exhaustion.
- Vulnerable dependencies with a demonstrated impact on JuggleIM.

## Disclosure process

Maintainers will evaluate the report, confirm affected versions, coordinate a fix, and prepare release guidance. Please allow reasonable time for remediation before public disclosure. We will credit reporters when appropriate unless anonymity is requested.

Out-of-scope reports, automated scans without demonstrated impact, or reports that expose user data may receive limited response.

