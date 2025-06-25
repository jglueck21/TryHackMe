# 🧱 TryHackMe: Cyber Kill Chain

This is my personal write-up for the [Cyber Kill Chain](https://tryhackme.com/room/cyberkillchain) room on TryHackMe. The room introduces the Cyber Kill Chain model, a framework developed by Lockheed Martin to describe the stages of a cyberattack. This documentation outlines the main concepts, key takeaways, and my answers (without spoilers) for educational purposes.

---

## 📘 Overview

The **Cyber Kill Chain** is a seven-stage model that describes the typical phases of a cyberattack. Understanding this model helps both offensive and defensive security professionals recognize how attacks unfold and how to break the chain at each step.

---

## 🔗 The 7 Stages of the Kill Chain

### 1. Reconnaissance  
- The attacker gathers information about the target.  
- This can include passive methods (WHOIS lookups, DNS queries) and active techniques (port scanning, phishing research).  
- Goal: Identify weak points to exploit.

### 2. Weaponization  
- Crafting a malicious payload (e.g., malware, macro-laced documents) tailored to exploit a specific vulnerability.  
- No interaction with the target happens at this stage.

### 3. Delivery  
- The attacker delivers the weapon to the target, typically via phishing emails, malicious websites, USB drives, etc.  
- It's one of the most visible points for defenders to intervene.

### 4. Exploitation  
- Once delivered, the payload is executed by the target (often unknowingly).  
- Common vectors: buffer overflows, script injection, malicious macros.

### 5. Installation  
- The attacker establishes a foothold, often through malware like Remote Access Trojans (RATs).  
- Persistence techniques may be used (startup scripts, services, etc.).

### 6. Command and Control (C2)  
- The attacker creates a communication channel with the compromised system.  
- This allows remote control, data exfiltration, or further internal reconnaissance.

### 7. Actions on Objectives  
- The attacker acts on their goal, which could include data theft, sabotage, or lateral movement within the network.

---

## 🧠 Key Takeaways

- The Kill Chain model provides a **structured approach** to understanding and defending against cyberattacks.
- Defenders can **break the chain at any stage** to stop an attack from succeeding.
- Real-world security tools and practices (e.g., SIEMs, IDS/IPS, endpoint protection) are often mapped against these stages.

---

## 📝 What I Learned

- The importance of **early detection**, especially during reconnaissance and delivery phases.
- How **each stage builds upon the previous**, emphasizing the need for layered defenses.
- That even **basic knowledge of the kill chain** enhances both offensive strategy and defensive analysis.

---

## ✅ Room Completion

All questions were completed successfully. The room is non-interactive (quiz-based), and does not involve any real exploitation or hands-on attack simulation.

---

## 📜 Disclaimer

This write-up is for educational purposes only and reflects my own understanding and interpretation of the Cyber Kill Chain room. All intellectual property belongs to [TryHackMe](https://tryhackme.com/).

---

Thanks for reading! ✨  
Happy hacking and stay safe!
