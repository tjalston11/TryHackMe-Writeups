# Task 5: Engagement Structure

**Room:** Red Team Fundamentals  
**Objective:**  
Understand the structure of a red team engagement and how the Lockheed Martin Cyber Kill Chain is used to map attacker TTPs.

---

### 🔹 Task Summary
A core function of the red team is **adversary emulation**, which simulates what a real attacker would do using their tools and methodologies. Red teams use **cyber kill chains** to summarize and assess the steps of an engagement.  

Blue teams also use kill chains to map behaviors and detect adversary movement, while red teams adapt these frameworks to map attacker TTPs.  

Commonly referenced kill chains include:  
- Lockheed Martin Cyber Kill Chain  
- Unified Kill Chain  
- Varonis Cyber Kill Chain  
- Active Directory Attack Cycle  
- MITRE ATT&CK Framework  

The **Lockheed Martin Cyber Kill Chain** focuses on external breaches and is widely used for red and blue team exercises.

---

### 🔹 Components of the Lockheed Martin Cyber Kill Chain

| Technique             | Purpose                                           | Examples                                  |
|----------------------|--------------------------------------------------|------------------------------------------|
| Reconnaissance        | Obtain information on the target                | Harvesting emails, OSINT                  |
| Weaponization         | Combine the objective with an exploit           | Exploit with backdoor, malicious doc      |
| Delivery              | How the weaponized function is delivered       | Email, web, USB                           |
| Exploitation          | Exploit the target's system to execute code    | MS17-010, Zero-Logon                      |
| Installation          | Install malware or other tooling                | Mimikatz, Rubeus                          |
| Command & Control     | Control compromised assets from a central host | Empire, Cobalt Strike                      |
| Actions on Objectives | Achieve end objectives                          | Conti, LockBit2.0                          |

---

### ✅ Questions & Answers
**Q1:** If an adversary deployed Mimikatz on a target machine, where would they be placed in the Lockheed Martin cyber kill chain?  
**A1:** Installation ✅

**Q2:** What technique's purpose is to exploit the target's system to execute code?  
**A2:** Exploitation ✅

---

### ✅ Key Takeaways
- Red teams emulate attackers to test detection and response.  
- The **Lockheed Martin Cyber Kill Chain** provides a structured approach for mapping TTPs.  
- Understanding each step helps both red and blue teams improve security posture and response capabilities.  
