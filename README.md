# Interactive Phishing Awareness Training

An interactive, browser-based training module that teaches users how to recognize common phishing indicators in realistic email scenarios.

## Project Purpose

Phishing succeeds when users react to urgency, authority, fear, or financial pressure without verifying the request. This project gives users hands-on practice identifying suspicious details before they submit an answer.

## Training Scenarios

The module includes three simulated phishing emails:

1. **Suspicious login alert** — deceptive sender domain, false urgency, account threats, and a look-alike URL
2. **Executive gift-card request** — impersonation, secrecy, financial pressure, and mismatched addresses
3. **IT password reset** — credential requests, deceptive support domain, and time pressure

## Features

- Clickable phishing indicators inside sender, subject, and message fields
- Immediate feedback explaining why an item is suspicious
- Visual highlighting for correct, incorrect, and missed selections
- Per-scenario scoring
- Final assessment and key takeaways
- Responsive design that runs in a modern web browser

## Technologies

- HTML5
- CSS
- Vanilla JavaScript
- Tabler Icons webfont

## Run Locally

1. Download or clone the repository.
2. Open `index.html` in a modern browser.
3. Complete each scenario by selecting every suspected phishing indicator.
4. Review the explanations and final score.

No server-side setup is required.

## Learning Objectives

After completing the module, a user should be better able to:

- Verify sender domains rather than relying on display names
- Recognize look-alike domains and suspicious URLs
- Identify urgency, secrecy, and intimidation tactics
- Reject requests for passwords or other credentials
- Independently verify unusual financial or executive requests
- Escalate suspicious messages to IT or security personnel

## Security Concepts Demonstrated

- Phishing and social-engineering awareness
- Business email compromise indicators
- Credential-harvesting recognition
- User-centered security education
- Interactive assessment design
- Security-control communication

## Responsible Use

All emails, domains, people, and requests shown in this module are simulated for educational purposes. Users should never enter real credentials or other sensitive information into an unverified form or email.

## Future Improvements

- Publish a hosted demonstration
- Add additional scenarios for QR phishing, malicious attachments, and MFA fatigue
- Add randomized questions and a larger scenario bank
- Provide completion reporting without collecting sensitive data
- Map each scenario to relevant MITRE ATT&CK techniques
