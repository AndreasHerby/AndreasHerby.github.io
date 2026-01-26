---
layout: default
title: Projects
---

# <u> Projects </u>

This page highlights selected security engineering projects focused on cloud security, malware analysis, and defensive automation.
Each project is designed to reflect real-world threat models, production constraints, and security best practices.

## <u> 1. Secure Malware Ingestion & Analysis Pipeline </u>

Documentation: [Malware pipeline documentation](projects/malware_pipeline.md)

This project implements an end-to-end malware ingestion and analysis pipeline modeled after production-grade security platforms.
The system is designed to safely accept untrusted artifacts, enforce strict custody controls, perform layered analysis, and produce actionable security insights.

The pipeline is built in phases, each introducing additional capability while maintaining strong security boundaries.

Key Capabilities:
- Controlled ingestion of untrusted files
- SHA-256-based identification and deduplicaiton
- File-type detection via magic bytes
- Quarantine enforcement with non-executable storage
- Persistent chain-of-custody logging


# <u> Coming soon </u>

## <u> 2. Cloud Identity Abuse Detection </u>

A detection engineering project focused on identifying cloud identity abuse techniques such as privilege escalation, anomalous token usage, and persistence through IAM misconfiguration.

-----------------------------------------------------------------------------------

## <u> 3. AI-Driven Phishing Detection System </u>

An AI-driven phishing detection system designed to identify malicious emails using a combination of natural language processing, feature engineering, and classification models.


[back](./)
