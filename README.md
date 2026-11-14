# Recon and Network Scanning Labs

Hands-on write-ups of two early penetration testing phases: **OSINT footprinting with theHarvester** and **network scanning with Zenmap (Nmap)**. Every step has the exact commands, screenshots, saved output and a short explanation, so you can follow along or reuse the structure for your own labs.

## Who this is for

Anyone is free to use this material: students, study groups, instructors, self-learners and organizations running security awareness or training exercises. Copy it, adapt it, or use it as a template for your own lab reports (see the [MIT licence](LICENSE)).

## What is inside

| Folder | What it covers |
| --- | --- |
| [01-theharvester-osint](01-theharvester-osint/) | Finding sub-domains, hosts, IPs and emails for a domain from public sources with theHarvester. |
| [02-zenmap-network-scanning](02-zenmap-network-scanning/) | Finding your own IP and subnet, running a ping scan, listing live hosts and MAC addresses, saving the topology as PDF. |
| [03-pentest-report](03-pentest-report/) | A full report (Word and PDF) combining both labs: methods, evidence, risk analysis, recommendations and limitations. |

## Quick start

1. Read the module README for the lab you want.
2. Run the commands on a machine and network you own or are allowed to test.
3. Compare your results with the screenshots. Results will differ, because networks and online sources change.
4. Reuse the report in `03-pentest-report` as a template for your own findings.

## Requirements

- Kali Linux (theHarvester comes pre-installed) or any system with theHarvester installed.
- Nmap and Zenmap from <https://nmap.org/download.html> for the scanning lab.

## Legal and ethical use

This is for education and research only. Test only systems and networks you own or have written permission to test. The footprinting lab uses public data sources and does not send scanning traffic to the target. The scanning lab was run only on the author's own network. Unauthorised scanning or access is illegal in many countries. The author accepts no responsibility for how this material is used.

