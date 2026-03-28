# Applying the NIST Cybersecurity Framework 2.0 in a Web Development Agency

## 1. Introduction

The NIST Cybersecurity Framework (CSF) 2.0 gives organizations a practical structure for understanding and managing cybersecurity risk. It organizes cybersecurity outcomes into functions, categories, and subcategories that can be adapted to different industries and operating environments.

This report explains how a web development agency can use the CSF to improve its cybersecurity posture. The selected organization is a model firm named H&L Development (HLD), a Montreal-based web development agency specializing in custom enterprise applications, secure authentication portals, cloud-hosted systems, and e-commerce integrations.

HLD operates in an environment where source code, login systems, cloud infrastructure, and personal information all play a central business role. As a result, the company faces threats such as account takeover, data exfiltration, ransomware, supply chain compromise, and leakage of privileged API secrets.

This report shows how HLD can use the NIST CSF to identify its assets and risks, protect against threat actors, detect and respond to incidents, and recover after a cybersecurity event.

## 2. Identify Assets and Associated Risks

The first step is to understand what the organization depends on and what could go wrong. For HLD, several categories of assets are especially important.

The first category includes customer-facing authentication systems. HLD develops login portals for clients, and those systems are exposed to the internet. They are attractive targets for credential stuffing, password spraying, and account takeover attacks. Because those systems often connect to broader application environments, a successful attack on the login layer may become an entry point into more critical infrastructure.

The second category includes cloud-hosted databases and storage systems. These environments may contain customer data, employee data, operational logs, and application data. If an attacker gains access, the organization may face service disruption, extortion, breach notification obligations, reputational damage, and legal consequences.

The third category includes source code repositories and software delivery pipelines. HLD depends on private repositories to build, store, review, and deploy client systems. A compromised developer account or malicious code insertion could lead to a software supply chain incident in which tainted code reaches production environments.

The fourth category includes third-party integrations and privileged secrets such as API keys. Modern web platforms often depend on cloud providers, payment services, analytics tools, identity services, and automation platforms. If a secret is exposed in code or logs, an attacker may be able to abuse cloud resources, access protected services, or create fraudulent transactions.

Using the Identify function, HLD can build an asset inventory, map dependencies, and maintain a risk register. This process helps the company move from vague concern to concrete prioritization. It also supports regulatory awareness, since the organization must understand where sensitive and regulated information resides.

## 3. Protect Against Threat Actors

Once the organization understands its critical assets and major exposures, it can implement controls to reduce the likelihood and impact of attack.

For customer authentication systems, HLD should apply rate limiting, adaptive CAPTCHA, and multi-factor authentication for privileged access. These controls help reduce the effectiveness of automated attacks such as credential stuffing and lower the chance that stolen passwords will result in unauthorized access.

For cloud databases and stored information, HLD should use strong encryption at rest and in transit. Sensitive production data should be encrypted, and key management should be separated from the data it protects. Transport security should be enforced so that external communications are protected from interception and tampering.

For source code and deployment pipelines, HLD should strengthen software platform security. Repository branch protection, mandatory peer review, cryptographic commit signing, least privilege, and separation of duties all help reduce the chance that a compromised account can silently modify production code.

For API keys and service credentials, HLD should eliminate plaintext secrets from source code and local development environments. A centralized secret management service should be used instead. The organization should also scan code before commits or merges to detect exposed secrets early.

These protections should be supported by clear policies and operational discipline. Security is stronger when protective controls are not left to personal habit but are instead embedded into the normal workflow of the organization.

## 4. Detect and Respond to Cybersecurity Events

Protection alone is not enough. HLD must also be able to notice suspicious activity quickly and react in a structured way.

To improve detection, the organization should centralize logging from authentication systems, cloud platforms, repositories, and critical applications. A SIEM or similar monitoring capability can help correlate activity across systems. This makes it easier to spot attack patterns such as repeated failed logins, unusual API usage, unexpected code changes, or suspicious privilege escalation.

Behavioral analysis also improves visibility. By establishing normal activity baselines, HLD can detect deviations that deserve investigation. Examples include abnormal database queries, unexpected administrative actions, or sign-ins from unusual locations and times.

Once suspicious activity is detected, HLD should follow a formal incident response process. The first step is triage and classification. The team must determine what happened, how severe it is, what systems are affected, and whether customer or personal data may be involved.

Next comes containment. If an API key is exposed, the key should be revoked immediately. If an endpoint is under active abuse, malicious traffic should be blocked and affected systems isolated if needed. After containment, the organization works on eradication by removing malicious artifacts, patching vulnerabilities, or resetting compromised credentials.

Communication is also part of response. Technical teams, management, legal stakeholders, and potentially affected clients must be informed in a timely and appropriate way. Documentation is essential throughout the process so that the organization can support investigation, reporting, and later improvement.

## 5. Recover After a Cybersecurity Incident

Recovery focuses on restoring operations in a safe, controlled, and business-aware manner.

For HLD, recovery should begin with a defined recovery plan supported by secure and regularly tested backups. Before restoration, backups should be validated so the organization does not restore corrupted or compromised data. Restoration should follow business priority. Customer authentication systems and payment-related services may need to return first because they have the most direct operational and financial impact.

Recovery is not complete when systems are merely online again. They must return in a trusted state. That means verifying configurations, credentials, logs, and system integrity before declaring recovery complete.

Communication also matters during recovery. Clients and internal stakeholders need clear updates about service status, expected timelines, and any known impacts. This supports trust and reduces confusion during a stressful period.

After service restoration, HLD should conduct a lessons-learned review. The organization should ask what failed, what worked, what controls were missing, and what must change. For example, if the incident began with a leaked API key, then secret management, scanning, and monitoring should be strengthened. In this way, recovery becomes part of continual improvement rather than just a return to the previous state.

## 6. Conclusion

The NIST CSF 2.0 gives HLD a practical and adaptable structure for cybersecurity risk management. By using the framework, the organization can better understand its critical assets, prioritize risk, implement stronger protections, improve visibility, coordinate response, and restore operations after incidents.

In a web development environment where cloud systems, customer authentication, source code, and third-party services are central to the business, the framework helps translate cybersecurity from an abstract goal into specific operational actions. That is the main value of the NIST CSF: it helps organizations move from uncertainty to structured and repeatable cybersecurity practice.