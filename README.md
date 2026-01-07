Windows Forensics — Event Log Analysis (Blue Team)

Project: Investigating Windows Event Logs for Security Incidents

Overview
This repository provides learning material, PowerShell scripts, and Log Parser examples to investigate Windows Event Logs for common security incidents. It's aimed at beginners and SOC/Blue Team learners.

What's included
powershell/collect-eventlogs.ps1 — simple exports and collection helpers.
powershell/search-events.ps1 — quick search and filtering helpers for suspicious Event IDs.
logparser/queries.txt — example Log Parser queries (CSV-based examples).
docs/quickstart.md — how to run the scripts and quick workflow.
detections.md — common Event IDs and what they indicate.
Goals
Teach what Windows Event Logs are and why they matter.
Show how attackers leave traces in logs and how to detect suspicious activity.
Provide reproducible PowerShell recipes for collecting and searching logs.
Usage
Open the docs/quickstart.md to get started. The PowerShell scripts are intended to run on a Windows host (run as Administrator).

License & Notes
Use these scripts for training and incident response exercises. They are intentionally simple — adapt them for production workflows and SIEM ingestion.

Windows-Forensic-1
Repositories contain a project's files and version history. Have a project elsewhere? Import a repository. Required fields are marked with an asterisk (*). Error Repository creation failed.
