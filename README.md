# Automated Incident Response Lab (SOAR + EDR using LimaCharlie & Tines)

## Objective
Simulate a real-world credential dumping attack and automate detection and response using EDR and SOAR tools.

## Lab Setup
- Windows 10 Endpoint
- LimaCharlie (EDR)
- Tines (SOAR)
- Slack & Email (alerting)

## Attack Simulation
- Executed Mimikatz to simulate credential dumping
- Triggered suspicious process activity on endpoint

## Detection
- Created custom detection rule in LimaCharlie
- Identified malicious process execution in real time

## Automated Response Workflow
- Alert forwarded to Tines via webhook
- Analyst decision simulated (Yes/No)

### If YES:
- Endpoint isolated automatically
- Alerts sent to Slack & Email

### If NO:
- Event logged for monitoring

## Results
- Successfully detected credential dumping activity
- Automated response reduced manual intervention
- Demonstrated real-world SOAR workflow

## Tools Used
- LimaCharlie (EDR)
- Tines (SOAR)
- Slack API
- Windows Endpoint

## Skills Demonstrated
- Incident Response
- SOAR Automation
- Detection Engineering
- Endpoint Security Monitoring
