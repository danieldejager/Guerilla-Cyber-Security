### 🧠 Persona 3: Engineers (Infrastructure, Network, Cloud)

| Scenario | Comeback | Professional Reframe |
|----------|----------|------------------------|
| Disable logging to improve performance | "Performance isn’t an excuse for blindness." | "Let’s optimize logs, not eliminate visibility—security needs insight." |
| Use default admin accounts in prod | "Default creds are default breach vectors." | "Let’s implement named accounts for accountability and audit integrity." |
| Store secrets in plain text | "You may as well hand them to an attacker." | "Let’s enforce secure credential storage as part of CI/CD hygiene." |
| Deploy infra before risk review | "Speed without review is just risk at scale." | "Let’s embed pre-deployment risk checks into the process." |
| Skip patching cycles due to resource constraints | "Unpatched is unprotected." | "Let’s prioritize patching based on asset criticality and exposure." |
| Hardcode credentials in scripts | "That’s not automation—it’s a liability factory." | "Use vaults or secret managers—scripts should never store credentials." |
| Open firewall ports for convenience | "Convenience to you is exposure to them." | "Every exception should be reviewed for legitimate use and time-bounded." |
| Avoid SIEM integration due to log noise | "Noise is fixable—breaches are not." | "We can tune the SIEM, but visibility must remain non-negotiable." |
| Skip TLS cert renewals | "Expired certs don’t just break things—they invite impersonation." | "Let’s automate renewals to maintain availability and trust." |
| Roll back MFA during outages | "Temporarily vulnerable is still vulnerable." | "We need a failover that preserves access security during incidents." |
| Refuse to tag cloud assets | "If we can’t find it, we can’t defend it." | "Let’s implement tagging standards for inventory and response." |
| Use personal GitHub repos | "Personal repos for company code? That’s called exfiltration." | "We need central, monitored repositories for corporate IP protection." |
| Claim security breaks their automation | "Bad automation is just fast failure." | "Security and automation must coexist—let’s collaborate on solutions." |
| Don't review role-based access in AD | "Outdated access is an attacker’s favorite door." | "Let’s schedule regular RBAC reviews to maintain least privilege." |
| Ignore conditional access configs | "Ignoring policy doesn’t make it go away—it makes it risky." | "We’ll partner with you to validate configs that balance access and safety." |
| Miss change control reviews | "Skipping change control? That’s how incidents happen." | "Let’s ensure security sign-off is embedded in your workflow." |
| Reject vulnerability severity levels | "The scanner isn’t trying to annoy you—it’s warning you." | "We’ll validate severity collaboratively—but let’s not dismiss warnings." |
| Apply quick fixes instead of remediating root cause | "Band-aids don’t stop breaches." | "Let’s document short-term fixes with a ticket for full remediation." |
| Blame vendors for misconfigurations | "Vendors sell tools—we configure them." | "Let’s align on shared responsibility and tighten implementation standards." |
| Don’t document their changes | "If it’s not documented, it’s a ghost change." | "We need traceability—especially in production environments." |
| Engineers | Refuses to deploy endpoint/security agents, says it's security’s job | "Security doesn’t have access, permissions, or the operational mandate—*you* do. If you want documentation, we’ll write it. But the onus sits with the accountable team, and that’s not us." | "Security teams will provide the