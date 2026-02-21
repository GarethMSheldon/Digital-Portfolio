
## 🎯 CORE SECURITY CONCEPTS

### 🔐 The CIA Triad (Protection Goals)

| **KEYWORD**         | **NOTES**                                                                                                                                                    |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Confidentiality** | ✓ Data known only to authorized persons  <br>✓ Ask: What if this appeared on a billboard?  <br>✓ Consider: Legal trouble, lost contracts, privacy violations |
| **Integrity**       | ✓ Data are correct, complete, up to date  <br>✓ Ask: What if this data is inaccurate?  <br>✓ Impact: Medical errors, bad decisions, unfair loan rates        |
| **Availability**    | ✓ Data accessible when and where needed  <br>✓ Ask: Can business operate without this system?  <br>✓ Consider: Legal penalties, harm to individuals          |

> **Key Insight:** These three goals interconnect and balance each other. Protecting one often supports or conflicts with another.

---

### 💎 Key Assets & Concepts

| **TERM**            | **DEFINITION & IMPORTANCE**                                                                                                                                                                    |
| ------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Assets**          | • Tangible: computers, equipment, physical items  <br>• Intangible: data, reputation, employee skills  <br>• **People = most valuable asset**  <br>• Data value depends on secrecy and utility |
| **Vulnerabilities** | • Weaknesses in technology, physical space, people, procedures  <br>• Software/hardware: fixed with patches  <br>• Human factors: fixed with training                                          |
| **Risk Formula**    | **Risk = Probability × Impact**  <br>Exists when you have: Asset + Vulnerability + Threat                                                                                                      |
| **Risk Treatment**  | ① Accept (within tolerance)  <br>② Correct (fix it)  <br>③ Transfer (insurance)  <br>④ Mitigate (reduce indirectly)  <br>⑤ Ignore (❌ not recommended)                                          |

---

### ⚔️ PHYSICAL ATTACKS

|**ATTACK TYPE**|**HOW IT WORKS**|**PREVENTION**|
|---|---|---|
|**Technology Theft**|Stealing devices containing data|• Clean-desk principle  <br>• Lock devices when not in use  <br>• Secure rooms/containers|
|**Shoulder Surfing**|Watching over shoulder for:  <br>• PINs at ATMs  <br>• Phone unlock codes  <br>• Confidential documents|• Screen privacy filters  <br>• Awareness in public spaces  <br>• Position screens away from traffic|
|**Document Theft**|Taking unattended printouts|• Retrieve prints immediately  <br>• Use secure print release  <br>• Shred sensitive documents|

---

## 💻 LOGICAL ATTACKS

### 🎣 Phishing

**What:** Social engineering via email, text, social media  
**Tactics:** Emotional triggers (fear, guilt, sympathy) + urgency  
**Why it works:** Low cost, high volume, only needs few successes

**Examples:**

- "Your account will be closed unless you verify now"
- "I'm stranded abroad and need money to get home"
- "Click here to claim your prize"

---

### 🦠 Malware Types

|**TYPE**|**BEHAVIOR**|**KEY FEATURE**|
|---|---|---|
|**Virus**|Attaches to legitimate files|Needs user action to spread|
|**Worm**|Self-contained program|Spreads independently  <br>_(e.g., SQL Slammer 2003)_|
|**Ransomware**|Encrypts your data|Demands payment for decryption key|
|**Trojan**|Disguised as useful app|Hides malicious functions inside|
|**Spyware**|Records user activity|Captures keystrokes, browsing, data|

---

### 💥 DoS/DDoS Attacks

**DoS (Denial of Service)**

- Single attacker overwhelms service with requests
- Makes legitimate access impossible

**DDoS (Distributed Denial of Service)**

- Multiple attackers simultaneously
- Often uses botnets (compromised devices)
- Can exceed 300 Gbps traffic

**Defense:** Firewalls, load balancing, disable unnecessary services

---

## 👥 THREAT ACTORS

|**ACTOR**|**MOTIVATION**|**CHARACTERISTICS**|
|---|---|---|
|**🎲 Opportunists**|Quick financial gain|Agile, spontaneous, unplanned attacks|
|**💰 Professional Hackers**|Career criminals|Strategic, coordinated, profit-driven|
|**🏴 Organized Crime**|Bulk data sales|Dark web transactions, support other crimes|
|**🏢 Business Competitors**|Competitive advantage|Steal intellectual property, strategic plans|
|**🎖️ Nation-State**|Government interests|Highly skilled, target governments/infrastructure|
|**👻 APT (Advanced Persistent Threat)**|Long-term espionage|Stealthy, use zero-day exploits, remain undetected|

> **APT Hallmarks:** Stealth + New vulnerabilities + Technical skill + Long-term presence

---

## 🛡️ SECURITY STRATEGIES

### Strategy 1: Defense in Depth

```
🔥 Firewall
  └─ 🦠 Antivirus
      └─ 🔄 Patching
          └─ 🔐 Access Control
              └─ 🔒 Encryption
                  └─ 📱 Physical Security
```

**Principle:** Multiple layers, assume any single layer will fail

---

### Strategy 2: Encryption Everywhere

- **In Transit:** Network traffic (internet + intranet)
- **At Rest:** Databases, servers, workstations
- **Modern Reality:** Processors handle encryption easily
- **Key Question:** Who should have decryption keys?

---

### Strategy 3: Assume Breach

**Mindset:** Presume intrusion has already happened

**Ask:** "Are we protected from internal attacks?"

**Benefits:**

- Better incident response planning
- Doesn't rely on perimeter defenses alone
- Realistic about modern threats

---

## ⚖️ COMPLIANCE & LEGAL

### 📋 Responsibility

|**WHO?**|**ROLE**|
|---|---|
|**Data Owners**|• Ultimately responsible  <br>• Determine value, risk appetite, funding  <br>• Make final decisions|
|**IT Security Teams**|• Create protection programs  <br>• Implement controls  <br>• Report risks clearly|

> **Critical:** Security departments can't be effective without strong business owner support

---

### 📜 Standards vs Laws

|**STANDARDS**|**LEGAL REGULATIONS**|
|---|---|
|Optional (often contractual)|Legally required|
|Industry-specific benchmarks|Geographic/national laws|
|Strongest for health/finance|Privacy: protect citizens (GDPR)  <br>Security: critical infrastructure|
|National/international frameworks|Apply to data location  <br>(origin, processing, storage)|

---

## 📝 SUMMARY BOX

Information security protects organizational assets through the **CIA triad** (Confidentiality, Integrity, Availability). Organizations face **physical attacks** (theft, shoulder surfing) and **logical attacks** (phishing, malware, DoS). **Threat actors** range from opportunists to nation-states, primarily motivated by financial gain. Effective security requires **layered strategies** (defense in depth, encryption everywhere, assume breach), **clear responsibility** (data owners, not just IT), and **compliance** with geographic legal requirements.

---

## ❓ REVIEW QUESTIONS

1. What are the three components of the CIA triad and how do they interact?
2. What makes an Advanced Persistent Threat different from other attackers?
3. How does "Assume Breach" improve security posture?
4. What's the difference between DoS and DDoS attacks?
5. Why are data owners ultimately responsible for security instead of IT departments?

---

**📌 Study Tip:** Focus on the CIA triad first, then understand how attacks threaten each component, and finally learn how strategies defend against those attacks.
