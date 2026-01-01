# Web Application Security Assessment – Talentin

This repository documents an **authorized internal security assessment**
of app.talentin.ai conducted to evaluate both application-level and
cloud-level security risks.

The assessment combines manual web application testing with
cloud activity monitoring to provide a comprehensive view of the
overall security posture.

---

## Scope
- Target: app.talentin.ai
- Environment: AWS cloud infrastructure supporting the application
- Testing type: Passive and low-impact testing

### Focus Areas
- HTTP security headers and configuration
- Authentication and session handling
- Basic input validation (non-destructive)
- Cloud security monitoring using AWS GuardDuty

Activities such as denial-of-service, brute-force attacks, and
destructive testing were explicitly excluded.

---

## Methodology
The assessment follows structured security testing practices aligned with
:contentReference[oaicite:0]{index=0} Top 10 principles.

Application-layer testing was performed using manual request and response
analysis, while cloud-level risks were identified through continuous
monitoring of AWS activity.

Each documented finding includes:
- Tested component or service
- Tool used
- Evidence (screenshots)
- Risk assessment
- Remediation recommendation

---

## Tools Used
- Burp Suite – Web application traffic interception and analysis
- Kali Linux – Security testing environment
- Browser Developer Tools – Client-side inspection
- AWS GuardDuty – Cloud-level threat detection and monitoring

---

## Repository Structure
- `methodology/` – Detailed test cases and practical findings
- `reports/` – Executive-level summaries
- `screenshots/` – Evidence collected during testing
- `authorization.md` – Authorization statement
- `scope.md` – Defined testing boundaries

---

## Disclaimer
This assessment was conducted **with authorization** and is intended
solely for internal security improvement and educational purposes.
