# Cloud Security Monitoring – AWS GuardDuty

## Overview
AWS GuardDuty was enabled to monitor cloud activity
related to the application during the assessment period.

GuardDuty analyzes AWS CloudTrail, VPC Flow Logs,
and DNS logs to identify suspicious behavior.

---

## GuardDuty Finding Summary

**Finding Type:** <redacted>  
**Severity:** Low / Medium / High  
**Affected Service:** <IAM / EC2 / VPC / API>  

### Description
GuardDuty detected anomalous activity indicating
potential cloud-level security risks.

Specific identifiers have been redacted to protect
sensitive infrastructure details.

---

## Evidence

Multiple AWS GuardDuty findings were identified during the monitoring period.

### SSH Brute Force Attempts
![SSH Brute Force](../screenshots/guardduty-ssh-bruteforce.png)
![SSH Brute Force (Additional)](../screenshots/guardduty-ssh-bruteforce-2.png)

### RDP Brute Force Attempt
![RDP Brute Force](../screenshots/guardduty-rdp-bruteforce.png)

### EC2 Instance Probing
![EC2 Probing](../screenshots/guardduty-ec2-probed.png)

### RDS Database Access Attempt
![RDS Database Activity](../screenshots/guardduty-rds-database.png)

---

## Impact Assessment
The finding highlights risks at the cloud infrastructure
level that are not visible through application-layer
testing tools.

No confirmed application exploitation was identified.

---

## Recommendations
- Review IAM roles and permissions
- Investigate the source of the activity
- Enable alerting and automated response where appropriate
