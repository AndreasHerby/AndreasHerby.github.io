---
layout: default
title: Home
---

# <u> Home Page and About Me </u>

I am a first-year cybersecurity student at Leeds Beckett University focused on building practical security systems. This site documents hands-on projects and applied learning across multiple areas of cybersecurity beyond formal coursework.

<br>

# <u> Project Navigation </u>

This page highlights selected security engineering projects focused on cloud security, malware analysis, and defensive automation.
Each project is designed to reflect real-world threat models, production constraints, and security best practices.



## <u> 1. Secure Malware Ingestion & Analysis Pipeline </u>

My documentation: *[Malware pipeline documentation](projects/malware_pipeline.md)*

This project implements an end-to-end malware ingestion and analysis pipeline modeled after production-grade security platforms.
The system is designed to safely accept untrusted artifacts, enforce strict custody controls, perform layered analysis, and produce actionable security insights.

The pipeline is built in phases, each introducing additional capability while maintaining strong security boundaries.

**Highlights**:

- End-to-end malware analysis pipeline with controlled ingestion, secure quarantine, and automated analysis
- Cryptographic hashing and chain-of-custody tracking to preserve file integrity
- GUI-based interface for ingestion, analysis monitoring, and results review
  
<br>

## <u> 2. VLAN-Based Enterprise Network Design

My documentation: *[Enterprise network documentation](projects/enterprise_network.md)*

This project demonstrates the design and security hardening of a small enterprise-style network using Cisco Packet Tracer. It includes VLAN segmentation, inter-VLAN routing, access control with ACLs, and secure network device management following enterprise best practices.

**Highlights**

- Designed a small enterprise network with logical segmentation using multiple VLANs for users, administrators, servers, and management traffic
- Implemented inter-VLAN routing with a router-on-a-stick architecture and 802.1Q trunking between network devices
- Applied Access Control Lists (ACLs) to enforce least-privilege communication and restrict traffic between VLANs
- Secured network device management by disabling Telnet, enabling SSH, and limiting administrative access to the Admin VLAN
- Hardened the network by disabling unused switch ports and reducing the overall attack surface

# <u> Coming soon </u>

## <u> 2. Cloud Identity Abuse Detection </u>

A detection engineering project focused on identifying cloud identity abuse techniques such as privilege escalation, anomalous token usage, and persistence through IAM misconfiguration.

-----------------------------------------------------------------------------------

## <u> 3. AI-Driven Phishing Detection System </u>

An AI-driven phishing detection system designed to identify malicious emails using a combination of natural language processing, feature engineering, and classification models.


