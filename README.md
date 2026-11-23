# Reyts Fintech Security Assessment

**Fintech security simulation | Splunk investigation | Threat analysis**

## Overview

This repository documents work completed during the Amdari Cybersecurity Hackathon 2026, powered by Reyts Fintech.

The project combined security testing scenarios with investigation of authentication and transaction activity in a controlled fintech simulation. The work was presented as part of a team hackathon submission.

## Investigation Work

The log-analysis work involved:

- Approximately **17,169 authentication events**
- Approximately **7,768 transaction records**
- Splunk investigation using the `reyts_auth` and `reyts_txs` data sources
- Correlation of suspicious activity and reconstruction of event timelines
- Review of account-takeover, phishing, and ransomware-related scenarios within the simulation

The hackathon also included a KYC-bypass scenario involving deepfake-based techniques. This should be understood as a simulated attack scenario, not a claim of compromise of a live financial institution.

## What the Project Demonstrates

- Working with sizeable authentication and transaction datasets
- Searching and correlating events in Splunk
- Investigating identity-related attack scenarios
- Building an evidence-led incident narrative
- Communicating security observations and recommendations

## Tools and Frameworks

- **Splunk:** log search, filtering, and event correlation
- **Python:** supporting data analysis
- **MITRE ATT&CK:** structuring adversary behaviour and investigation notes
- **OSINT techniques:** supporting threat research where applicable

## Report

The detailed report is available in this repository:

[Fintech Security Assessment Report](Fintech_Security_Assessment_Pentest_SOC_ThreatIntel.docx)

## Project Context and Limitations

This work was completed in a controlled hackathon environment using supplied simulation data and scenarios. It is not an independent audit of Reyts production infrastructure, and the scenarios should not be interpreted as confirmed real-world incidents.

## Author

[GitHub – JK-xpinn](https://github.com/JK-xpinn)  
[LinkedIn](https://www.linkedin.com/in/joseph-adekunle-87600b295)  
[Medium](https://medium.com/@spinnnate7)
