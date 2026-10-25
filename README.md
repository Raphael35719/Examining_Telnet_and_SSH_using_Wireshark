# Examining Telnet and SSH Using Wireshark

## Project overview
This project examines Telnet and SSH traffic with Wireshark, focusing on confidentiality and what packet captures reveal.

## Objectives
- Capture and inspect Telnet and SSH traffic in an authorized lab.
- Compare what is visible in packet captures.
- Document actual observations with screenshots and captures.
- Explain why SSH is generally preferred for remote administration.

## Repository structure
- `docs/` — report, methodology, and findings.
- `evidence/screenshots/` — Wireshark screenshots.
- `evidence/captures/` — reviewed packet captures.
- `src/` — optional helper scripts or configuration.
- `references/` — sources used.
- `logs/` — optional sanitized lab logs.

## Safety and privacy
Capture only systems and networks you own or are explicitly authorized to test. Do not publish credentials, private keys, personal information, or other people's traffic. Inspect captures before publishing because packet captures can contain sensitive data.

## High-level comparison
Telnet does not encrypt its session, so application data may be visible in a capture. SSH encrypts the session; Wireshark can show metadata and protocol exchanges, but normally cannot read protected application content.

## Status
Project completed. Replace or extend this starter README with your actual setup, findings, and evidence.
