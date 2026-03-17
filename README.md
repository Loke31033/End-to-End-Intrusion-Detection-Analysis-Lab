

🔥 SOC Intrusion Detection & Analysis Lab

📌 Overview

This project demonstrates an end-to-end simulation of a cyber attack and its detection from a Security Operations Center (SOC) perspective. It covers the complete attack lifecycle including reconnaissance, exploitation, web attacks, and traffic analysis using industry-standard tools.

⸻

🎯 Objective

To understand attacker behavior and develop practical skills in detecting and analyzing security incidents using network monitoring and security tools.

⸻

🧰 Tools & Technologies Used
	•	Nmap – Network scanning and reconnaissance
	•	Wireshark – Packet capture and traffic analysis
	•	Metasploit – Exploitation framework
	•	Burp Suite – Web application testing

⸻

🖥️ Lab Setup

Component	Description
Attacker Machine	Kali Linux
Target Machine	Metasploitable2
Monitoring Tool	Wireshark


⸻

⚔️ Attack Simulation Workflow

1️⃣ Reconnaissance (Nmap)
	•	Performed network scanning to identify active hosts
	•	Discovered open ports and running services
	•	Detected vulnerable service (vsftpd 2.3.4)

⸻

2️⃣ Exploitation (Metasploit)
	•	Used vsftpd_234_backdoor exploit
	•	Gained command shell access to target system
	•	Demonstrated how attackers compromise systems

⸻

3️⃣ Web Attack (Burp Suite)
	•	Intercepted HTTP login requests
	•	Modified parameters (username/password)
	•	Simulated brute-force login attempts

⸻

4️⃣ Traffic Analysis (Wireshark)
	•	Captured live network traffic during attacks
	•	Identified:
	•	SYN scan patterns
	•	FTP exploitation traffic
	•	Repeated HTTP POST requests

⸻

🚨 Indicators of Compromise (IOCs)
	•	High volume of SYN packets (port scanning)
	•	Suspicious FTP activity
	•	Multiple failed login attempts
	•	Unauthorized shell access

⸻

📊 Key Findings
	•	Outdated services increase attack surface
	•	Network traffic analysis is critical for detection
	•	Attack patterns can be identified through packet-level inspection
	•	Multiple tools combined provide better visibility of threats

⸻

🛡️ Mitigation Strategies
	•	Disable unused ports and services
	•	Patch vulnerable software
	•	Implement firewall rules
	•	Enable Intrusion Detection Systems (IDS)
	•	Use account lockout policies

⸻

📁 Project Structure

soc-intrusion-lab/
│
├── screenshots/
├── report.md
├── nmap_scan.txt
└── README.md


⸻

📸 Screenshots

🔍 Nmap Scan

📡 SYN Scan Detection (Wireshark)

🧨 Exploitation (Metasploit)

🌐 Web Attack (Burp Suite)


⸻

🧠 Skills Gained
	•	Network scanning and enumeration
	•	Packet analysis using Wireshark
	•	Understanding exploitation techniques
	•	Web application attack analysis
	•	SOC-level incident investigation

⸻

🚀 Future Improvements
	•	Integrate SIEM tools like Splunk
	•	Automate alert detection
	•	Simulate advanced attack scenarios

⸻

👨‍💻 Author

Lokeshwar V
Cybersecurity Enthusiast | SOC Analyst Aspirant

⸻

⭐ Acknowledgment

This project was developed as part of hands-on practice to build real-world cybersecurity skills.
