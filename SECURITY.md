# Security Policy

AI Tinkerers Luxembourg encourages responsible disclosure and security-conscious collaboration. We appreciate reports that help protect community-maintained code, documentation, infrastructure, and participants.

## Scope

This policy applies to security issues in repositories and services **maintained by AI Tinkerers Luxembourg**, including this `.github` repository where applicable.

Individual contributors' personal projects, linked third-party services, and the global AI Tinkerers website may have their own maintainers and disclosure policies. Report vulnerabilities to the responsible project or service owner.

## Reporting a vulnerability

**Please do not disclose a suspected vulnerability through a public issue, pull request, or discussion before it has been reviewed.**

1. Open the affected repository's **Security** tab and look for **Report a vulnerability** (GitHub private vulnerability reporting), if enabled.
2. If private reporting is unavailable, use a private maintainer or organizer contact channel published in the affected repository or on the [Luxembourg chapter website](https://luxembourg.aitinkerers.org/).
3. If no private channel can be found, request a private contact method without including exploit details, credentials, or sensitive evidence in the public request.

When reporting, please include where possible:

- The affected repository, file, component, or URL.
- A clear description of the vulnerability and its potential impact.
- Steps to reproduce safely, including relevant versions or configuration.
- A minimal proof of concept with sensitive details redacted.
- Any suggested mitigation or fix.

**Never submit live credentials, personal data, or confidential production information.**

## Responsible testing

- Test only systems and data you own or are explicitly authorized to assess.
- Avoid disrupting services, accessing other users' data, or changing production information.
- Do not perform denial-of-service attacks, destructive testing, or social engineering against community members.
- Share findings privately and allow maintainers an opportunity to investigate before public disclosure.

## What happens next

Community maintainers will review reports as volunteer availability allows, attempt to confirm the issue, and coordinate a fix or mitigation when appropriate. We do **not** currently publish a guaranteed response or remediation time, and this policy does not establish a bug-bounty program.

If a vulnerability is confirmed, maintainers may coordinate a security advisory, patch, and disclosure timeline with the reporter. We appreciate clear, respectful communication throughout the process.

## AI-specific security considerations

When contributing AI demos, agents, datasets, or sample applications:

- Keep API keys, tokens, secrets, and private datasets out of commits and examples.
- Treat model outputs, retrieved documents, prompts, and external tool responses as untrusted inputs.
- Avoid publishing personal information or confidential logs in prompts, screenshots, or benchmark data.
- Document material security limitations or risks in demos and examples.

## Further guidance

GitHub documentation: [Privately reporting a security vulnerability](https://docs.github.com/en/code-security/security-advisories/working-with-repository-security-advisories/privately-reporting-a-security-vulnerability).

---

**Thanks for helping keep the AI Tinkerers Luxembourg community and its projects safer.**
