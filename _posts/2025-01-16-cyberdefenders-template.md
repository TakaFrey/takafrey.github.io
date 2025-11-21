---
title: "CyberDefenders — <Challenge Name>"
author: Rémy Dupeyroux
date: 2025-01-16 12:00:00 +0200
categories: [CyberDefenders]
tags: [cyberdefenders, dfir, pcap, memory, malware-analysis, forensics]
---

# 🧩 Challenge Overview

**Platform**: CyberDefenders  
**Challenge**: <Name>  
**Difficulty**: <Easy / Medium / Hard>  
**Dataset Type**: <Memory / PCAP / Disk / Windows Artifacts / Logs>

---

# 📝 Scenario Summary

Décris le pitch : attaque simulée, SOC alert, ransomware, intrusion…  
CyberDefenders donne toujours un contexte → résume-le proprement.

---

# 📦 Dataset

Explique les fichiers fournis :

- Memory dump  
- PCAP  
- Registry hives  
- Disk image  
- eventlogs  
- Browser history  

---

# 🔍 Tools Used

Liste rapide :

- Volatility / Rekall  
- Autopsy  
- KAPE  
- CyberChef  
- Wireshark  
- Sigma  
- Chainsaw  

---

# 🧠 Step-by-Step Analysis

## 1. Initial Recon

Exemples :

```bash
volatility3 -f mem.raw Windows.Info
