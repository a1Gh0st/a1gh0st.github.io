---
layout: default
title: TryHackMe Write-Ups
permalink: /tryhackme-writeups/
---

<link rel="stylesheet" href="/assets/main.css">

# A1Gh0st | TryHackMe Writeups

<nav style="background-color:#101827; padding:15px; border:1px solid #00e5ff; border-radius:6px;">
  <a href="/" style="color:#00e5ff; background:transparent; text-decoration:none;">Home</a>
  &nbsp; | &nbsp;
  <a href="/projects/" style="color:#00e5ff; background:transparent; text-decoration:none;">Projects</a>
  &nbsp; | &nbsp;
  <a href="/thm-writeups/" style="color:#00e5ff; background:transparent; text-decoration:none;">TryHackMe Write-ups</a>
</nav>

---

## Welcome to My TryHackMe Write-ups

This is where I document my hands-on cybersecurity training, including vulnerability research, exploitation, system enumeration, and security investigations.

My goal is to develop practical penetration testing skills while documenting what I learn along the way.

---

## Featured Write-up: Bricks Heist

**Platform:** TryHackMe  
**Room:** TryHack3M: Bricks Heist  
**Date Completed:** November 19, 2026  
**Category:** Penetration Testing / Incident Investigation  
**Status:** Completed

### Objective

Investigate a vulnerable WordPress application, identify security weaknesses, gain authorized access, and analyze evidence of suspicious cryptocurrency mining activity.

### Tools Used

- Nmap
- Firefox Developer Tools
- SearchSploit
- Metasploit Framework
- Meterpreter
- Linux command-line utilities
- grep, sed, xxd, and Base64

### Key Findings

**1. Network Reconnaissance**

Used Nmap to identify exposed services and investigate potential attack surfaces.

**2. Vulnerability Discovery**

Identified CVE-2024-25600, a critical remote code execution vulnerability affecting WordPress Bricks Builder.

**3. Exploitation**

Successfully exploited the vulnerability using Metasploit and established a Meterpreter session under the apache account.

**4. Post-Exploitation Investigation**

Investigated suspicious processes, system services, and files associated with cryptocurrency mining activity.

**5. Log Analysis**

Recovered and analyzed mining-related logs from the compromised system.

**6. Encoded Data Analysis**

Used hexadecimal and Base64 decoding to recover an embedded Bitcoin wallet address.

### Biggest Takeaway

This lab taught me how different penetration testing techniques connect during a real investigation.

I started with reconnaissance, identified a vulnerable application, researched the vulnerability, successfully exploited it, and investigated suspicious activity after gaining access.

The biggest lesson was understanding why each step matters and how evidence guides the next step of an investigation.

### Full Penetration Testing Report

A detailed 12-page technical report documenting the methodology, commands, findings, and remediation recommendations is available.

**PDF report link coming soon.**

---

## More Writeups Coming Soon

As I complete additional TryHackMe rooms, I'll document:

- Reconnaissance and enumeration
- Vulnerability assessment
- Web application exploitation
- Linux and Windows privilege escalation
- Post-exploitation investigation
- Security tools and techniques
- Lessons learned
