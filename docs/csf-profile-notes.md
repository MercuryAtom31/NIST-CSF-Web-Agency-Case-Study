# Cybersecurity Framework (CSF) Profile Notes

## Purpose

These notes show how a simplified Cybersecurity Framework (CSF) profile mindset can be applied to H&L Development (HLD).

A CSF profile helps an organization describe:

- where it is now
- where it wants to be
- what gaps it must close

## Scope of this profile

This profile is scoped to the cybersecurity capabilities that support HLD’s core business operations:

- client authentication portals
- cloud-hosted application infrastructure
- customer and operational databases
- software development repositories and pipelines
- third-party service integrations
- incident handling and service restoration

## Simplified current profile

The current state assumed in this case study includes:

- cloud-hosted applications and databases are in place
- development work is stored in private repositories
- the organization relies on API keys and service integrations
- security practices exist but are uneven
- monitoring is limited or fragmented
- incident handling is possible but not fully mature
- backup and recovery exist but require stronger testing and prioritization

## Simplified target profile

The desired future state includes:

- complete and current asset inventory
- formalized risk register
- protected administrative access through MFA
- rate limiting and CAPTCHA on login endpoints
- strong secret management with no plaintext secrets in code
- controlled code changes through branch protection and peer review
- centralized logging and SIEM visibility
- formal incident triage, containment, and communication workflows
- recovery plans tied to backup validation and business priorities
- continuous improvement after each incident

## Priority gaps

The main gaps between current and target state are:

1. Incomplete visibility over assets and dependencies
2. Weak or inconsistent protection of secrets and privileged access
3. Limited centralized detection capability
4. Need for more formal response procedures
5. Need for recovery testing and clearer restoration priorities

## Example action plan

### Near term
- create and maintain asset inventory
- build a risk register
- enforce MFA for privileged accounts
- move secrets into centralized secret management
- enable branch protection and code review

### Mid term
- centralize logging
- create correlation rules for suspicious activity
- define incident severity criteria
- build and test incident runbooks

### Longer term
- perform regular recovery exercises
- map more controls to CSF categories
- expand third-party and supply chain oversight
- refine metrics and dashboard reporting

## Why this matters

The profile approach helps the organization move from vague security intentions to concrete outcomes, priorities, and measurable improvement.
