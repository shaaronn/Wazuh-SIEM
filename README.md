# Wazuh-SIEM
A home lab to simulate and detect security events using Wazuh SIEM


# 🛡️ Wazuh SIEM Home Lab Project

## 📌 Overview
This project simulates a SOC (Security Operations Center) environment using Wazuh to monitor, detect, and respond to simulated cyber threats on Linux endpoints.

## 🧱 Architecture
- **Wazuh Manager** on Ubuntu (Host-Only + NAT)
- **Wazuh Agent** on Ubuntu Endpoint
- Communication over Host-Only VirtualBox network

## ⚙️ Setup Process
1. VirtualBox VM setup
2. Wazuh Manager Installation
3. Wazuh Agent Installation
4. Configuring `ossec.conf`
5. Testing agent communication
6. Generating and detecting security events

## 📊 Results
- Agent status: `Active`
- Detected SSH brute-force attacks
- Monitored file modifications
- Created dashboards for alerts and events

## 📷 Screenshots
![Agent Active](screenshots/agent-active.png)
![Alert View](screenshots/alerts-ssh.png)

## 📁 Files Included
- `ossec.conf` samples
- Setup scripts
- Visualizations (if exported)

## 🧠 Lessons Learned
- XML config troubleshooting
- SIEM data flow and network setup
- Wazuh UI dashboard design
