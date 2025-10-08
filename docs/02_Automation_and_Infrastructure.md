# ⚙️ Automation and Infrastructure
**Project:** Coeurl Discord - Automation and Bot Infrastructure  
**Role:** Community Administrator / Lead Developer  
**Duration:** 2021 – Present  
**Purpose:** Bot architecture, integrations, deployment, monitoring, and security controls used in Coeurl.  
**Last Updated:** October 2025
 
---

## 📘 Overview
This document describes the automation and infrastructure that support **Tempo-Bot** and its integrated systems for the Coeurl Discord community.  
It covers the configuration of multi-bot environments, layered permissions, and security automation that maintain uptime, reduce spam, and streamline contributor management across a 45,000-member ecosystem.

---

## 🧩 Bot Infrastructure Overview

| Bot | Primary Function | Key Integrations | Access Level |
|-----|------------------|------------------|---------------|
| **Tempo-Bot (Custom / Node.js / Discord.js v14)** | Handles automated role management, message relays, command logging, and contributor permissions. | Discord API, GitHub repo for version control, private dev instance for staging. | Moderate (restricted to automation and logging channels). |
| **KupoBot** | Verifies users by linking Discord accounts to in-game FFXIV characters. | FFXIV API, Discord OAuth2. | High trust, verification-specific access only. |
| **CarlBot** | Provides moderation utilities, reaction roles, and message logging. | Audit logs, Discord message events. | Moderate. |
| **YAGPDB** | Powers the ticketing system and event automation triggers. | Discord commands, message parsing. | Limited (tickets and logs only). |
| **Zira** | Manages certain role menus and self-assignable roles. | Reaction triggers, role assignment. | Restricted to onboarding channels. |

Each bot is isolated to a **dedicated functional domain** (Moderation, Logging, Automation, or Engagement) to minimize cross-permission overlap and improve reliability.

---

## 🧠 Automated Security & Filtering

### Spam and Abuse Prevention
- **Mention Flood Filter:** Blocks messages with more than five mentions, sends alerts, and issues automatic timeouts.  
- **Hyperlink Regex Filter:**  ^\[[^\]]+\]\((?:\s*<?https?.+>?\s*)\) Blocks potentially malicious or spammy link embeds.
- **@everyone/@here Protection:** Blocks unauthorized global mentions while allowing specific elevated roles.  

### Alert System
- Alerts are forwarded to a secure moderator-only channel for triage.  
- Logged events include timestamps, user IDs, and triggering content.  
- As of 2025, **84 automated security alerts** were successfully handled.

---

## 🪶 Ticketing & Workflow Automation
- **System:** YAGPDB ticket module integrated with custom permissions and logging.  
- **Workflow:**  
1. User opens a ticket via command.  
2. System auto-assigns the correct moderation category.  
3. Ticket is logged and closed with standardized macros.  
- **Use Cases:** Technical support, contributor onboarding, community appeals, and event coordination.  
- **Audit:** Ticket logs retained indefinitely private channels for transparency.

---

## 📈 Monitoring & Metrics
- **Uptime Tracking:** Automated bot status checks using periodic self-pings and admin alerts.  
- **Message Throughput:**  
- July 2024: ~115,360 total messages.  
- Monthly average: 85k–100k messages.  

---

## 📚 Related Documentation
- [Hierarchy & Access Control](01_Hierarchy_and_Access_Control.md)  
- [Governance & Operations](04_Governance_and_Operations.md)  
- [Technical Skills Demonstrated](06_Technical_Skills_Demonstrated.md)  

---

## 🧠 Skills Demonstrated
- Dockerized bot deployment and version control (Node.js / Discord.js)  
- Automated role-based access management  
- Regular expression (regex) use for input validation and spam mitigation  
- Cross-platform bot integration and permission segregation  
- Logging, metrics, and monitoring via Grafana and Netdata  
- Documentation and structured workflow design  

---

## 📊 Summary
The automation framework transforms a large-scale community into a self-sustaining ecosystem.  
By containerizing bots, integrating multiple security layers, and automating moderation workflows, the infrastructure maintains **99.9% uptime** while minimizing manual intervention and reducing human error across operations.
