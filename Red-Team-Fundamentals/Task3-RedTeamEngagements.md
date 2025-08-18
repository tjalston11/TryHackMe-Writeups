## Task 3 - Red Team Engagements  

To keep up with the emerging threats, red team engagements were designed to shift the focus from regular penetration tests into a process that allows us to clearly see our defensive team's capabilities at detecting and responding to a real threat actor. They don't replace traditional penetration tests, but complement them by focusing on detection and response rather than prevention.  

Red teaming is a term borrowed from the military. In military exercises, a group would take the role of a red team to simulate attack techniques to test the reaction capabilities of a defending team, generally known as blue team, against known adversary strategies. Translated into the world of cybersecurity, red team engagements consist of emulating a real threat actor's Tactics, Techniques and Procedures (TTPs) so that we can measure how well our blue team responds to them and ultimately improve any security controls in place.  

Every red team engagement will start by defining clear goals, often referenced as **crown jewels** or **flags**, ranging from compromising a given critical host to stealing some sensitive information from the target. Usually, the blue team won't be informed of such exercises to avoid introducing any biases in their analysis. The red team will do everything they can to achieve the goals while remaining undetected and evading any existing security mechanisms like firewalls, antivirus, EDR, IPS and others. Notice how on a red team engagement, not all of the hosts on a network will be checked for vulnerabilities. A real attacker would only need to find a single path to its goal and is not interested in performing noisy scans that the blue team could detect.  

It is important to note that the final objective of such exercises should never be for the red team to "beat" the blue team, but rather simulate enough TTPs for the blue team to learn to react to a real ongoing threat adequately.  

---

### Key Points
- **Technical Infrastructure**: Similar to a penetration test but with more focus on stealth and evasion.  
- **Social Engineering**: Phishing, phone calls, or social media to gather sensitive information.  
- **Physical Intrusion**: Techniques like lockpicking, RFID cloning, or bypassing access controls.  

### Engagement Types
- **Full Engagement**: Simulate the entire workflow of an attacker.  
- **Assumed Breach**: Assume initial access and proceed from there.  
- **Table-top Exercise**: Theoretical discussions of threat response.  

---

### Questions & Answers
**Q1:** The goals of a red team engagement will often be referred to as flags or...?  
**A1:** Crown jewels ✅  

**Q2:** During a red team engagement, common methods used by attackers are emulated against the target. Such methods are usually called TTPs. What does TTP stand for?  
**A2:** Tactics, Techniques, and Procedures ✅  

**Q3:** The main objective of a red team engagement is to detect as many vulnerabilities in as many hosts as possible (Yay/Nay).  
**A3:** Nay ✅  
