# Security Policy

## Reporting a Vulnerability

We take the security of Salah seriously. If you discover a security vulnerability, please report it responsibly.

### How to Report

**Please do NOT report security vulnerabilities through public GitHub issues.**

Instead, please report them via email at [INSERT SECURITY EMAIL].

### What to Include

When reporting a vulnerability, please include:

- Type of issue (e.g., buffer overflow, SQL injection, cross-site scripting, etc.)
- Full paths of source file(s) related to the manifestation of the issue
- The location of the affected source code (tag/branch/commit or direct URL)
- Any special configuration required to reproduce the issue
- Step-by-step instructions to reproduce the issue
- Proof-of-concept or exploit code (if possible)
- Impact of the issue, including how an attacker might exploit it

### Response Timeline

- **Initial Response**: Within 48 hours
- **Status Update**: Within 1 week with progress update
- **Resolution**: We strive to resolve all security vulnerabilities in a timely manner

### Disclosure Policy

We follow a coordinated disclosure policy:

1. Security researcher reports vulnerability
2. We confirm and assess the vulnerability
3. We develop and test a fix
4. We release the fix and notify users
5. We publicly disclose the vulnerability after users have had reasonable time to update

### Recognition

We appreciate the work of security researchers and will acknowledge valid security reports in our release notes (unless you prefer to remain anonymous).

## Supported Versions

| Version | Supported          |
| ------- | ------------------ |
| 1.0.x   | :white_check_mark: |
| < 1.0   | :x:                |

## Scope

This security policy applies to:
- The Salah Flutter application
- The Daily Prayer Time API integration
- Location and Qibla direction features

This policy does NOT apply to:
- Third-party dependencies (please report to their respective maintainers)
- Self-hosted deployments (users are responsible for their own security)
