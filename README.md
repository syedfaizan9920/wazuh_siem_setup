# 🛡️ Wazuh SIEM + Windows Log Monitoring – Beginner SOC Analyst Project

![Wazuh](https://img.shields.io/badge/Wazuh-SIEM-blue) ![Windows](https://img.shields.io/badge/Windows-Agent-green) ![VirtualBox](https://img.shields.io/badge/VirtualBox-Setup-orange) ![SOC](https://img.shields.io/badge/SOC-Analyst-yellow)

> **Created by:** Faizanullah Syed  
> **Email:** faizanullah.syed19@gmail.com  

## 📌 Project Overview

This project demonstrates how to deploy the **Wazuh SIEM platform** using a pre-built OVA in **VirtualBox**, and integrate a **Windows agent** to collect and monitor logs in real time.

✅ Ideal for beginners preparing for a **SOC Analyst role** or learning SIEM basics.  
✅ No cloud or paid tools needed – fully offline and lightweight.

---

## 🧰 Tools & Technologies Used

- [Wazuh OVA](https://documentation.wazuh.com/current/deployment-options/virtual-machine/index.html)
- VirtualBox (Local VM setup)
- Windows OS (as the agent)
- Pastebin (for transferring install commands)
- Wazuh Web Interface (Browser-based access via HTTPS)

---

## 🎯 Objectives

- Set up a functional SIEM environment with **Wazuh Manager**
- Deploy a **Wazuh Agent on Windows**
- Securely connect the agent and verify **log collection**
- Use **Wazuh Dashboard** to monitor and analyze events

---

## 🛠️ Setup Steps

### 1. Wazuh Installation

- Import Wazuh `.ova` file into VirtualBox
- Start the VM and get the IP address
- Access the dashboard in your browser:  
  `https://<wazuh-vm-ip>`
- Login with default credentials, then change the password

### 2. Access Agent Management

- Click the **☰ Menu**
- Go to **Agent Management → Summary**
- Here you will monitor registered agents

### 3. Install Windows Agent

- On your Windows machine, download the Wazuh agent installer
- Use **Pastebin** to copy the registration command from Wazuh VM to Windows easily
- Run the command in **CMD as Administrator**
- Agent registers with the Wazuh Manager automatically

### 4. Confirm Agent Status & Logs

- Go back to **Agent Summary** on the Wazuh Dashboard
- Confirm the Windows agent is **active (green status)**
- Check logs under Security, System, and Application

---

## ✅ Project Outcome

- Fully working Wazuh setup with Windows logs being received in real-time
- All agent logs visible on the Wazuh dashboard
- Ready to expand with more agents, alerts, and rule tuning

---

## 💡 What I Learned

- End-to-end deployment of an open-source SIEM
- How agents send logs to a central manager
- Hands-on log analysis skills for SOC Analyst preparation
- VirtualBox networking, HTTPS access, and basic troubleshooting

---

## 📈 Keywords for SEO (Recruiter Friendly)

`SOC Analyst`, `SIEM`, `Wazuh Project`, `Windows Log Monitoring`, `Beginner Cybersecurity Project`, `VirtualBox OVA`, `SIEM Use Case`, `Cybersecurity Resume Project`, `Wazuh Agent`, `SIEM Dashboard`, `Security Operations Center`, `Open-source SIEM`, `Endpoint Monitoring`

---

## 📂 Project Status

🟢 **Completed**  
📘 Basic SIEM Use Case  
🔒 Ready for demo or interview walkthrough  

---

## 📧 Contact

If you'd like to collaborate, ask questions, or view the full PDF guide:

📨 Email: **faizanullah.syed19@gmail.com**  
🔗 LinkedIn: *LinkedIn.com/in/faizanullah-syed*

---

## ⭐ If this project helped or inspired you, give it a star and fork !


