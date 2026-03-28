# Scenario Set

## Scenario 1: Credential stuffing against a customer login portal

HLD hosts a customer-facing authentication portal for one of its enterprise clients. Attackers use previously leaked username and password combinations to automate login attempts from distributed IP addresses.

### Main concerns
- account takeover
- fraudulent access
- reputational damage
- potential access to additional business systems

### Cybersecurity Framework (CSF) use
- **Identify** the portal as a critical internet-facing asset
- **Protect** with rate limiting, MFA for privileged roles, and CAPTCHA
- **Detect** repeated failed logins and abnormal access patterns
- **Respond** by blocking malicious traffic and investigating successful logins
- **Recover** by restoring trust, resetting credentials if needed, and improving authentication monitoring

## Scenario 2: Cloud database exfiltration

An attacker gains access to a cloud environment and begins extracting sensitive customer data from a production database.

### Main concerns
- privacy breach
- regulatory reporting obligations
- loss of trust
- possible extortion or ransomware follow-up

### CSF use
- **Identify** the database as a critical regulated asset
- **Protect** with encryption, least privilege, and tighter access control
- **Detect** unusual query volume and abnormal access behavior
- **Respond** by isolating affected resources and revoking compromised credentials
- **Recover** through validated restoration, security verification, and lessons learned

## Scenario 3: Source code supply chain compromise

A developer account is compromised and used to insert malicious code into a private repository.

### Main concerns
- hidden compromise of production systems
- downstream client impact
- integrity loss in the software delivery lifecycle

### CSF use
- **Identify** the repository and pipeline as critical operational assets
- **Protect** with peer review, branch protection, commit signing, and MFA
- **Detect** suspicious code changes or unexpected branch activity
- **Respond** by disabling the account, rolling back changes, and reviewing deployment history
- **Recover** by restoring trusted code state and strengthening software change controls

## Scenario 4: Leaked API key in source code

A privileged API key is accidentally committed to code and exposed in a public location or shared build log.

### Main concerns
- unauthorized cloud resource use
- cost abuse
- service compromise
- broader lateral movement through integrations

### CSF use
- **Identify** API keys as critical high-impact assets
- **Protect** with secret managers and commit scanning
- **Detect** unusual API use and secret exposure alerts
- **Respond** by revoking and rotating the key immediately
- **Recover** by validating all affected integrations and tightening secret handling practices