# Peter Andrews Jr.

### Cloud security and detection engineering · AWS · Splunk · Python · Terraform

I build security projects across the defensive loop: collecting cloud and workload telemetry, turning it into analyst-ready detections, and prototyping human-approved response automation. My software background includes leading development of **MyFitPlate**, a native iPhone and Apple Watch app shipped on the App Store, and my research includes a peer-reviewed IEEE paper on mobile application security and privacy.

I am pursuing cloud security, detection engineering, security automation, DevSecOps, and SOC opportunities.

## Selected Work

### [MyFitPlate](https://github.com/PeteAndrews1289/MyFitPlate)

A production SwiftUI application for nutrition, training, recovery, and evidence-aware coaching. The public repository documents its iPhone and Apple Watch architecture, Firebase and Cloud Functions backend, privacy and security controls, migrations, and automated test suites. [View it on the App Store](https://apps.apple.com/us/app/myfitplate-macro-tracker/id6740922831).

### [AWS DevSecOps Pipeline](https://github.com/PeteAndrews1289/aws-devsecops-pipeline)

A deliberately split supply-chain security case study. It preserves an isolated vulnerable Flask target for teaching evidence while a separate remediated application is protected by tests, Bandit, repository policy checks, and blocking HIGH/CRITICAL Trivy gates. The supporting Terraform and Kubernetes examples use hardened defaults and disclose their decommissioned, reference-only status.

### [Honeypot SIEM Case Study](https://github.com/PeteAndrews1289/honeypot-siem-project)

A completed and decommissioned Cowrie and Conpot study used to analyze real SSH, Telnet, and ICS/SCADA activity in Splunk. Its public evidence package withholds raw identifiers, credentials, commands, and payloads while preserving auditable aggregate results.

### [Detection Engineering Lab](https://github.com/PeteAndrews1289/detection-engineering-lab)

A detection-as-code portfolio with versioned AWS IAM, AWS root, PowerShell, and LSASS hypotheses; synthetic malicious and benign fixtures; a dependency-free matcher; regression tests; and analyst triage playbooks. The checked-in results report four expected fixture matches with no fixture false positives or false negatives, without presenting synthetic validation as production efficacy.

### [AWS Automated SOAR Playbook](https://github.com/PeteAndrews1289/aws-automated-soar-playbook)

A serverless response case study with authenticated webhooks, replay resistance, explicit incident states, human approval, scoped IAM roles, and containment verification. Sixteen tests cover success and failure paths; the original IAM `AccessDenied` outcome remains documented as negative evidence instead of being rewritten as a successful containment claim.

## Research

Co-author, **“A Security and Privacy Assessment of Mobile Ride-Sharing Applications,”** IEEE SoutheastCon 2026. [DOI: 10.1109/SoutheastCon63549.2026.11476248](https://doi.org/10.1109/SoutheastCon63549.2026.11476248)

## Currently Building

[Pokémon Red AI](https://github.com/PeteAndrews1289/pokemon-red-ai) is a reproducible Python and PyBoy harness for controlled game-agent experiments, with ROM validation, automated tests, and private-artifact safeguards.

## Credentials

CompTIA Security+ · Splunk Core Certified Power User · AWS Certified Cloud Practitioner

## Working Principles

- Separate observed evidence from inference.
- Prefer reproducible code, tests, and sanitized data over screenshots alone.
- Keep risky actions human-approved and record failure honestly.
- Destroy temporary cloud and honeypot infrastructure after evidence collection.

> All security projects shown here are controlled educational labs. Completed cloud and honeypot infrastructure was dismantled after evidence collection.
