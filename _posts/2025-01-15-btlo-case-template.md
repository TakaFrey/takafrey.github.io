---
title: "BTLO Investigation — <Case Name>"
author: Rémy Dupeyroux
date: 2025-01-15 12:00:00 +0200
categories: [BTLO]
tags: [btlo, soc, incident-response, windows-artifacts, logs, blue-team]
---

# 🧩 Case Overview

**Platform**: Blue Team Labs Online  
**Case**: <Name>  
**Difficulty**: <Easy / Medium / Hard>  
**Category**: <SOC / IR / Forensics / Threat Hunting / Log Analysis>

---

# 🎯 Scenario Summary

Explique le contexte :

- Incident alerté par *EDR/SIEM*  
- Type de compromission  
- Objectif des questions  
- Artefacts fournis (logs, memory, pcap, eventlogs…)

---

# 🔍 Evidence Collection

Liste ce que BTLO te donne :

- Security logs  
- PowerShell history  
- Autoruns  
- PCAP  
- Sysmon  
- MFT/Registry  

---

# 🧠 Step-by-Step Investigation

### 🧩 Event Analysis

```bash
wevtutil qe Security /q:"Event[System/EventID=4624]"
