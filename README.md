# Simulated-threat-port-scan
A hands-on simulation of port scanning detection using Nmap, Snort Wireshark, and UFW

## 🛠 Tools Used
- Kali Linux + Nmap (Attacker)
- Ubuntu + Snort (IDS)
- UFW (Firewall)
- Wireshark (Packet Analysis)

## 🧪 Simulation Summary
- A SYN scan was run from Kali using Nmap
- Snort detected the scan and triggered alerts
- UFW blocked all incoming traffic except SSH
- Wireshark captured traffic for deeper analysis

## 📸 Screenshots
See the `screenshots/` folder for:
- Nmap scan results
- Snort alert logs
- UFW firewall status

## 📄 Report
The full write-up is in `report.pdf`.

## ✅ What I Learned
This project helped me understand real-world network defense: how reconnaissance works and how layered controls can detect and prevent it. Next step: testing Suricata for deeper protocol analysis.
