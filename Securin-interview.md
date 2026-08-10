# SECURIN PENETRATION TESTER — COMPREHENSIVE INTERVIEW GUIDE
## Franklin Stevens | CISSP | Pentest+ | SecAI+ | CPTS | eJPT

---

## EXECUTIVE OVERVIEW

**Your Application Strengths:**
- 20+ years cybersecurity leadership (USAF, classified programs)
- 5 relevant certifications (CISSP, Pentest+, SecAI+, CPTS pathway, eJPT)
- Demonstrated penetration testing execution (CMU coursework, HackerOne, DFIR background)
- Published researcher (cyber insider threats, AI/ML security)
- Teaching & curriculum design (shows communication depth)
- Military discipline & attacker mindset

**Securin's Focus:**
<cite index="11-1">Securin is an AI-driven cybersecurity company focused on proactive, adversarial exposure and vulnerability management, combining artificial intelligence, machine learning, threat intelligence, and deep vulnerability research to deliver an adversarial approach to cyber defence.</cite>

**Your Edge:** You combine hands-on penetration testing with AI security knowledge (SecAI+) and a proven teaching background. That's rare.

---

## YOUR COMPLETE CREDENTIAL STACK

### Certifications (For Interview, Lead With These)
- **CISSP** — Active (20+ years experience validates this)
- **Pentest+** — Active (directly relevant to role)
- **SecAI+** — Certified May 2026 (aligns with Securin's AI focus)
- **CPTS** — In Progress, ~50% pathway (shows commitment, active learning)
- **eJPT** — Completed (entry-level penetration testing credential—show discipline)

**For Interviews:**
- Lead with CISSP + Pentest+ (primary credentials)
- Mention SecAI+ when discussing AI security angle (differentiator)
- Reference CPTS pathway when talking about current skill development
- Only mention eJPT if asked about foundational credentials

### Technical Demonstrated Skills (From Your Work)

**Penetration Testing Execution:**
- Vulnerability scanning (Nessus proficiency, scanning, severity classification)
- CVSS scoring and interpretation
- Phishing payload construction (Veil, MSFVenom, AV evasion)
- Privilege escalation (MS16-032 exploitation)
- Post-compromise enumeration (hashdump, credential extraction)
- Social engineering (OSINT, phishing, vishing)
- Email manipulation (swaks, SMTP/POP3 enumeration)

**Tools Mastery:**
- Metasploit (exploit suggester, meterpreter, payloads)
- Burp Suite Pro (scanning, payload testing, macro recording)
- Nessus (vulnerability scanning and analysis)
- Nmap (service enumeration, OS fingerprinting)
- Evil Portal + WiFi Pineapple Mark VII (worked attack infrastructure)
- GoPhish (campaign design)
- Auxiliary tools: dig, nslookup, whois, FFUF, GoBuster, Hydra
- Custom scripting: Python, Bash (CVE mapping automation, metadata analysis)

**Frameworks & Methodology:**
- MITRE ATT&CK (technique mapping, attack chain modeling)
- OWASP Top 10 / OWASP Zap
- CIS Controls
- CVSS scoring system
- "Outside-in, breadth-then-depth" reconnaissance approach
- Rules of Engagement (ROE) / Scope of Work (SOW) discipline

**AI Security Specialization:**
- LLM attack surface understanding (from SecAI+)
- Adversarial ML concepts
- AI supply chain risks
- Published research on AI/ML security risks

**Professional Disciplines:**
- Technical documentation & reporting (areas for growth, but functional)
- Client communication (teaching background proves this)
- Classified program management (USAF experience)
- Incident response understanding (DFIR teaching background)

---

## YOUR CORE STORIES (Memorize These)

### Story 1: "My Penetration Testing Approach"
**Use this:** In Phase 1 & 2 interviews when asked to walk through an assessment

**Structure (2-3 minutes, no notes):**

"I start with reconnaissance—methodical information gathering using NMAP, DNS enumeration tools, and internet research. I identify all in-scope systems, map service versions, and prioritize targets based on exploitability.

From there, I use a breadth-first approach: scan broadly with Nessus to understand the attack surface, then select the most vulnerable hosts for deeper analysis. I analyze CVSS scores not just by number but by the specific vectors—a CVSS 10 is only dangerous if it's actually exploitable in their environment.

When I find vulnerabilities, I validate them before reporting. I don't trust automated scanner output alone—I manually confirm using Burp Suite, custom payloads, or direct exploitation with Metasploit.

My rule is simple: stay in scope, document everything, and if exploitation succeeds, I immediately determine what an attacker could do post-compromise. That's where the real value is—showing the actual impact, not just vulnerability existence.

I present findings in two layers: executive summary for decision-makers (what's the risk in business terms?), and technical details for the security team (how to fix it specifically)."

**Why this works:**
- Shows methodical, framework-based thinking
- Demonstrates tool proficiency without just listing tools
- Emphasizes validation (not trusting automation blindly)
- Shows understanding of business impact (not just technical metrics)
- Honest about your strength area (execution) and growth area (reporting)

---

### Story 2: "A Time You Overcame a Technical Challenge"
**Use this:** Behavioral/culture fit interviews (Phase 3 & 4) OR when asked about problem-solving

**Your Real Example (From PWN Challenge #3):**

"I was tasked with infiltrating a network and recovering three target files. My initial reconnaissance identified an SMTP server and a Windows workstation. I attempted Hydra brute-force against the mail server—nothing. Standard MSFVenom payload was detected by antivirus.

Rather than give up, I pivoted. I knew the mail server was open, so I used swaks to craft a phishing email targeting a user known to open attachments. I switched to Veil for payload encoding—the AV missed it. That gave me initial access.

From there, I used Metasploit's exploit suggester to identify MS16-032, an unpatched privilege escalation. That worked. I extracted credentials using hashdump and located two of my three targets.

The lesson: The first plan rarely survives contact. When AV blocked msfvenom, I adapted. When Hydra failed, I pivoted to social engineering. That's real penetration testing—not running a single tool, but thinking like an attacker and adapting when defenses work."

**Why this works:**
- Shows resilience and adaptation (not giving up at first failure)
- Demonstrates multiple technical approaches
- Honest about incomplete success (found 2 of 3 targets—that's realistic)
- Emphasizes thinking, not just tool-running
- Shows you learned something actionable

---

### Story 3: "Why I'm Pursuing CPTS (and Why Securin)"
**Use this:** When asked about motivation or growth trajectory

"I'm pursuing CPTS because I want to systematize what I've learned through labs and coursework into formal penetration testing methodology. CPTS focuses on practical, hands-on testing—which is what matters in real engagements.

Why Securin specifically: Your focus on adversarial exposure and AI-driven vulnerability management aligns with where I see the field moving. You're not doing checkbox compliance testing—you're helping enterprises think like attackers and prioritize what actually matters.

I bring both depth and breadth to that mission. My CISSP and 20 years of security leadership mean I understand enterprise risk. My SecAI+ certification and published research on AI/ML security give me insight into emerging threats. And my hands-on penetration testing work—Evil Portal deployments, phishing campaigns, exploitation at scale—proves I can execute operationally.

I see Securin as the place where I can contribute at all three levels: strategic thinking, technical execution, and emerging threat research."

**Why this works:**
- Shows you researched Securin
- Frames CPTS as intentional growth (not just cert-stacking)
- Positions your background as a value proposition (leadership + technical + research)
- Demonstrates alignment with Securin's AI-driven mission

---

## INTERVIEW PHASE BREAKDOWN

### PHASE 1 & 2: Technical Skills + Behavioral Assessment

**What They're Testing:**
- Can you talk penetration testing intelligently?
- Have you actually *done* this work?
- How do you solve problems when blocked?
- Do you fit the team?

**Questions You'll Likely Face:**

#### Technical Questions

**"Walk us through a penetration test from start to finish."**
- Answer: Use your PWN Challenge story (above)
- Show: Reconnaissance → enumeration → exploitation → post-compromise
- Prove: You validate findings and understand business impact

**"What's the difference between vulnerability assessment and penetration testing?"**
- VA = automated scanning, identifying weaknesses
- PT = validated exploitation, proving real risk, understanding impact
- You: "Nessus scan finds PHP 5.3.5. That's a vulnerability. But is it exploitable? Does the application actually use that function? Can an attacker reach it? That's penetration testing."

**"Tell us about your experience with [specific tool: Metasploit, Burp Suite, Nessus]"**
- Don't just list capabilities
- Give an example: "In Metasploit, I used the exploit suggester module to identify MS16-032 as the attack vector. I configured the meterpreter payload, set my LHOST/LPORT, and executed. That gave me System-level access."

**"How do you approach a target you've never seen before?"**
- Reconnaissance first (NMAP, DNS, Google dorking)
- Identify services and versions
- Map to known CVEs
- Prioritize by exploitability
- Validate before reporting
- This is your "outside-in, breadth-then-depth" methodology

**"What's your approach to IDS/WAF evasion?"**
- MSFVenom encoders (you've studied this)
- NOPs and payload fragmentation
- Alternative tools when primary detection
- But: "Evasion is a last resort. Better to understand why the target is there and if there's a legitimate vector."

**"Walk us through privilege escalation. How do you find unpatched systems?"**
- Metasploit exploit suggester
- Manual assessment: kernel version, Windows build, sudo misconfigs
- Google for CVE database
- Example: "MS16-032 was identified by the suggester as unpatched. I checked the Windows build number, confirmed it was vulnerable, and executed. That gave me SYSTEM."

#### Behavioral Questions

**"Tell us about a time you made a mistake. How did you handle it?"**
- Own it: Don't blame tools or users
- Show learning: What would you do differently?
- Example: "Early in my HTB labs, I relied too heavily on automated Nessus output and missed context. Now I validate every finding manually."

**"How do you stay current in offensive security?"**
- CPTS pathway (active, ~50%)
- Published research (AI/ML security)
- Teaching (forces deep knowledge)
- Hack The Box labs
- Professional development (CISOseries, Darknet Diaries)

**"Tell us about a time you had to communicate technical findings to non-technical stakeholders."**
- Teaching experience (explaining CVSS to students who don't know security)
- Your reports (executive summary vs. technical section)
- Example: "I explain CVSS as 'likelihood times impact.' A 10 means remote attackers can take full control without authentication. That's business language, not technical jargon."

**"How do you handle working under pressure or tight deadlines?"**
- Military background (rapid response, classified program management)
- Teaching + CPTS + Master's degree (competing priorities)
- Your honesty in PWN Challenge (found 2 of 3—that's realistic under time pressure)

---

### PHASE 3: VP of Operations (Ravi Pandey) + Sr. Technical Manager (Jon Guild)

**What They're Testing:**
- Do you fit the team culture?
- Can you communicate with technical leadership?
- Do you understand business context?
- Are you someone they can invest in?

**Questions You'll Face:**

**"Why Securin? What do you know about us?"**
- Research: AI-driven vulnerability management, threat researchers, CNA status
- Reference: Securin's proactive approach to adversarial defense
- Connect to you: "My SecAI+ background and published research on AI/ML security align with your mission."

**"How do you approach working in a team?"**
- You: Military discipline (team-oriented), teaching (collaboration), USAF management
- Frame: "I'm comfortable leading when needed, but I work best in teams where we collectively own outcomes."

**"Tell us about your experience managing security projects or teams."**
- USAF: Deputy Center Cybersecurity Manager, directed multi-site operations
- Teaching: Mentored students, managed curriculum design
- Story: "I led a team analyzing classified program vulnerabilities. We prioritized by risk, coordinated remediation across multiple stakeholders, and reported up to executive leadership."

**"What does good penetration testing look like to you?"**
- Thorough reconnaissance
- Validated findings (not noise)
- Business-impact framing
- Specific, actionable remediation
- Professional, clear reporting
- "It's not just identifying vulnerabilities—it's helping the client understand and fix what matters most."

**"How do you balance depth and speed?"**
- You did this in PWN Challenge (found 2 of 3 under time pressure)
- Teaching: Explain complex concepts quickly
- Frame: "I use structured notes and prioritization. I know what's exploitable, I focus there first, and I don't get lost in rabbit holes."

---

### PHASE 4 (FINAL): CPO (Hitesh Kapoor) + CEO (Srinivas Mukkamala)

**What They're Testing:**
- Strategic thinking
- Long-term fit
- Passion for the work
- Vision alignment

**Prepare These Stories:**

**"Where do you see penetration testing going in the next 5 years?"**
- AI integration (your angle: SecAI+ certification shows forward-thinking)
- Shift from reactive to proactive (Securin's mission)
- Emerging attack surfaces (cloud, API, AI supply chain)
- Your take: "As more of the attack surface becomes automated and AI-driven, penetration testers need to think like AI-powered attackers. That's where my AI security focus comes in."

**"Tell us about a research project or publication you've worked on."**
- Your paper on cyber insider threats (socio-economic perspective)
- AI/ML security risks publication
- Frame: "I'm not just executing engagements—I'm contributing to the field's understanding of emerging threats."

**"What excites you most about this role?"**
- Honest answer: Working with a team that values methodology and rigor
- Securin's mission: Proactive, adversarial approach
- Your contribution: Execution + AI security + teaching/leadership

**Questions to Ask Them (This is Your Chance):**
- "How does Securin approach emerging threats like AI supply chain attacks?"
- "What's your team structure? How do pentesting engagements get staffed?"
- "How do you balance thorough testing with client timelines?"
- "Where do you see the biggest gaps in the market that Securin is addressing?"
- "How does Securin foster continuous learning and skill development?"

---

## TECHNICAL DEEP-DIVE PREP

### MITRE ATT&CK Fluency

<cite index="7-1">Penetration testing phases typically include pre-engagement (scoping and rules of engagement), reconnaissance and scanning, vulnerability identification, exploitation, post-exploitation, reporting, and cleanup.</cite>

**Be Ready to Map Attack Chains Using ATT&CK:**

Your PWN Challenge chain in ATT&CK terms:
1. **Reconnaissance** (T1598: Phishing for Information via DNS enumeration)
2. **Initial Access** (T1566: Phishing with malicious attachment)
3. **Execution** (T1204: User Execution of Malicious File)
4. **Defense Evasion** (T1027: Obfuscated Files or Information via Veil encoding)
5. **Persistence** (T1547: Boot or Logon Autostart Execution via meterpreter reverse shell)
6. **Privilege Escalation** (T1548: Abuse Elevation Control Mechanism via MS16-032)
7. **Credential Access** (T1110: Brute Force + T1056: Keylogging/hashdump)

**Practice this mapping for your stories.**

---

### CVSS Scoring Mastery

Be ready to explain your CVSS analysis. Example from your Vuln Scan:

**PHP 5.3.5 — CVSS 10**
- Attack Vector: Network (CVSS 1.0 multiplier)
- Attack Complexity: Low (1.0)
- Privileges Required: None (1.0)
- User Interaction: None (1.0)
- Scope: Unchanged (1.0)
- Confidentiality Impact: High (impact multiplier)
- Integrity Impact: High
- Availability Impact: High
= **CVSS 10 (Critical)**

**Business Translation:** "An unauthenticated remote attacker can execute arbitrary code on your web server without any user interaction. This means they can steal data, modify data, or shut down your website."

---

### Exploitation Question Examples

**"How would you exploit an out-of-date PHP 5.3.5 vulnerability?"**
1. Identify the specific CVE (e.g., bzread() out-of-bounds write)
2. Search for public exploits (Google, Exploit-DB)
3. Understand the exploit mechanism (what function, what memory corruption)
4. Craft the payload (may require specific PHP functions to be enabled)
5. Validate success (RCE proof, shell access)
6. Document proof (screenshot, command output)

---

## FINAL PREP CHECKLIST

**One Week Before Phase 1 & 2:**
- [ ] Practice your penetration testing story (2-3 min, memorized but natural)
- [ ] Practice your "overcome a challenge" story (PWN Challenge reframing)
- [ ] Practice explaining CVSS scoring
- [ ] Map your PWN Challenge to MITRE ATT&CK tactics
- [ ] Review your tools (Metasploit, Burp, Nessus) — be ready to talk through usage
- [ ] Prepare 3 behavioral examples (mistake + learning, team collaboration, pressure handling)

**One Week Before Phase 3:**
- [ ] Research Securin (mission, clients, company culture from LinkedIn)
- [ ] Research Ravi Pandey and Jon Guild (LinkedIn, look for themes)
- [ ] Prepare "Why Securin specifically?" answer
- [ ] Practice your USAF/leadership story
- [ ] Prepare 5 strategic questions for them

**One Week Before Phase 4:**
- [ ] Research Hitesh Kapoor and Srinivas Mukkamala (LinkedIn)
- [ ] Refine "future of pentesting" answer
- [ ] Prepare your research/publication story
- [ ] Practice discussing AI security angle (SecAI+)
- [ ] Prepare closing statement about fit and contribution

---

## INTERVIEW DAY EXECUTION

### Before Each Interview
- Sleep well night before
- Test tech setup 30 min early (video, mic, lighting)
- Dress: Business casual minimum (full business for Phase 4)
- Have water nearby
- Have notebook for notes
- Review your resume and these talking points (not word-for-word, but concepts)

### During Each Interview
1. **Listen completely before answering** — Don't interrupt
2. **Answer directly** — 2-3 minutes is ideal
3. **Use specific examples** — Not general statements
4. **Show your thinking** — "Here's how I approached it..."
5. **Admit what you don't know** — "I haven't worked with X before, but here's my approach..."
6. **Ask clarifying questions** — Shows you're thinking
7. **Maintain eye contact** (or look at camera)
8. **Speak clearly** — No filler words ("uh," "like")

### After Each Interview
- Send thank-you email within 2 hours
- Personalize it (mention something specific they said)
- Express continued interest
- Keep it short (3-4 sentences)

---

## RED FLAGS TO AVOID

❌ Exaggerate skills or fake experience  
❌ Criticize previous employers or teachers  
❌ Admit you don't know MITRE ATT&CK (say "I can learn quickly" instead)  
❌ Be overly casual or disengaged  
❌ Check your phone during interview  
❌ Ramble or go over 3 minutes on answers  

✅ Be authentic  
✅ Show enthusiasm for offensive security  
✅ Demonstrate preparation  
✅ Ask thoughtful questions  
✅ Follow up professionally  

---

## KEY MANTRAS FOR THESE INTERVIEWS

**"Deep understanding over tool-running"** — You don't just run Metasploit; you understand what exploit you're running, why it works, what the target is doing, and what the impact is.

**"Precision execution, ethical discipline"** — Everything you do is documented, in scope, and within rules of engagement.

**"Information superiority"** — You gather information systematically, prioritize targets methodically, and adapt when conditions change.

**Your Actual Differentiator:** You combine elite-level offensive skills with strategic thinking and teaching ability. Most penetration testers have the first. You have all three.

---

## FINAL THOUGHT

You've built a genuinely strong application. You have certifications most people never get, real hands-on penetration testing experience, and the discipline to stay ethical and focused.

Securin is hiring you to identify and exploit vulnerabilities in their clients' systems. You've done exactly that in your CMU coursework and USAF role.

You know this material. Trust your preparation. Be confident.

Good luck.
