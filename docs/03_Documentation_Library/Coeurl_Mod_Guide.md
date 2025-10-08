# 🛡️ Coeurl Mod Guide
**Project:** Coeurl Discord - Moderator Operations  
**Role:** Community Administrator / Documentation Author  
**Duration:** 2021 – Present  
**Purpose:** Reference for moderation tools, permissions, escalation procedures, and conduct standards.  
**Last Updated:** October 2025


---

## 🧭 Overview  

The Coeurl Mod Guide serves as the primary internal reference for moderation operations within the 45,000+ member FFXIV community server.  
It standardizes workflows, permissions, and procedures across all moderators and ensures that community policies are applied consistently and transparently.  

The guide functions as both:
- A **training reference** for new moderators joining the team, and  
- A **policy enforcement framework** for established staff managing tickets, warnings, and incident reports.  

All documentation is structured to follow the principle of least privilege, modularizing access by function (moderation, contributors, bots, etc.).  

---

## 🧩 Structure  

The guide is divided into four major operational sections:

### ◽ Faloop Admin Guide  
- Navigating Faloop Admin  
- User and permissions management  
- Audit log tracking and activity verification  

### ◽ Faloop Process Guide  
- Roles and Channels  
- Trial Process and Promotions  
- A-Rank and B-Rank operations  
- Traveler and Off-DC coordination  
- Permission removal workflows  

### ◽ Bots  
- Kupo Bot (Verification and linking)  
- Carl Bot (Moderation automations)  
- YAGPDB (Ticketing and reaction systems)  
- Zira (Role self-assignment system)  

### ◽ General Moderation  
- Ticket handling procedures  
- Warning, kicking, and timeout criteria  
- Message logging and escalation process  
- Conflict resolution and documentation  

---

## 🧰 Tools & Systems  

| Tool | Function |
|------|-----------|
| **Carl Bot** | Moderation automation, role management, and logging |
| **YAGPDB** | Ticket handling and rule enforcement |
| **Zira** | Role assignment and onboarding |
| **Kupo Bot** | Account verification and character linking |
| **Discord Audit Logs** | Tracking moderator actions and maintaining transparency |
| **Google Docs** | Drafting and maintaining mod documentation revisions |

---

### 🧾 Documentation Governance Overview  

All moderator guidelines are maintained under version control principles.  
Updates are discussed in moderation channels before implementation and synchronized across shared moderator resources.  
Changes are logged with edit notes and timestamps to ensure accountability, and redundant or outdated rules are pruned regularly.  

Documentation revisions are made in response to operational changes, audit findings, or moderator feedback to ensure clarity and maintain community trust.  

---

## 🗂️ Operational Change Example (Redacted)

**Context**  
Moderators requested a faster way to remove spambot posts and temporarily ban accounts that slip past filters.

**Change Implemented**  
Added a Carl-bot slash command for quick temp bans with message cleanup.

**Command**  
`/moderation tempban <userID> [duration]`

**What it does**
- Accepts a **userID** and auto-populates username and server name
- Applies a **temporary ban** (default: 4 days if duration is not set)
- **Deletes the user’s messages** from the last 24 hours

**When to use**
- Spambot joins and posts across multiple channels
- Rapid cleanup needed to restore channel integrity
- Suspicious or recently flagged accounts rejoin the server

**Rollout & Comms**
- Announced in the moderators’ commands channel (redacted)
- Provided step-by-step usage notes and expected outcomes
- Invited feedback for tuning default duration and purge window

**Result**
- Faster containment and cleanup of spam waves
- Reduced manual moderator effort during bursts
- Consistent application of timeouts and evidence hygiene

---

## 🗂️ Operational Change Example – Faloop Role Command (Redacted)

**Context**  
Moderators requested a faster way to promote contributors and update roles without manually searching the member list or adjusting them through the Faloop admin interface.

**Change Implemented**  
Introduced a custom `/faloop` command to automate internal role adjustments within the Discord server.  
The command simplifies permission management for Conductors, Spawners, and Reporters by allowing role changes via dropdown selections.

**Command**  
`/faloop <option> <user>`

**What it does**  
- Displays selectable role options when typing `/faloop`  
- Updates user roles **only** within the Coeurl Discord environment (not the Faloop website)  
- Auto-loads the full server member list to eliminate manual search lag  
- Logs usage through Tempo-Bot for audit tracking  

**When to use**  
- Promoting contributors (e.g., granting B-Science or EA permissions)  
- Adjusting internal Discord roles for alignment with Faloop access  
- Testing role configurations or onboarding new moderators  

**Rollout & Comms**  
- Announced in `#faloop-roles` with detailed usage explanation  
- Noted that this only affects internal server roles, not the external Faloop database  
- Feedback encouraged to report issues or enhancements  

**Result**  
- Streamlined role management and promotion process  
- Reduced errors from manual role editing  
- Faster onboarding for new moderators and contributors  

---

**Change Log**
| Date       | Summary                                   | Editor  |
|------------|--------------------------------------------|---------|
| 2023-10-16 | Added Carl tempban command with 24h purge | Meetra |
| 2023-08-30 | Added `/faloop` role management command        | Meetra  |
| 2022-11-08 | Initial Creation | Meetra  |

---

## 🧩 Outcome  

- Established a transparent, documented moderation framework for a high-volume community.  
- Reduced staff onboarding time through detailed process guides and examples.  
- Standardized escalation, reporting, and role management procedures to minimize ambiguity.  
- Increased operational consistency and accountability among moderators.  