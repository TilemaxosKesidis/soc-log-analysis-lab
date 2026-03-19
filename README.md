# SOC Log Analysis Lab (Splunk)

##  Project Overview

This project demonstrates a basic Security Operations Center (SOC) workflow using Splunk. The goal was to collect, monitor, and analyze Windows security logs to detect suspicious activity.

##  Tools Used

* Splunk Enterprise
* Sysmon
* Windows Event Logs

##  Lab Setup

* Windows machine (log source)
* Sysmon installed for enhanced logging
* Splunk configured to ingest logs

## Detection Scenario

Detected multiple failed login attempts using EventCode 4625 from Windows Security logs.

## Key Findings

* 95 failed login attempts identified
* Some attempts had no associated username
* Logon ID (0x3E7) indicated SYSTEM-level activity
* Activity likely includes failed authentication attempts and system processes

## kills Demonstrated

* Log analysis
* SIEM usage (Splunk)
* Threat detection
* Basic incident investigation

## Screenshots


## Conclusion

This lab demonstrates the ability to monitor and analyze system logs to identify suspicious behavior, a key skill for a SOC Analyst role.
