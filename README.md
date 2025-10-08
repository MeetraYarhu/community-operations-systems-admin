## 🧭 Community Administration  
**Project:** Tempo-Sapphire / Coeurl Community  
**Role:** Community Administrator & Systems Architect  
**Duration:** 2021 – Present  
**Scale:** 45,000+ members  

### Overview  
I serve as the lead administrator for one of the largest FFXIV communities on Discord, responsible for all technical operations, governance design, and documentation management. This includes permission hierarchy design, bot automation, moderation systems, and contributor onboarding processes.  

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

### Documentation Library  
Authored and maintained a comprehensive documentation suite for multiple internal audiences:  

#### Contributor-Facing  
**Faloop Guidelines for the Primal Datacenter**  
- Mission Statement  
- Guidelines & Expectations  
  - Hunt Disruption  
  - Spawning  
  - Relaying  
  - Releasing Others’ Spawns  
  - Negative Behavior  
  - Promoting The Coeurl  
- Becoming a Reporter  
  - B-Science  
  - Instant Posting (Trials)  
  - Early Access  
- Requesting Promotions  
  - B-Science Promotions  
  - Instant Posting Promotions  
  - EA Promotions  
  - Causes for Demotion  

#### Mentor-Facing  
**Mentor Guide**  
- Purpose & Responsibilities  
- General Guidelines for Working with Trials  
- Relevant Channels  
- Trial Process for Mentors  

#### Public-Facing  
**Faloop Info**  
- What is Faloop?  
- What sets Faloop apart from other trackers?  
- How does Faloop work?  
- I registered an account but I still can’t report anything?  
- I want to help out! How do I become a Reporter?  

#### Moderator-Facing  
**Coeurl Mod Guide**  
- **Faloop Admin Guide**  
  - Users, Permissions, and Audit Logs  
- **Faloop Process Guide**  
  - Roles & Channels  
  - Trial Process  
  - B-Science  
  - A-Ranks  
  - EA/Promotions  
  - Travelers / Off-DC  
  - Permission Removal  
- **Bot Management**  
  - KupoBot, CarlBot, YAGPDB, Zira  
- **General Moderation**  
  - Tickets, Warns, Kicks, Mutes  

### Governance & Operations  
- Established mentor-based onboarding program for new contributors.  
- Developed verification workflows and contributor promotion processes.  
- Managed ticket response, dispute resolution, and tech assistance for members.  
- Coordinated moderation, logging, and auditing for multiple active teams.  

### Results  
- Successfully scaled a live community to over **45,000 members** with minimal downtime.  
- Maintained a stable, automated environment with **>99.9% uptime** across all bots.  
- Streamlined onboarding and documentation, cutting contributor ramp-up time by ~60%.  
- Reduced spam and moderation incidents through proactive bot-based filtering.  
