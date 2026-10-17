# FUTURE_CS_01
Future Interns Cyber Security Task 1 - Vulnerability Assessment Report
# Future Interns — Cyber Security Internship

## Task 1: Vulnerability Assessment Report

### Objective
To perform a preliminary, read-only security review of a public website using browser developer tools.

### Scope
- Public homepage only
- HTTPS and response-header observations
- No login bypass, exploitation, brute force, or denial-of-service testing

### Tools Used
- Google Chrome Developer Tools
- Network tab and HTTP response headers

### Preliminary Observations
- The homepage was accessed over HTTPS.
- The response included `X-Powered-By: PHP/8.2.34` and `Server: hcdn`.
- The visible Content-Security-Policy value included `upgrade-insecure-requests`.
- A `304 Not Modified` response was observed; this is a normal cache response and is not itself a vulnerability.

### Limitations
This was a limited browser-based observation, not a comprehensive vulnerability assessment. The observations do not prove that the website is exploitable. Other security headers were not confirmed from the available evidence.

### Recommendations
- Review the complete Content-Security-Policy against the website’s requirements.
- Remove unnecessary technology-identification headers where practical.
- Verify security configurations with the website owner’s authorization.

### Files
- `FUTURE_CS_Task1_Report.pdf` — assessment report
- `evidence/` — screenshots supporting the observations

**Authorization note:** Confirm permission to assess the target and publish findings before making the report public.
