# Security Checklist (What can be done in CursorAI & software-level not infrastructure!)

## Configuration Security
- [ ] Detect secrets in code
- [ ] Identify secrets committed to version control
- [ ] Flag hardcoded credentials

## Authentication & Authorization
- [ ] Identify missing authentication checks
- [ ] Detect improper authorization patterns
- [ ] Flag violations of principle of least privilege

## Data Protection
- [ ] Identify unencrypted sensitive data
- [ ] Detect missing input validation
- [ ] Find XSS vulnerabilities through missing output encoding
- [ ] Identify SQL injection vulnerabilities

## API Security
- [ ] Detect missing rate limiting
- [ ] Identify improper error handling that leaks information
- [ ] Find missing input validation in API endpoints

## Logging & Monitoring
- [ ] Identify sensitive information in logs
- [ ] Detect missing error logging

## Dependency Management
- [ ] Flag outdated dependencies with known vulnerabilities
- [ ] Identify excessive dependencies that increase attack surface

## Resilience & Availability
- [ ] Detect missing error handling
- [ ] Identify potential DoS vulnerabilities
- [ ] Find missing timeout configurations

## SDLC Security
- [ ] Identify common security issues through static analysis
- [ ] Suggest security improvements in code reviews