# Security Review Checklist & Guidance

## Purpose
Embed a pragmatic security checklist into delivery so teams can reduce security risks early and consistently.

## Security Engineer - Role Summary
Security Engineers ensure security considerations are addressed through design, implementation, and release.

## Responsibilities
- Perform threat modeling for significant changes
- Run and review automated dependency and vulnerability scans
- Review PRs for security issues and advise on mitigations
- Validate secrets management and access controls

## Security checklist (to run during planning, PR review, and pre-release)
- [ ] Threat model or notes for significant features
- [ ] Identify sensitive data and required protections
- [ ] Dependency scans run and critical vulnerabilities addressed
- [ ] IAM/permissions reviewed for new services or resources
- [ ] Secrets & config reviewed for safe handling
- [ ] Security test cases added to QA/integration tests
- [ ] Compliance/regulatory requirements identified (if applicable)

## Suggested process
- Add a security checklist item to the PR template for significant changes.
- Request a security review for high-risk features or changes that handle sensitive data.
- Track security findings as issues and assign remediation owners.

