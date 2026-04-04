# Incident Playbook Template

## 1. Playbook Metadata

- Playbook name:
- Incident type:
- Owner:
- Backup owner:
- Version:
- Last updated:
- Related CSF categories:

## 2. Purpose and Scope

Describe what this playbook covers, which systems are in scope, and when this workflow must be used.

## 3. Activation Criteria

Use this playbook when one or more conditions are true:

- suspicious activity exceeds defined threshold
- privileged credential or secret is exposed
- unauthorized access to critical system is confirmed
- service degradation indicates active security event

## 4. Severity Classification

- Low: limited impact, no sensitive data exposure, minimal business disruption
- Medium: contained impact, possible sensitive data exposure, moderate disruption
- High: major service impact, confirmed sensitive data exposure, legal or client reporting implications

## 5. Roles and Responsibilities

- Incident commander:
- Technical lead:
- Communications lead:
- Legal/privacy contact:
- Executive approver:

## 6. Detection and Validation Checklist

- [ ] Confirm alert source and timestamp
- [ ] Validate indicator quality (false positive or true positive)
- [ ] Identify affected assets and accounts
- [ ] Preserve initial evidence and logs
- [ ] Open incident record with unique incident ID

## 7. Containment Actions

- [ ] Disable compromised accounts or sessions
- [ ] Revoke exposed keys, tokens, or credentials
- [ ] Block malicious IPs or suspicious traffic paths
- [ ] Isolate affected endpoints, workloads, or services
- [ ] Apply temporary controls to prevent further spread

## 8. Eradication Actions

- [ ] Remove malicious artifacts or unauthorized changes
- [ ] Patch exploited vulnerabilities
- [ ] Rotate credentials and secrets
- [ ] Verify access policies and least privilege settings
- [ ] Validate clean state before recovery begins

## 9. Recovery Actions

- [ ] Restore from trusted backup where needed
- [ ] Prioritize business-critical services
- [ ] Validate integrity and security configuration
- [ ] Monitor for reinfection or repeat activity
- [ ] Confirm service restoration with owners

## 10. Communication Plan

### Internal
- stakeholders to notify:
- notification timeline:
- update cadence:

### External
- client communication criteria:
- regulatory/legal notification criteria:
- approved spokesperson:

## 11. Evidence and Documentation

Record and attach:

- incident timeline
- decisions and approvals
- commands/actions executed
- affected assets and data categories
- communication log
- final remediation summary

## 12. Lessons Learned and Follow-Up

- Root cause:
- Control gaps identified:
- Corrective actions:
- Risk register updates:
- Owner and due date for each follow-up action:

## 13. Sign-Off

- Incident commander sign-off:
- Security lead sign-off:
- Business owner sign-off:
- Date closed:
