# Security Investigation Writeups

Practical blue team investigations by **Javier Criado**, based on retired Blue Team Labs Online (BTLO) investigations.

These reports demonstrate my approach to analysing security evidence, correlating findings and documenting the limits of what the available data establishes. They are training projects, not professional incident-response engagements.

> **Spoiler warning:** Contains spoilers and solutions for retired BTLO investigations. All three investigations were confirmed as retired in the BTLO platform.

## Investigations

| Investigation | Focus | Report |
|---|---|---|
| **Drilldown** | Splunk, Sysmon, HTTP telemetry and FortiGate correlation | [Read the PDF](drilldown/Drilldown_Writeup.pdf) |
| **Deep Phish** | Phishing email analysis, network traffic, redirects and JavaScript collection flows | [Read the PDF](deep-phish/Deep_Phish_Writeup.pdf) |
| **Spilled Bucket** | AWS CloudTrail, S3, IAM and VPC Flow Log analysis | [Read the PDF](spilled-bucket/Spilled_Bucket_Writeup.pdf) |

## What the reports demonstrate

- Tracing findings to the evidence that supports them.
- Correlating host, network and cloud telemetry.
- Distinguishing observed activity from assumptions and unresolved questions.
- Documenting indicators, timestamps and investigation limitations.

The reports contain screenshots and technical findings from the lab scenarios. Addresses, domains and identities discussed in the reports are investigation artifacts; their historical appearance does not establish their current status.

## Attribution and scope

Lab scenarios, supplied evidence and lab artwork belong to their respective owners, including Blue Team Labs Online / Centri. The analysis and report narrative are my own writeups. No original lab evidence datasets, virtual machines or certification exam material are distributed in this repository.

BTLO permits writeups after content has officially retired: [publication policy](https://support.blueteamlabs.online/hc/en-gb/articles/11815988264220-Reporting-Suspensions-and-Bans).

## About me

Aeronautical engineer transitioning into technical cybersecurity, with BTL1, eJPT and ISC2 CC certifications. Based in Munich, Germany.

[GitHub profile](https://github.com/jc1-cybersec) · [LinkedIn](https://www.linkedin.com/in/javier-c-a6163a42/)
