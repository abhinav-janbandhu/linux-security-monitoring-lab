# Linux Security Monitoring Lab

## Overview

This project documents a Linux Security Monitoring and Incident Investigation home lab built using Ubuntu and Kali Linux.

The objective was to gain hands-on experience with Linux auditing, authentication monitoring, privileged activity monitoring, file integrity monitoring, and basic incident investigation techniques commonly used by security operations teams.

---

## Lab Environment

### Ubuntu Server

* Target system
* auditd enabled
* SSH enabled
* Authentication and system logs analyzed

### Kali Linux

* Client system
* SSH connectivity testing
* Failed and successful login simulation
* Activity generation for investigation exercises

---

## Skills Demonstrated

### Auditd Monitoring

* Configured auditd monitoring
* Created audit rules
* Generated and reviewed audit events

### File Integrity Monitoring

* Monitored changes to sensitive files
* Reviewed audit logs
* Investigated file modification events

### Privileged Command Monitoring

* Monitored sudo activity
* Investigated privileged actions
* Reviewed authentication and privilege escalation logs

### Authentication Monitoring

* Analyzed failed login attempts
* Investigated successful SSH logins
* Reviewed login history and authentication events

### Incident Investigation

* Correlated multiple log sources
* Reviewed authentication activity
* Investigated privileged user actions
* Analyzed file modification events
* Produced findings and conclusions

---

## Key Commands Used

```bash
auditctl -l
ausearch
last
lastb
who
grep "Failed password" /var/log/auth.log
grep "Accepted password" /var/log/auth.log
grep sudo /var/log/auth.log
```

---

## Key Learnings

* Understanding how Linux auditing works with auditd
* Monitoring authentication activity and login events
* Investigating failed and successful SSH access attempts
* Tracking privileged user activity
* Collecting and correlating evidence from multiple log sources
* Applying basic incident investigation techniques on Linux systems

---

## Future Enhancements

* Splunk integration
* Centralized log collection
* Detection engineering use cases
* Security dashboards and reporting
* Alerting and automation
* SIEM-based monitoring and investigations

---

## Screenshots

The `screenshots` folder contains evidence collected during the lab exercises, including:

* Auditd service verification
* Audit rule creation
* File change detection
* Failed SSH login detection
* Successful SSH login detection
* Privileged activity investigation
* Login history analysis

These screenshots demonstrate Linux auditing, authentication monitoring, file integrity monitoring, privileged activity monitoring, and incident investigation techniques performed during the home lab exercises.
