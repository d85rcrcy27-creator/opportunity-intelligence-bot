# Security Policy

## Reporting Security Vulnerabilities

If you discover a security vulnerability in this project, please email security concerns to the repository maintainer instead of using the issue tracker.

Please include:
- Description of the vulnerability
- Steps to reproduce or proof of concept
- Potential impact
- Suggested fix (if available)

## Security Measures

This repository has the following security measures in place:

- **CodeQL Analysis**: Automated code scanning for security vulnerabilities runs on every push and pull request
- **Dependabot**: Automatic scanning and patching of vulnerable dependencies
- **GitHub Actions**: CI/CD security checks on all code changes
- **Branch Protection**: Required reviews and status checks before merging

## Supported Versions

| Version | Supported          |
| ------- | ------------------ |
| latest  | :white_check_mark: |
| older   | :x:                |

Please keep your dependencies up to date by accepting Dependabot pull requests.

## Security Best Practices

- Keep all dependencies up to date
- Review and merge security-related PRs promptly
- Run security scans locally before submitting PRs
- Do not commit sensitive data (API keys, credentials, etc.)
- Use GitHub Secrets for sensitive environment variables
