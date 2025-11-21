---
title: "HackTheBox - <Machine Name>"
author: Rémy Dupeyroux
date: 2025-01-10 12:00:00 +0200
categories: [HackTheBox]
tags: [htb, pentest, enumeration, exploitation, privilege-escalation]
---

# 🧩 Machine Overview

**Platform**: HackTheBox  
**Machine**: <Name>  
**Difficulty**: <Easy / Medium / Hard>  
**OS**: <Linux / Windows>  
**Points**: <10 / 20 / 30>  
**Release**: <Date>  
**IP**: <Machine IP>

---

# 🔍 Enumeration

## ➤ Network Scan

```bash
nmap -sC -sV -A -oN scan.txt <IP>
