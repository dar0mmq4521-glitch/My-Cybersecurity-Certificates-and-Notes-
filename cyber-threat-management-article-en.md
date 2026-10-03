# From Governance to Incident Response: What I Learned from Cisco's Cyber Threat Management Course

I recently completed **Cyber Threat Management** on Cisco Networking Academy, all six modules. When I sat down to go through my notes after each one, I noticed something I didn't expect: the course wasn't teaching me scattered tools. It was drawing a full picture of how an organization actually protects itself, from the first policy written down to the last report filed after an incident.

## The Start: Governance Before Anything Technical

The first module wasn't about tools or attacks, it was about **Governance**. That surprised me, honestly, because I expected cybersecurity to start with the technical side. But I learned that governance decides who has the authority to make decisions about risk, while management is what actually implements those decisions. I came across roles like Data Owner and Data Custodian, and the different types of security policies an organization needs.

What stuck with me most was the ethics side: as a future specialist, I'll have the same skills a malicious actor has. The only real difference is ethics. That's what connected this module directly to something I'm already interested in: **GRC** (Governance, Risk, Compliance).

## Next: How We Actually Test Protection

Module two moved from "the rules" to "testing them." I learned the difference between vulnerability scanning and penetration testing — one discovers, the other actually tries to exploit, with permission. I got familiar with core command-line tools like ping, tracert, and nmap, and the distinction between SIEM (which collects and monitors) and SOAR (which responds automatically).

The clearest moment for me was comparing Telnet traffic to SSH traffic in Wireshark: you literally watch unencrypted data get read character by character, while SSH hides it completely. Some things you only really understand once you see them.

## Threat Intelligence: Security Doesn't Happen in Isolation

Module three taught me that a good analyst doesn't just defend, they follow. I learned about CVE as a universal identifier for vulnerabilities, and standards like STIX and TAXII that let organizations share threat information automatically. I also saw how SIEM and SOAR stop being just internal tools and become part of a much larger system that shares indicators in real time.

## Vulnerability Assessment: From "Normal" to "Suspicious"

Module four centered on a simple but deep idea: you can't detect anomalies until you know what "normal" looks like. That's the whole point of network and server profiling. I also learned the **CVSS** system for scoring vulnerability severity from 0 to 10, and that anything above 3.9 is worth addressing.

## Risk Management: Where the Numbers Talk

Module five was the closest to how my mind naturally works. I learned simple but powerful formulas: asset value × exposure factor gives the expected loss from a single event, and that number × the annual rate of occurrence gives the expected annual loss. These are the numbers that actually convince leadership to spend on security, not just "we need a bigger security budget."

## The Final Stretch: When the Breach Actually Happens

The sixth and final module covered the hardest moment: the incident already happened, now what? I learned about chain of custody and why every step with digital evidence has to be documented, and about the **Cyber Kill Chain**, seven stages showing how an attack escalates from reconnaissance to achieving its objective. Breaking the chain at any single stage means the attack fails.

## Where This Leaves Me

Honestly, this course gave me the full map, but it didn't turn me into a ready analyst. I now understand how the pieces connect: governance sets the rules, testing confirms they're applied, intelligence tracks the threat, assessment measures severity, risk management decides priority, and response handles reality when every earlier layer fails.

What I still need is hands-on practice, not just tools described in theory. My next step is trying some of these concepts in a virtual lab, before preparing for the Security+ certification.

---

**#CyberSecurity #CiscoNetAcad #RiskManagement #IncidentResponse #GRC**
