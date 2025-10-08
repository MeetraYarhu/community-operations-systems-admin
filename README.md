## Community Administration  
**Project:** Tempo-Bot / Coeurl Community  
**Role:** Community Administrator & Systems Architect  
**Duration:** 2021 – Present  
**Scale:** 45,000+ members  

---

## Table of Contents
1. [Overview](#overview)
2. [Hierarchy & Access Control](#hierarchy--access-control)
3. [Automation & Infrastructure](#automation--infrastructure)
4. [Documentation Library](#documentation-library)
5. [Governance & Operations](#governance--operations)
6. [Results & Metrics](#results)
7. [Technical Skills Demonstrated](#technical-skills-demonstrated)
8. [Further Documentation](#further-documentation)

---

### Overview  
I serve as the lead administrator for one of the largest FFXIV communities on Discord, responsible for all technical operations, governance design, and documentation management. This includes permission hierarchy design, bot automation, moderation systems, and contributor onboarding processes.  

👉 See full details in [`docs/00_Overview.md`](docs/00_Overview.md)

---

### Hierarchy & Access Control  
Designed and implemented a structured permissions model based on least-privilege principles:  
- **Admins:** Full control of Discord server and integrations (solo administrator).  
- **Moderation Team:** Broad permissions excluding sensitive archives; delegated authority to manage channels, roles, and bots within defined boundaries.  
- **Contributors & Spawners:** Tiered access to private coordination and planning channels.  
- **Verified Users:** General membership with linked FFXIV accounts via KupoBot integration.  
- **Unverified Users:** Read-only access to public information channels.  

Key highlights:  
- Implemented fine-grained access controls using role hierarchy and channel-level overrides.  
- Authored detailed moderation and contributor handbooks outlining standard operating procedures.  
- Conducted regular audits of permissions and activity logs to maintain security compliance.  

👉 See [`docs/01_Hierarchy_and_Access_Control.md`](docs/01_Hierarchy_and_Access_Control.md)

---

### Automation & Infrastructure  
Configured, maintained, and audited all bot infrastructure and integrations:  
- **KupoBot:** Character verification and in-game linkage.  
- **CarlBot & YAGPDB:** Moderation, ticketing, and spam mitigation.  
- **Zira:** Self-role assignment and onboarding flows.  
- **Custom Bot (Node.js, Discord.js v14):**  
  - Handles automated role management for contributor tiers (Full, Trial, Retired).  
  - Provides command logging and relay systems.  
  - Deployed in both production and development environments for testing.  

Implemented automated security measures and alert filters:  
- **Mention spam filter:** Blocks messages with >5 mentions; whitelisted for contributor roles.  
- **Regex hyperlink filter:** Detects and blocks phishing/spam links.  
- **@everyone/@here restriction:** Prevents global pings by unprivileged users.  

Example metrics:  
- **2024:** 115,360 total messages processed in July alone.  
- **2025:** 84 automated alerts triggered and resolved.  

👉 See [`docs/02_Automation_and_Infrastructure.md`](docs/02_Automation_and_Infrastructure.md)

---

### Documentation Library  
Authored and maintained a comprehensive documentation suite for multiple internal audiences:  

| Audience | Guide | Description |
|-----------|-------|-------------|
| **Contributor-Facing** | [Faloop Guidelines](docs/03_Documentation_Library/Faloop_Guidelines.md) | Contributor policies, mission statement, and promotion rules |
| **Mentor-Facing** | [Mentor Guide](docs/03_Documentation_Library/Mentor_Guide.md) | Mentor responsibilities, communication norms, and trial process |
| **Public-Facing** | [Faloop Info](docs/03_Documentation_Library/Faloop_Info.md) | General information for players and users |
| **Moderator-Facing** | [Coeurl Mod Guide](docs/03_Documentation_Library/Coeurl_Mod_Guide.md) | Moderation tools, bot management, and Faloop admin process |

---

### Governance & Operations  
- Established mentor-based onboarding program for new contributors.  
- Developed verification workflows and contributor promotion processes.  
- Managed ticket response, dispute resolution, and tech assistance for members.  
- Coordinated moderation, logging, and auditing for multiple active teams.  

👉 See [`docs/04_Governance_and_Operations.md`](docs/04_Governance_and_Operations.md)

---

### Results  
- Successfully scaled a live community to over **45,000 members** with minimal downtime.  
- Maintained a stable, automated environment with **>99.9% uptime** across all bots.  
- Streamlined onboarding and documentation, cutting contributor ramp-up time by ~60%.  
- Reduced spam and moderation incidents through proactive bot-based filtering.  

👉 See [`docs/05_Results_and_Metrics.md`](docs/05_Results_and_Metrics.md)

---

## Technical Skills Demonstrated
- Access control design (RBAC / least privilege)  
- Automation & monitoring systems (Discord.js, regex filters, ticketing systems)  
- Log analysis & alert tuning  
- Documentation architecture and knowledge management  
- Community governance and moderation frameworks  
- Incident response workflows and user verification systems  

👉 See [`docs/06_Technical_Skills_Demonstrated.md`](docs/06_Technical_Skills_Demonstrated.md)

---

## Further Documentation
For detailed examples, diagrams, and supporting documentation, refer to the [`/docs`](docs/) directory and the [`/assets`](assets/) folder for sanitized images and workflow diagrams.

---

**Disclaimer:**  
This repository is a sanitized case study of my community management and systems administration work. All sensitive data, identifiers, and internal assets have been removed or anonymized.