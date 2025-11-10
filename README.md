# wazuh-siem-deployment
Hands-on project deploying and configuring Wazuh SIEM on Ubuntu VirtualBox. Includes setup logs, dashboard screenshots, and active agent monitoring for endpoint security.

# Wazuh SIEM Deployment Project

This project demonstrates the deployment and configuration of the **Wazuh Security Information and Event Management (SIEM)** platform on **Ubuntu (VirtualBox)** as part of a hands-on cybersecurity lab.

## 🧰 Project Overview
- Installed and configured **Wazuh Indexer, Manager, Filebeat, and Dashboard**
- Connected and monitored a **Windows Agent** for endpoint security
- Validated threat detection, file integrity monitoring, and vulnerability assessment modules
- Captured configuration and dashboard screenshots as implementation evidence

## 📸 Screenshots
All screenshots of the setup and configuration process are available in the [`/screenshots`](./screenshots) folder.

| Installation | Login | Dashboard | Agent Monitoring |
|---------------|--------|------------|------------------|
| ![Install](./screenshots/installation_logs.png) | ![Login](./screenshots/wazuh_login.png) | ![Dashboard](./screenshots/wazuh_dashboard.png) | ![Agent](./screenshots/wazuh_agent_connected.png) |

## ⚙️ Tools & Technologies
- **Ubuntu 22.04 LTS (VirtualBox)**
- **Wazuh v4.13**
- **Windows 11 Agent**
- **Linux CLI, Networking Basics**

## 💡 Challenges Faced
- **Limited system resources:** The Wazuh components required significant CPU and RAM, which caused slow performance during indexing and dashboard loading.  
- **Complex new tool:** As a first-time Wazuh user, understanding its modular architecture (manager, indexer, dashboard) and configuration files was initially challenging.  
- **Network connectivity issues:** The Windows agent connection failed multiple times before resolving port and service configuration problems.  
- **Time management:** Balancing installation troubleshooting, documentation, and verification within tight deadlines.  
- **Learning curve:** Understanding SIEM concepts like rule-based detection, log correlation, and alert analysis took extra research and practice.  

## 🎯 Key Learnings
- Hands-on understanding of **SIEM architecture, log management, and endpoint monitoring**
- Experience with **Linux administration and security configuration**
- Improved ability to **analyze security events and visualize threats** in real time
- Developed problem-solving skills by troubleshooting service dependencies and network issues

---

**Author:** R. Farhan  
**Date:** October 2025  
**Tags:** `SIEM` `Wazuh` `Cybersecurity` `SOC` `Ubuntu` `Hands-on`
