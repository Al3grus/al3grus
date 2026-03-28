# Hi there, I'm Ricardo 👋
```Cybersecurity Analyst | eJPT 97% | Security Operations | Mastercard · Binance | Brussels```

Security professional with a background in high-security operational environments at Mastercard (cryptographic operations, PKI, PCI compliance) and Binance (AML/KYC fraud investigation, OSINT, pattern analysis and risk escalation). I completed an intensive 6-month cybersecurity bootcamp covering SOC workflows, SIEM operations, PCAP analysis, digital forensics, incident response, and MITRE ATT&CK framework, alongside networking fundamentals and red team methodologies. I hold the eJPT certification (97% score) and ISC2 Certified in Cybersecurity (CC). EU national (Portuguese), Brussels-based, and eligible for EU SECRET security clearance.

---

## 🎯 What I'm Focused On
- Targeting SOC Analyst and Security Operations roles within EU institutions and defence contractors in Brussels
- **Currently building [Argus SOC](https://github.com/Al3grus/Argus-SOC)** — an AI-augmented Security 
  Operations Center on Raspberry Pi hardware

---

## 🔐 Featured Work
🛡️ **[Argus SOC](https://github.com/Al3grus/Argus-SOC)**  |  AI-augmented SOC on Raspberry Pi — 
Wazuh · Suricata · Claude API triage · WireGuard MSSP topology *(in development)*

📂 **[Cybersecurity Portfolio](https://github.com/Al3grus/Cybersecurity-Portfolio)**  |  Comprehensive documentation of my red team and blue team projects and tools

✍️ **[Blog](https://al3grus.github.io)**  |  CTF writeups, certifications & cybersecurity project 
documentation

🏆 **TryHackMe**: Top 4% globally (3M+ users)  |  [Profile](https://tryhackme.com/p/Al3grus)

---

## 🖥️ Home Lab — Argus SOC
Currently building a three-tier AI-augmented SOC that mirrors real MSSP/MDR infrastructure:

**[Argus SOC](https://github.com/Al3grus/Argus-SOC)** *(in development)*
- **Hetzner VPS (argus-soc)** — Cloud SOC platform: Wazuh SIEM (Manager + Indexer + Dashboard), 
  n8n workflow engine, Velociraptor DFIR, Claude API alert triage. Server in Helsinki, Finland — GDPR compliant.
- **Pi 5 (argus-central)** — Client infrastructure: Pi-hole DNS, WireGuard VPN server, 
  Grafana dashboards, MediaMTX RTSP streaming, Frigate AI camera detection, Metasploitable 2 + DVWA (Docker)
- **Pi 3B+ (argus-edge-01)** — MSSP remote edge sensor: Wazuh Agent, Suricata NIDS (SPAN port), 
  Zeek protocol analysis, Cowrie SSH honeypot, Velociraptor agent
- **Cisco SG300-10MP** — Managed switch with hardware SPAN port mirroring for full network visibility
- **ThinkPad T480 (red team)** — Kali Linux VM on isolated guest WiFi, simulating an external attacker
