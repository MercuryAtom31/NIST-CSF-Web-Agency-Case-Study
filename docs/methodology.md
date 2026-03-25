# Methodology

## Purpose

This case study was developed to show how a realistic organization in the web development sector can apply the NIST Cybersecurity Framework (CSF) 2.0 to practical cybersecurity risk management.

## Selected industry sector

The chosen sector is a web development agency. This sector was selected because it combines several modern cybersecurity concerns in one environment:

- customer authentication systems
- cloud infrastructure
- payment-related integrations
- source code repositories
- third-party service dependencies
- personal information processing

This makes it a strong example for showing how the CSF can be applied in a business setting.

## Organizational scenario

A fictional organization named **H&L Development (HLD)** was used as the model organization. The scenario assumes that HLD:

- develops enterprise web applications for clients
- manages customer-facing authentication portals
- hosts applications and databases in the cloud
- maintains private version control repositories
- uses privileged API keys and third-party integrations
- handles personal data and faces privacy obligations

## Analytical approach

The work was organized around the five CSF functions used in the assignment scope:

1. **Identify**
2. **Protect**
3. **Detect**
4. **Respond**
5. **Recover**

Although CSF 2.0 also includes the **Govern** function, this repository focuses mainly on the assignment’s requested operational areas while still acknowledging that governance supports the whole process.

## Steps followed

### 1. Scope the scenario

The organization’s business model, technology environment, and regulatory context were defined first. This created the boundaries of the case study.

### 2. Identify key assets

The most important information assets and service dependencies were listed, including:

- authentication portals
- cloud databases
- source code repositories
- API keys and service accounts
- payment and cloud integrations

### 3. Identify threat scenarios

Likely and high-impact threats were selected based on the business context. These included:

- credential stuffing
- ransomware
- data exfiltration
- source code tampering
- API key leakage
- supply chain compromise

### 4. Estimate risk

Each asset-threat pair was reviewed in terms of vulnerability, business impact, and likelihood. This was used to produce a practical risk register.

### 5. Map controls to CSF outcomes

Recommended controls were then aligned to CSF functions, categories, and selected subcategories. This helped show how the framework translates into operational action.

### 6. Define detection, response, and recovery actions

The report then described how the organization would monitor for incidents, respond in a structured way, and restore services with business priorities in mind.

## Output artifacts

This repository includes several outputs created from that methodology:

- a narrative report
- an executive summary
- a risk register
- a CSF mapping table
- scenario writeups
- PlantUML diagrams

## Limitations

This case study is intentionally scoped for educational and portfolio purposes. It is not a full audit, not a control implementation guide, and not a formal legal compliance assessment. It shows a structured and realistic application of the NIST CSF, not a complete enterprise security program.