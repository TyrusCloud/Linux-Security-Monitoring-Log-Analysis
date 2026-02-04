# linux-security-logging-lab

Linux Security Monitoring & Log Analysis Lab (VMware)

Project Overview

This project implements a controlled Linux-based cybersecurity lab using VMware to demonstrate centralized logging, security event detection, & log analysis aligned with Department of Defense (DoD) Security Operations Center (SOC) workflows.

The lab focuses on host-based monitoring and mirrors real-world SOC visibility and detection processes used in government and contractor environments.

⸻

Target Audience
	•	DoD Hiring Managers
	•	SOC Leads
	•	Cleared Recruiters
	•	Linux / Cybersecurity Roles

⸻

Lab Architecture

Virtualization Platform
	•	VMware Workstation / Fusion

Virtual Machines
	•	Rocky Linux 9 – Monitored system and log source
	•	Ubuntu Server – Centralized logging and analysis system

Networking
	•	NAT-only configuration (isolated, non-production)

Design Rationale
	•	Separation of monitored systems and monitoring infrastructure
	•	Reduced risk through isolation
	•	Alignment with enterprise and DoD SOC architectures

⸻

Project Scope
	•	Lab-only environment
	•	Simulated adversary activity
	•	No external exposure
	•	Focus on authentication and system-level logging

⸻

Methodology
	1.	Baseline Linux systems with minimal installs and administrative users
	2.	Verify system versions and patch levels
	3.	Enable and validate Linux logging services
	4.	Generate controlled security events (failed authentication attempts)
	5.	Implement centralized logging using rsyslog
	6.	Analyze logs for suspicious behavior

⸻

Security Monitoring & Detection

Monitored Events
	•	SSH authentication attempts
	•	Failed login activity
	•	Repeated access patterns

Analysis Techniques
	•	Log filtering and pattern recognition
	•	Time-based clustering of events
	•	Identification of brute-force indicators

⸻


Outcome
	•	Improved visibility into Linux authentication activity
	•	Demonstrated ability to detect → analyze 

⸻

Skills Demonstrated
	•	Linux system administration
	•	Centralized logging and monitoring
	•	Security event detection and analysis
	•	VMware-based lab design
