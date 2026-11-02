# Security Policy

## Supported Versions

The following versions of Onpu AI currently receive security updates:

| Version | Supported          |
| ------- | ------------------ |
| 2.x     | :white_check_mark: |
| 1.x     | :white_check_mark: |
| &lt; 1.0   | :x:                |

&gt; Only the latest minor release of each supported major version receives
&gt; patches. If you're running an unsupported version, please upgrade before
&gt; reporting issues.

## Reporting a Vulnerability

**Please do not report security vulnerabilities through public GitHub issues.**

Instead, report them via one of the following channels:

- **Email:** security@your-domain.com &lt;!-- replace with your real address --&gt;
- **GitHub Private Reporting:** Use the "Report a vulnerability" button under
  the Security tab of this repository (GitHub private vulnerability reporting).

When reporting, please include:

- A description of the vulnerability and its potential impact
- Steps to reproduce, proof-of-concept code, or a screenshot if applicable
- The affected version(s) and environment (OS, deployment method, etc.)
- Any suggested mitigations, if you have them

### What to Expect

- **Acknowledgment:** within 72 hours of your report
- **Status updates:** at least once every 7 days until resolution
- **Resolution target:** critical issues within 14 days; others within 30–90 days
  depending on severity

### If the Report Is Accepted

- We will confirm the issue, develop a fix, and credit you in the release notes
  (unless you prefer to remain anonymous).
- A fix will be shipped for all supported versions, followed by a public
  advisory (GitHub Security Advisory / CVE where applicable).
- We ask that you do not disclose the issue publicly until the advisory is
  published — typically within 90 days of the initial report.

### If the Report Is Declined

- We will explain why (e.g., not reproducible, intended behavior, out of scope)
  and, where possible, suggest an alternative place to raise the concern.

## Scope

The following are generally **out of scope**:

- Vulnerabilities in third-party dependencies already tracked upstream —
  please report those to the dependency's maintainers
- Denial-of-service attacks requiring unrealistic resource expenditure
- Social engineering or physical attacks
- Issues in unsupported (EOL) versions listed above

## Disclosure Policy

We follow coordinated disclosure. Once a fix is available for all supported
versions, we will publish a security advisory describing the issue, affected
versions, and remediation steps. Reporters who follow this policy will be
publicly credited.
