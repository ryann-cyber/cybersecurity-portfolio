# Linux Authentication Log Analysis

## Scenario
This project analyses Linux authentication logs to identify suspicious
login activity and demonstrate how an L1 SOC analyst would triage and
assess potential security incidents.

## Environment
- Platform: TryHackMe.com
- OS: Linux
- Log source: Authentication logs

## Alert / Suspicion
Multiple failed login attempts were observed within a short time window,
indicating potential brute-force activity.

## Investigation Steps
- Reviewed authentication logs
- Identified repeated failed login attempts
- Checked source patterns and frequency
- Assessed likelihood of malicious activity

## Outcome
The activity was classified as suspicious and would be escalated to
a higher-tier analyst for further investigation.

## What I Learned
- How authentication failures appear in Linux logs
- Why repeated login attempts are a security concern
- How SOC analysts decide when to escalate incidents
