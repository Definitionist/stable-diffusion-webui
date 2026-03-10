# Security Policy

## Supported Versions

| Version | Supported          |
| ------- | ------------------ |
| latest  | :white_check_mark: |

## Reporting a Vulnerability

We take the security of Stable Diffusion web UI seriously. If you believe you have found a security vulnerability, please report it responsibly.

**Please do NOT report security vulnerabilities through public GitHub issues.**

Instead, please report them via one of the following methods:

1. **GitHub Security Advisories**: Use the [Security tab](../../security/advisories/new) to report a vulnerability privately.
2. **Email**: Contact the maintainers directly.

### What to include

Please include as much of the following information as possible to help us better understand and resolve the issue:

- Type of issue (e.g., remote code execution, path traversal, cross-site scripting, etc.)
- Full paths of source file(s) related to the issue
- The location of the affected source code (tag/branch/commit or direct URL)
- Step-by-step instructions to reproduce the issue
- Proof-of-concept or exploit code (if possible)
- Impact of the issue, including how an attacker might exploit it

### Response Timeline

- **Acknowledgment**: We will acknowledge receipt of your vulnerability report within 48 hours.
- **Assessment**: We will provide an initial assessment of the report within 7 days.
- **Resolution**: We aim to release a fix within 30 days, depending on the complexity of the vulnerability.

### Disclosure Policy

- We will work with you to understand and resolve the issue before any public disclosure.
- We will credit you for the discovery (unless you prefer to remain anonymous).
- We request that you give us reasonable time to address the issue before making it public.

## Security Best Practices for Users

- Always run the web UI in a trusted environment.
- Be cautious when loading models, extensions, or embeddings from untrusted sources.
- Keep your installation up to date to benefit from security patches.
- Use `--listen` and `--share` flags with caution, as they expose the web UI to network access.
- Consider using `--api-auth` when exposing the API to set authentication credentials.
