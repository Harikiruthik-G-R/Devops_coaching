# Security Policy

## Supported Versions

We are committed to maintaining the security of the KEC × GUVI collaboration website. Currently supported versions:

| Version | Supported          |
| ------- | ------------------ |
| 1.0.x   | :white_check_mark: |

## Reporting a Vulnerability

We take the security of our website seriously. If you discover a security vulnerability, please follow these steps:

### How to Report

1. **DO NOT** create a public GitHub issue for security vulnerabilities
2. Email us at: **security@kec.edu** or **support@guvi.in**
3. Include the following information:
   - Description of the vulnerability
   - Steps to reproduce the issue
   - Potential impact
   - Suggested fix (if any)

### What to Expect

- **Acknowledgment**: We will acknowledge receipt of your report within 48 hours
- **Investigation**: We will investigate and validate the reported vulnerability
- **Updates**: You will receive updates on the progress every 5-7 days
- **Resolution**: We aim to resolve critical vulnerabilities within 30 days
- **Credit**: With your permission, we will credit you in our security acknowledgments

## Security Measures

Our website implements the following security measures:

### Frontend Security
- ✅ Input validation on all form fields
- ✅ XSS prevention through proper encoding
- ✅ HTTPS enforcement (when deployed)
- ✅ No sensitive data stored in localStorage/sessionStorage
- ✅ Content Security Policy headers (recommended for deployment)

### Code Security
- ✅ Regular dependency updates
- ✅ Automated security scanning via GitHub Actions
- ✅ Code review process for all changes
- ✅ No hardcoded credentials or API keys

### Deployment Security
- ✅ Secure hosting configuration
- ✅ Regular security audits
- ✅ Automated vulnerability scanning
- ✅ HTTPS/TLS encryption

## Security Best Practices for Contributors

If you're contributing to this project, please follow these guidelines:

1. **Never commit sensitive data**
   - No API keys, passwords, or tokens
   - Use environment variables for configuration
   - Add sensitive files to `.gitignore`

2. **Validate all inputs**
   - Sanitize user inputs
   - Use proper encoding for outputs
   - Implement CSRF protection where needed

3. **Keep dependencies updated**
   - Regularly update npm packages
   - Review security advisories
   - Use `npm audit` before committing

4. **Follow secure coding practices**
   - Avoid `eval()` and similar dangerous functions
   - Use parameterized queries (if database is added)
   - Implement proper error handling

5. **Test security features**
   - Test form validation
   - Check for XSS vulnerabilities
   - Verify HTTPS enforcement

## Automated Security Checks

Our repository includes automated security workflows:

- **Dependency Scanning**: OWASP Dependency Check
- **Code Analysis**: GitHub CodeQL
- **Secret Detection**: TruffleHog
- **Web Security**: Security headers and best practices
- **HTML Validation**: W3C validation

These checks run automatically on:
- Every push to main/develop branches
- Every pull request
- Weekly scheduled scans (Mondays at 9:00 AM UTC)

## Security Updates

We will notify users of security updates through:
- GitHub Security Advisories
- Release notes
- Email notifications (for critical issues)

## Compliance

This project follows:
- OWASP Top 10 security guidelines
- Web Content Accessibility Guidelines (WCAG)
- General Data Protection Regulation (GDPR) principles

## Contact

For security-related questions or concerns:
- **Email**: security@kec.edu, support@guvi.in
- **GitHub**: Create a private security advisory

## Acknowledgments

We appreciate the security research community and will acknowledge researchers who responsibly disclose vulnerabilities (with their permission).

---

**Last Updated**: February 9, 2026
