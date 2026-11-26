Hi, I'm Muhammad Hasaan 👋

Information Systems student at UMBC working toward a career in cybersecurity, focused on security operations.

I learn security by building systems, attacking them, and investigating what happened in the logs.

Certifications: CompTIA Security+ (SY0-701) · ISC2 Certified in Cybersecurity (CC)

🔐 Featured projects

Splunk SOC Investigation: Web Defacement & Ransomware

Investigated two attacks on a fictional company using Splunk and Splunk's BOTS v1 dataset.

	•	Searched 955,807 events across 22 log sources (IDS, firewall, web, DNS, Sysmon, Windows, registry)
	•	Traced a website takeover from vulnerability scan → brute-forced admin login (412 attempts) → web shell → defacement
	•	Traced Cerber ransomware from a USB drive and macro-enabled Word file to 970 encrypted files on a shared server
	•	Mapped 15 MITRE ATT&CK techniques and wrote detection searches for the attacks

Splunk SPL Sysmon Suricata MITRE ATT&CK Incident Response

IoT Water-System Security Lab

Attacked and then secured a simulated hotel water-monitoring pipeline during my IoT Cyber Defense externship with Extern.

	•	Showed an eavesdropper could read 100% of plain-text traffic, then locked it down with TLS 1.3 and mutual TLS (4/4 identity tests passed)
	•	Blocked 100% of replay attacks in 12 experiments by layering HMAC-SHA256, timestamp and sequence checks
	•	Built a live security dashboard and found a restart flaw that caused 30 false alarms
	•	Tuned an Isolation Forest model from 14 false alarms to 0, then ran rules and AI together on live data

Python MQTT TLS/mTLS PKI HMAC scikit-learn WebSockets

🛠️ Skills

Security Operations: SIEM (Splunk, SPL), log analysis (Sysmon, Windows Event Logs, Suricata IDS), incident investigation, IOC extraction, MITRE ATT&CK
Security: network security, encryption & PKI (TLS/mTLS, X.509), message authentication (HMAC), vulnerability assessment, threat modeling (STRIDE), anomaly detection
Programming & Tools: Python (Pandas, NumPy, scikit-learn, cryptography), Java, C++, PowerShell, Git

📫 Contact

mhasaan2@umbc.edu
