# 🧱 TryHackMe: Cyber Kill Chain (ZMT)

This is my personal write-up for the [Cyber Kill Chain (ZMT)](https://tryhackme.com/room/cyberkillchainzmt) room on TryHackMe. The room is part of the **SOC Level 1 path** and guides you through each phase of Lockheed Martin’s Cyber Kill Chain model via quiz questions and a practical exercise.

---

## 📘 Overview

The **Cyber Kill Chain** is a seven-stage model describing the lifecycle of a cyberattack. It helps defenders understand attack sequences and break the chain at vulnerable points.

---

## 🔗 The 7 Phases & My Answers

### 1. Reconnaissance
- **OSINT Framework** — a web‑based collection of open‑source intelligence tools.
- **Email harvesting** — the process of collecting email addresses during OSINT.

### 2. Weaponization
- **Macro** — a set of commands/scripts commonly embedded (often maliciously) in Office documents.

### 3. Delivery
- **Watering hole attack** — infecting a site frequently used by a specific target group.

### 4. Exploitation
- **Zero‑day** — an exploit targeting a previously unknown vulnerability.

### 5. Installation
- **Timestomping** — modifying file timestamps to hide malicious changes.
- **Web shell** — a malicious script installed on a compromised webserver to maintain remote access.

### 6. Command & Control (C2)
- **DNS Tunneling** — using DNS queries to communicate covertly with a C2 server.

### 7. Actions on Objectives (Exfiltration)
- **Shadow Copy** — a Windows feature used to create snapshots of files/volumes, which attackers can exploit for exfiltration.

---

## 🧪 Practical Task

In the **Practice Analysis** section, I mapped a real-world attack onto the Cyber Kill Chain phases.

---

## 📝 Key Takeaways

- The Kill Chain offers a structured framework to analyze attacks end-to-end.
- Breaking the chain at any early stage (like reconnaissance or delivery) can prevent full compromise.
- Even older models like Lockheed Martin’s remain relevant today, especially when combined with frameworks like MITRE ATT&CK.

---

## ✅ Completion Notes

- This room is quiz-based with a final static site exercise.
- No hands-on exploitation or labs were performed.

---

## 📜 Disclaimer

My write‑up is based on my own answers and learning. All intellectual property belongs to TryHackMe. This document is for educational purposes only.

---

Thanks for reading — happy defending! 🛡️
