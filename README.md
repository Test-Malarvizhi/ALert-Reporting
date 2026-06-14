# ALert-Reporting
In a SOC Level 1 (Security Operations Center Tier 1) role, alert reporting is one of the most important responsibilities. After triaging and investigating an alert, the analyst documents the findings so that other analysts, incident responders, and management can understand what happened and what actions were taken.

**Purpose of Alert Reporting**

Alert reporting helps to:

Document incidents for future reference.
Communicate findings to SOC L2/L3 analysts or Incident Response teams.
Track trends and recurring threats.
Support compliance and audits.
Create a timeline of security events.

The 5 W's in SOC Alert Reporting

The 5 W's help analysts write clear and complete reports.

1. Who?

Who was involved?

Examples:

User: jsmith
Host: HR-LAPTOP-05
Source IP: 192.168.1.50
Threat actor: FIN7

Example:

User jsmith's account was targeted.

2. What?

What happened?

Examples:

Phishing email received
Malware detected
Brute-force attack observed

Example:

Multiple failed login attempts were detected against the VPN portal.

3. When?

When did it occur?

Examples:

Date
Time
Duration

Example:

Activity occurred on 15 August 2025 at 09:45 UTC.

4. Where?

Where did it happen?

Examples:

Workstation
Server
Cloud account
Network segment

Example:

The activity originated from the VPN gateway and targeted the Finance server.

5. Why?

Why is it important?

Examples:

Credential theft attempt
Malware execution
Unauthorized access

Example:

The attack appears to be an attempt to gain unauthorized access using stolen credentials.

Sample SOC L1 Alert Report
Alert Summary

Alert: Multiple Failed VPN Logins

Who
User: jsmith
Source IP: 203.0.113.25
What
50 failed login attempts detected.
When
15-Aug-2025
09:45–09:55 UTC
Where
Corporate VPN Portal
Why
Possible brute-force attack against user credentials.
Actions Taken
Verified logs in SIEM.
Checked IP reputation.
Escalated to SOC L2 for further investigation.
Severity
High
Status
Escalated
