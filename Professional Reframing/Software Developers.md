### 🧠 Persona 6: Software Developers

| Scenario | Comeback | Professional Reframe |
|----------|----------|------------------------|
| Skip input validation | "If you won’t validate input, the attackers will." | "Input validation is the first line of defense—let’s make it standard." |
| Push code directly to prod | "Straight to prod? That’s bold... and breach-prone." | "Let’s follow the deployment pipeline—QA and staging exist for a reason." |
| Don’t sanitize SQL queries | "Inject now, regret later." | "Prepared statements or ORMs reduce risk—let’s standardize secure query handling." |
| Disable secure headers for UI speed | "Fast isn’t secure if it gets intercepted." | "We’ll tune headers to optimize speed and maintain baseline security." |
| Refuse to use secure coding guidelines | "Guidelines don’t slow you down—breaches do." | "Let’s embed OWASP practices into peer reviews and onboarding." |
| Don’t rotate API keys | "If the key never changes, neither does the risk." | "We’ll schedule rotations and automate key lifecycle management." |
| Hardcode AWS keys into app config | "Might as well send attackers a welcome letter too." | "Let’s move secrets to vault-managed storage immediately." |
| Build without threat modeling | "No map? Then you’re coding in the dark." | "Let’s integrate lightweight threat modeling into sprint planning." |
| Use outdated libraries with known CVEs | "If the attacker knows the bug, you're already behind." | "We’ll scan dependencies continuously and prioritize critical CVEs." |
| Turn off CSP to 'debug faster' | "Debug mode shouldn't become breach mode." | "Let’s debug in a hardened sandbox—not in the wild." |
| Don’t log auth events | "No logs = no trail = no clue." | "Let’s log key events to support detection and investigation." |
| Misuse JWT with weak signing | "Unsigned tokens = signed breach warrants." | "We’ll standardize strong algorithms and enforce expiration checks." |
| Don’t encrypt sensitive fields at rest | "Plaintext storage is plain negligence." | "Let’s enforce encryption-at-rest as a minimum control." |
| Bypass OAuth2 for speed | "Skipping security for speed just gets you compromised faster." | "OAuth2 is proven—let’s lean into secure patterns." |
| Forget to implement session expiry | "Endless sessions = endless exposure." | "Let’s define session timeouts by sensitivity of function." |
| Leave error messages verbose | "Verbose errors are a gift to attackers." | "Let’s sanitize user-facing errors and log the details server-side." |
| Ignore CSRF protection in frontends | "That token you skipped? That’s your protection." | "CSRF tokens are a standard defense—easy to implement, hard to regret." |
| Build PoCs using prod data | "That’s not a PoC—that’s a privacy breach." | "We’ll enforce data masking and synthetic alternatives in test environments." |
| Say 'It works on my machine' | "Too bad prod isn’t your laptop." | "We’ll align dev, staging, and prod environments for better reliability." |
| Claim security should be handled by the infra team | "Security isn’t a department—it’s a discipline." | "DevSecOps means shared ownership—let’s align code and control together." |
