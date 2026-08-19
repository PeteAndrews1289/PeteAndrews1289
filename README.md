# Peter Andrews Jr.

### Cloud security and detection engineering · AWS · Splunk · Python · Terraform

I build security projects across the defensive loop: collecting cloud and workload telemetry, turning it into analyst-ready detections, and prototyping human-approved response automation. My software background includes leading development of **MyFitPlate**, a native iPhone and Apple Watch app shipped on the App Store, and my research includes a peer-reviewed IEEE paper on mobile application security and privacy.

I am pursuing cloud security, detection engineering, security automation, DevSecOps, and SOC opportunities.

## Selected Work

### [MyFitPlate](https://github.com/PeteAndrews1289/MyFitPlate)

A production SwiftUI application for nutrition, training, recovery, and evidence-aware coaching. The public repository documents its iPhone and Apple Watch architecture, Firebase and Cloud Functions backend, privacy and security controls, migrations, and automated test suites. [View it on the App Store](https://apps.apple.com/us/app/myfitplate-macro-tracker/id6740922831).

### [AWS DevSecOps Pipeline](https://github.com/PeteAndrews1289/aws-devsecops-pipeline)

A deliberately split supply-chain security case study. It preserves an isolated vulnerable Flask target for teaching evidence while a separate remediated application is protected by tests, Bandit, repository policy checks, and blocking HIGH/CRITICAL Trivy gates. The policy checker is itself tested — 22 cases that break one control at a time — which is how a real gap surfaced: unpinned GitHub Actions written in the compact `- uses:` form were passing the SHA-pinning gate unchecked.

### [Honeypot SIEM Case Study](https://github.com/PeteAndrews1289/honeypot-siem-project)

A completed and decommissioned Cowrie and Conpot study used to analyze real SSH, Telnet, and ICS/SCADA activity in Splunk. Its public evidence package withholds raw identifiers, credentials, commands, and payloads while preserving auditable aggregate results — and the redaction is proven rather than asserted: the test suite feeds the builder recognisable addresses, a download URL, and a path to a private key, then checks none of it survives into any output file.

### [Detection Engineering Lab](https://github.com/PeteAndrews1289/detection-engineering-lab)

Detection-as-code across AWS CloudTrail, Windows Sysmon, Windows Security, and Okta: 28 versioned hypotheses covering 23 ATT&CK techniques, each with a conditional mapping, documented false positives, tuning guidance, and analyst triage steps. A dependency-free matcher scores them against 71 synthetic fixtures, 32 of them benign near-misses written specifically to try to make the rules misfire. The catalog also exports to Sigma, and a replay harness reports alert volume, throughput, and any rule that has gone silent. Zero fixture false positives is reported as exactly that — a regression signal, not production efficacy.

### [AWS Automated SOAR Playbook](https://github.com/PeteAndrews1289/aws-automated-soar-playbook)

A serverless response case study with authenticated webhooks, replay resistance, explicit incident states, human approval, scoped IAM roles, and containment verification. The request-authentication boundary is covered by 38 tests that attack each assumption individually — modified bodies, flipped bytes, swapped timestamps, both edges of the replay window, and cross-protocol signature confusion. The original IAM `AccessDenied` outcome remains documented as negative evidence instead of being rewritten as a successful containment claim.

## Autonomous Systems & Reliability

These projects show how I move from controlled experimentation to product engineering: preserve negative evidence, identify the reliability boundary, and encode that lesson into deterministic, observable software.

### [Dungeon Apprentice — Cumulative-Learning Research](https://github.com/PeteAndrews1289/dungeon-apprentice)

A completed recurrent-PPO study with procedural solvability checks, disjoint evaluation suites, checkpoint integrity, and preregistered promotion gates. Strong average capability did not eliminate rare catastrophic interaction loops, so the study closed without promoting an unreliable architecture.

### [Dungeon Apprentice — Deterministic Godot Prototype](https://github.com/PeteAndrews1289/dungeon-apprentice-game)

A completed systems-rich vertical slice where players compose party playbooks, seal orders, observe autonomous expeditions, and audit evidence-grounded outcomes. The deterministic simulation remains independent of rendering, playback speed, and UI state.

### [Pokémon Red AI — Experiential-Learning Research](https://github.com/PeteAndrews1289/pokemon-red-ai)

A completed study of whether one randomly initialized recurrent visual policy could turn self-generated experience into cumulative game skills. V12 processed 8.24 million actions across four emulators and replay-verified seven milestones through Route 1, yet frozen evaluation ended at 55/502 with zero retained competent skills and no composition—evidence that discovery and training activity are not the same as durable competence.

## Research

Co-author, **“A Security and Privacy Assessment of Mobile Ride-Sharing Applications,”** IEEE SoutheastCon 2026. [DOI: 10.1109/SoutheastCon63549.2026.11476248](https://doi.org/10.1109/SoutheastCon63549.2026.11476248)

## Credentials

CompTIA Security+ · Splunk Core Certified Power User · AWS Certified Cloud Practitioner

## Working Principles

- Separate observed evidence from inference.
- Prefer reproducible code, tests, and sanitized data over screenshots alone.
- Keep risky actions human-approved and record failure honestly.
- Destroy temporary cloud and honeypot infrastructure after evidence collection.

> All security projects shown here are controlled educational labs. Completed cloud and honeypot infrastructure was dismantled after evidence collection.
