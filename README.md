# Log Analysis & Alerting Tool for a Retail Chain

## Overview

A security monitoring and alerting prototype developed using **Wazuh SIEM** for a simulated retail chain environment.

The project demonstrates how endpoint security events can be collected, analyzed, and detected through a centralized SIEM platform.

## Tools Used

* Wazuh SIEM
* Kali Linux
* VirtualBox
* Linux system logs
* MITRE ATT&CK

## Detection Scenarios

Five security-related activities were tested and documented:

1. Failed SSH login using a non-existent user
2. New local user account creation
3. File integrity monitoring
4. Privileged command execution using `sudo`
5. Filesystem search activity using `find`

Detailed detection procedures, Wazuh alerts, evidence, security significance, and recommended response steps are provided in the project report.

## Lab Environment

* **Wazuh Server:** `192.168.100.232`
* **Agent:** Kali-Lab
* **Host:** Windows + VirtualBox

## Project Structure

```text
Log-Analysis-Alerting-Tool/
├── Wazuh Detection Report.docx
├── README.md
└── Screenshots/
    ├── Detection-1/
    ├── Detection-2/
    ├── Detection-3/
    ├── Detection-4/
    └── Detection-5/
```

## Disclaimer

This project was conducted in a controlled virtual lab environment for educational and demonstration purposes.

