# Hi, I'm Luis Torres 👋

Entry-level IT and cybersecurity learner based in Charlotte, NC. I'm building hands-on skills in Linux, networking, and security analysis, and I document what I learn in small, reproducible labs.

## Credentials

- **Google Cybersecurity Professional Certificate** (Coursera, Sep 2026)
- **CS50's Introduction to Cybersecurity**, HarvardX (2024)
- **CS50's Introduction to Programming with Python**, HarvardX (2024)

## Cybersecurity Labs

Each lab includes the steps, evidence, and findings. Most run in an Ubuntu Linux virtual machine (VirtualBox); labs 06 to 08 add a Kali Linux attacker and a Wazuh SIEM in an isolated host-only network, and the VLAN lab uses Cisco Packet Tracer.

**Featured: labs 06 to 08 form one detection-and-response project.** A real SSH brute-force attack is analyzed by hand, detected with my own Bash script, detected again in a SIEM with a custom rule, and finally contained automatically by blocking the attacker's IP.

| Lab | What I investigated |
|---|---|
| [DNS Investigation](https://github.com/ltorres-security/CyberLab-DNS-Investigation-01) | DNS traffic in Wireshark: A/AAAA records, TTL, and NXDOMAIN responses |
| [TCP, TLS & HTTPS](https://github.com/ltorres-security/CyberLab-TCP-TLS-HTTPS-02) | TCP handshake and TLS 1.3 negotiation, and what stays visible vs. encrypted |
| [Linux Security Logs](https://github.com/ltorres-security/CyberLab-Linux-Security-Logs-03) | Tracing a failed sudo authentication with journalctl and regex |
| [SSH Authentication](https://github.com/ltorres-security/CyberLab-SSH-Authentication-04) | Comparing successful and failed SSH logins in the system logs |
| [Linux Processes & Ports](https://github.com/ltorres-security/CyberLab-Processes-Ports-05) | Tracing a listening TCP port to its process, user, and command |
| [SSH Brute-Force Detection](https://github.com/ltorres-security/CyberLab-SSH-Bruteforce-Detection-06) | Hydra attack from Kali, log analysis, and a custom Bash detection script (MITRE T1110) |
| [Wazuh SIEM Detection](https://github.com/ltorres-security/CyberLab-Wazuh-SIEM-Detection-07) | Wazuh agent and dashboard, why the default brute-force rule missed the attack, and a custom rule that caught it |
| [Wazuh Active Response](https://github.com/ltorres-security/CyberLab-Wazuh-Active-Response-08) | Automatic IP blocking with firewall-drop, verified end to end, including the automatic unblock |
| [VLAN Segmentation](https://github.com/ltorres-security/CyberLab-VLAN-Segmentation) | Isolating a guest PC from clinic PCs with VLANs in Cisco Packet Tracer |

## Skills

- **Systems and tools:** Linux, Bash scripting, SQL, Python (beginner), Wireshark, Nmap, Hydra, Git and GitHub CLI, VirtualBox, Cisco Packet Tracer
- **Security:** log analysis, network traffic analysis, SIEM detection (Wazuh custom rules and active response), IDS fundamentals, MITRE ATT&CK mapping, VLAN network segmentation
- **Languages:** English and Spanish

## Currently

Studying at Central Piedmont Community College and looking for an entry-level IT support or cybersecurity role.

📍 Charlotte, NC
