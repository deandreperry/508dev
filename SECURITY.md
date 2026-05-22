# Security Policy

## Supported Versions

The following versions of this project are currently receiving security updates:

| Version | Supported |
| ------- | --------- |
| Latest  | ✅ |
| Legacy versions | ❌ |

---

## Reporting a Vulnerability

If you discover a security vulnerability, accessibility exploit, injection issue, or other security concern, please report it responsibly through GitHub Issues.

### Please include:
- Description of the issue
- Steps to reproduce
- Potential impact
- Screenshots or proof-of-concept if applicable
- Suggested remediation (optional)

---

## Reporting Method

Please open a GitHub Issue using the repository’s issue tracker.

Before submitting:
- Check existing issues first
- Use a clear descriptive title
- Include reproduction steps when possible

---

## Response Timeline

| Stage | Estimated Time |
| --- | --- |
| Initial review | Within 72 hours |
| Verification | 3–7 business days |
| Patch / mitigation | Depending on severity |

Critical vulnerabilities are prioritized immediately.

---

## Scope

This policy applies to:
- Frontend application code
- Accessibility playgrounds and simulations
- Interactive WCAG tooling
- Embedded JavaScript utilities
- Client-side storage usage
- Theme persistence/localStorage logic
- Keyboard interaction systems
- ARIA implementation patterns

---

## Out of Scope

The following are generally considered out of scope unless they result in a real exploitable issue:

- Missing security headers on local/dev environments
- Self-XSS requiring manual console execution
- Rate limiting concerns on static deployments
- Lighthouse warnings without practical exploitability
- Accessibility issues that do not create security risk
- Third-party CDN issues outside project control

---

## Security Practices

This project aims to follow modern frontend security best practices including:

- No inline user-generated HTML rendering
- Minimal external dependencies
- Semantic and accessible interaction patterns
- Safe localStorage usage
- Focus management protections
- Reduced reliance on unsafe DOM APIs
- Defensive event handling
- Progressive enhancement principles

---

## Disclosure Policy

Please avoid publicly disclosing vulnerabilities before maintainers have had reasonable time to investigate and address the issue.

Responsible disclosure helps protect users and contributors.

---

## Acknowledgements

Contributors who responsibly disclose valid security issues may be acknowledged in future release notes unless anonymity is requested.

---

© De’Andre Perry · 508 Dev
