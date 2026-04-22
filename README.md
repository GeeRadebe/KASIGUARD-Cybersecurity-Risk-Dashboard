# 🛰️ KASIGUARD | Defensive Risk Matrix
**Status:** Active Monitoring
**Classification:** SME Cybersecurity Assessment Engine

### 0x01 Mission
KasiGuard is an automated adversarial risk assessment engine built to secure South African SMEs. It translates complex security vulnerabilities into a weighted "Defense Score," providing a tactical roadmap for infrastructure hardening.

### 0x02 The Risk Engine
The system utilizes a weighted heuristic scoring matrix:
- **MFA_STATUS (30%):** Validates multi-factor authentication across cloud nodes.
- **BACKUP_INTEGRITY (25%):** Checks for air-gapped or redundant data backups.
- **NETWORK_SEC (20%):** Evaluates segmentation between public and private traffic.
- **HYGIENE (25%):** Assesses patch management and user awareness metrics.

### 0x03 Stack
- **Interface:** Power Apps (Low-Code/High-Impact UI).
- **Automation:** Power Automate for real-time PDF threat reporting.
- **Dataverse:** Secure storage of telemetry and assessment history.
- **API Integration:** External threat intelligence feeds for real-time IP/Domain reputation checks.

### 0x04 Operational Use
Run the `Assessment_Module` to generate a system-wide vulnerability report. Follow the `Remediation_Path` generated in the PDF output to increase the Defense Score.
