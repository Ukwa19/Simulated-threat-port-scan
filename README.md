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
- Nmap scan results ![nmap-scan](https://github.com/user-attachments/assets/97c24059-98b2-46f8-b53d-bc704de9ef17)
- Snort alert logs ![snort-alerts](https://github.com/user-attachments/assets/bd1daea6-3bfe-4d61-87ba-1e8bc179c8ec)
- UFW firewall status ![ufw-status](https://github.com/user-attachments/assets/fea1bd4a-1866-4165-9878-d2cf6272a79d)
- Wireshark ![wireshark-nmap-scan](https://github.com/user-attachments/assets/c14901ae-47bb-48d1-8448-20dec701f14a)

## 📄 Report
The full write-up is in `Simulated Threat & Response- Miracle Ukwa.pdf`.
[Simulated Threat & Response- Miracle Ukwa.pdf](https://github.com/user-attachments/files/20501361/Simulated.Threat.Response-.Miracle.Ukwa.pdf)

## ✅ What I Learned
This project helped me understand real-world network defense: how reconnaissance works and how layered controls can detect and prevent it. Next step: testing Suricata for deeper protocol analysis.




