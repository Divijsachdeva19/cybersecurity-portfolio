# Divij Sachdeva – Cybersecurity Portfolio

## About Me
Hi, I'm Divij Sachdeva, a Bachelor of Information Technology (Business Analysis)
student at Federation University. This repo is my cybersecurity portfolio for
**ITECH1502 Cybersecurity Fundamentals**, where I'm documenting the hands-on
training and projects I complete throughout the unit.

**Student email:** dsachdeva@students.federation.edu.au
**Student ID:** 30486812

---

## Project 1: SOC Fundamentals (TryHackMe) — Security Operations & Alert Triage

**Platform:** TryHackMe
**Topic area:** Security Operations Centre (SOC) fundamentals, alert triage, SIEM analysis
**Status:** ✅ Completed — Room progress 100%, 7/7 tasks completed, 128 points earned

### Overview
This room walks through how a Security Operations Centre (SOC) detects, triages
and responds to security alerts. It covers what a SOC actually does, how SOC teams
are structured, the "5 Ws" framework analysts use to investigate alerts, and the
different tools (SIEM, EDR, Firewall) a SOC relies on day to day. It finishes with
a practical exercise where you investigate a real alert in a simulated SIEM
dashboard.

### Objectives
- Understand the core capabilities of a SOC: Detection, Response, and catching
  unauthorized activity/policy violations
- Learn the three pillars of a SOC: People, Process, and Technology
- Understand SOC team roles and escalation (L1/L2/L3 Analysts, Security Engineer,
  Detection Engineer, SOC Manager)
- Use the "5 Ws" (What, When, Where, Who, Why) to triage a security alert
- Understand what SIEM, EDR, and Firewall each actually do in a SOC
- Investigate a live alert in a simulated SIEM and decide if it's a true positive
  or false positive

### Methodology
1. Went through the theory tasks on what a SOC does, the three pillars (People,
   Process, Technology), and how SOC teams are structured/escalate alerts.
2. Learned the 5 Ws framework (What/When/Where/Who/Why) and practiced applying it
   to sample scenarios.
3. Covered how SIEM, EDR, and Firewall solutions each play a part in detecting and
   responding to threats.
4. Did the practical exercise: investigated a "Port Scanning Activity Detected"
   alert in a simulated SIEM dashboard.
   - Worked out the activity (**Port Scan**), the time (**June 12, 2024, 17:24**),
     and the destination host (**10.0.0.3**) using the traffic logs.
   - Figured out the scan was **Intended**, not an attack — the case notes said
     the vulnerability assessment team had already told the SOC team they were
     running it.
   - Checked whether a response was sent back to the scanning IP by spotting the
     reverse-direction log entry in the traffic table.
   - Closed the alert as a **False Positive** since it turned out to be expected,
     authorized activity rather than a genuine incident.
5. Finished the room at 100% (7/7 tasks).

### Evidence

<img width="1280" height="832" alt="Screenshot 2026-10-06 at 11 48 48 AM" src="https://github.com/user-attachments/assets/087f6735-fb28-454a-81a8-42a28618f7b2" />
<img width="1280" height="832" alt="Screenshot 2026-10-06 at 12 06 56 PM" src="https://github.com/user-attachments/assets/ee14381a-5840-404f-a444-abc04975cc7d" />
<img width="1280" height="832" alt="Screenshot 2026-10-06 at 12 07 43 PM" src="https://github.com/user-attachments/assets/96e61cee-a4a7-4f5a-a63d-6addc94f99aa" />



### What I Learned
This room showed me that SOC work isn't just about having the right tools — a lot
of it comes down to process and judgement. The exact same alert (a port scan) can
be a real threat or completely normal depending on the context, and the 5 Ws give
you a simple way to work that out quickly instead of panicking over every alert.
It also helped me understand how a SIEM pulls together raw logs into something an
analyst can actually investigate, and why communication between teams (like the
vulnerability assessment team giving the SOC a heads-up) matters just as much as
the technical side of detection.

---

## Skills Demonstrated
- SOC fundamentals and alert triage
- Applying the 5 Ws framework to security investigations
- Reading and interpreting SIEM traffic/log data
- Telling the difference between a true positive and a false positive alert
- Understanding how SIEM, EDR, and Firewall fit into a SOC's tech stack
- Technical documentation

---

## Repository Structure
```
├── README.md
├── screenshots/
│   └── (evidence images go here)
└── report/
    └── (final PDF/Word report, optional copy)
```
