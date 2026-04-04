# NIST CSF 2.0 Case Study for a Web Development Agency

## Overview

This repository presents a practical cybersecurity case study showing how a web development agency can apply the NIST Cybersecurity Framework (CSF) 2.0 to manage risk and improve resilience.

The case study is centered on a model organization called **H&L Development (HLD)**, a Montreal-based web development agency that builds secure enterprise web applications, customer authentication portals, cloud-hosted systems, and e-commerce integrations.

The project demonstrates how the organization can use the NIST CSF to:

- identify assets and associated risks
- protect against threat actors
- detect and respond to cybersecurity incidents
- recover after a cybersecurity incident

The repository also includes supporting artifacts that make the work read more like a real GRC package, including a structured risk register, a CSF mapping table, scenario notes, methodology, and references.

## Why this project matters

Modern web development firms handle valuable assets such as source code repositories, cloud databases, payment integrations, privileged API keys, and customer login systems. These assets are attractive to attackers and are also tied to privacy and compliance obligations.

This repository turns a course report into a public cybersecurity case study that can be used as a portfolio artifact for roles related to governance, risk, compliance, cybersecurity analysis, IAM, and application security.

## Organization scenario

H&L Development (HLD) is a fictional organization created for educational and portfolio purposes. It reflects a realistic web development business environment in which the company:

- builds and maintains customer-facing web platforms
- manages cloud infrastructure
- stores sensitive customer and operational data
- uses private version control repositories
- integrates with third-party payment and cloud services
- operates under privacy requirements such as PIPEDA and Quebec Law 25

## Main cybersecurity concerns

The case study focuses on realistic threats that affect this type of organization, including:

- credential stuffing against login portals
- ransomware or data exfiltration affecting cloud databases
- source code compromise through developer account takeover
- API key leakage in source code or deployment pipelines
- weak incident visibility across distributed systems

## Repository contents

### `docs/`
Contains the main report and supporting written material.

### `artifacts/`
Contains practical supporting material such as the risk register, scenario descriptions, CSF mapping table, methodology, and references.

### `diagrams/`
Contains PlantUML source files for colorful architecture and process diagrams.

## How the NIST CSF is used here

The case study uses the NIST CSF 2.0 core functions as the organizing structure:

- **Identify**
- **Protect**
- **Detect**
- **Respond**
- **Recover**

The case study also borrows the CSF profile mindset by describing a practical current-state view, a desired target-state view, and an improvement path.

## Intended audience

This repository may be useful to:

- cybersecurity students
- entry-level GRC or cybersecurity analysts
- IAM learners
- developers learning how security frameworks apply in real environments
- hiring managers reviewing cybersecurity portfolio work

## Disclaimer

This repository is for educational and portfolio purposes. It is not legal advice, not a formal audit, and not a complete security program. The organization described here is fictional, though the risks, controls, and recommendations are based on realistic industry practices and NIST guidance.

## Suggested next improvements

Future versions of this repository could add:

- a fuller CSF profile matrix
- more detailed incident playbooks
- backup and recovery testing evidence
- vendor risk and supply chain assessment artifacts
- a control mapping to NIST SP 800-53 or ISO 27001

## Author intent

This project was created to demonstrate the ability to translate cybersecurity frameworks into practical organizational action using a realistic business scenario.