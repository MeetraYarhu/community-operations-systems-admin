# 🧩 Hierarchy & Access Control  
**Project:** Tempo-Bot / Coeurl Hunt Community  
**Section:** Community Administration Documentation  
**Last Updated:** October 2025  

---

## 📘 Overview
This document outlines the hierarchical structure and access control framework for the Tempo-Bot / Coeurl Hunt Discord community.  
It is designed according to **least privilege principles** to ensure operational efficiency, role clarity, and security of sensitive channels and systems.

---

## 🧭 Role Hierarchy Overview

| Role Tier | Description | Key Permissions | Access Scope |
|------------|--------------|-----------------|----------------|
| **Administrator** | Full management of all systems, integrations, and documentation. | Manage server, channels, roles, integrations, audit logs. | All channels and archives. |
| **Moderation Team** | Oversees community conduct, enforces rules, and manages contributor channels. | Manage messages, roles, and channels within moderation and contributor areas. | All general + contributor channels. |
| **Contributors / Spawners** | Coordinates in-game events, follows Faloop and Coeurl guidelines. | Access to contributor planning channels and relevant resources. | Private contributor sections. |
| **Verified Members** | General participants with verified in-game identities. | Post and interact in most public and semi-public channels. | Verified chat, discussion, and alert channels. |
| **Unverified Members** | Read-only users who can view announcements and reference information. | None beyond view access. | Public sections only. |

---

## 🔐 Access Control Model

- **Principle:** Every permission is assigned based on functional necessity, not status.  
- **Methodology:** Roles are layered in descending order of privilege, each limited by Discord’s inherent role hierarchy.  
- **Implementation:**  
  - Administrators can modify all permissions.  
  - Moderators can only edit channels and roles **within their scope** (e.g., contributor-related areas).  
  - Contributors are sandboxed to prevent cross-team data leakage or accidental configuration changes.  

---

## 🧱 Technical Configuration Highlights

- Channel categories are segmented by function (e.g., `Admin`, `Moderation`, `Contributor Planning`, `Public Information`).  
- Permissions are configured per-category to minimize redundancy.  
- **Bot-specific permissions** are isolated to reduce risk of misfires:
  - **Moderation Bots:** Limited to relevant logs and ticket channels.  
  - **Chat Bots:** Restricted to non-sensitive interaction areas.  
- Regular audits are performed using bot-generated role and permission reports.  

---

## 📑 Moderation Access Policy

Moderators are empowered to:
- Manage messages, issue warnings, and handle temporary restrictions.  
- Create and organize new contributor channels as needed.  
- View logs from moderation, joins/leaves, command usage, and verification systems.  

Moderators **cannot**:
- Access administrator-only archives.  
- Permanently ban users or modify administrator permissions.  
- Modify informational channels (e.g. #rules, #welcome)

---

## 📚 Related Documentation
- [Automation & Infrastructure](02_Automation_and_Infrastructure.md)  
- [Governance & Operations](04_Governance_and_Operations.md)  
- [Moderator Guide (Coeurl)](03_Documentation_Library/Coeurl_Mod_Guide.md)  

---

## 🧠 Skills Demonstrated
- Role-Based Access Control (RBAC) design  
- Application of least privilege principles  
- Multi-role permission configuration  
- Documentation and process standardization  
- Audit and incident traceability  

---

## 📊 Summary
This structure enables a scalable, secure framework that allows the community to operate with efficiency and trust.  
By combining granular role design, automation, and written procedures, administrative overhead is minimized while maintaining operational transparency and accountability.
