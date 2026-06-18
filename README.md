# Linux Security Monitoring Lab

## Overview

This project documents a Linux Security Monitoring and Incident Investigation home lab built using Ubuntu and Kali Linux.

The objective was to gain hands-on experience with:

* Linux auditing using auditd
* File integrity monitoring
* Privileged command monitoring
* Authentication monitoring
* Incident investigation techniques

---

## Lab Environment

### Ubuntu Server

* Target system
* auditd enabled
* SSH enabled

### Kali Linux

* Client system
* SSH testing
* Authentication testing

---

## Skills Demonstrated

### Auditd Monitoring

* Created audit rules
* Monitored sensitive files
* Generated audit events

### File Integrity Monitoring

* Tracked changes to critical files
* Reviewed audit logs

### Privileged Command Monitoring

* Monitored sudo activity
* Investigated privileged actions

### Authentication Monitoring

* Analyzed failed logins
* Investigated successful SSH logins
* Reviewed authentication logs

### Incident Investigation

* Correlated multiple log sources
* Reviewed authentication events
* Investigated file modifications
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
```

---

## Key Learnings

* How Linux auditing works
* How authentication events are recorded
* How to investigate suspicious activity
* How security analysts collect evidence from logs
* Importance of monitoring privileged actions

---

## Future Enhancements

* Splunk integration
* Centralized log collection
* Detection engineering
* Security dashboards
* Alerting and automation

## Screenshots

The `screenshots` folder contains evidence collected during the lab exercises:

* Auditd service verification
* Audit rule creation
* File change detection
* Failed SSH login detection
* Successful SSH login detection
* Privileged activity investigation
* Login history analysis

These screenshots demonstrate Linux auditing, authentication monitoring, file integrity monitoring, and incident investigation techniques performed during the home lab exercises.

