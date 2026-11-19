---
layout: default
title: Bricks Heist
permalink: /thm-writeups/bricks-heist/
---

<link rel="stylesheet" href="/assets/main.css">

# A1Gh0st | Bricks Heist



<nav style="background-color:#101827; padding:15px; border:1px solid #00e5ff; border-radius:6px;">
  <a href="/" style="color:#00e5ff; background:transparent; text-decoration:none;">Home</a>
  &nbsp; | &nbsp;
  <a href="/projects/" style="color:#00e5ff; background:transparent; text-decoration:none;">Projects</a>
  &nbsp; | &nbsp;
  <a href="/thm-writeups/" style="color:#00e5ff; background:transparent; text-decoration:none;">Try Hack Me Write-ups</a>
</nav>




---

# TryHackMe: Bricks Heist

**Platform:** TryHackMe  
**Room:** TryHack3M: Bricks Heist  
**Completed:** November 19, 2026  
**Status:** Completed  
**Category:** Penetration Testing / Incident Investigation

## Overview

This lab focused on identifying and exploiting a critical WordPress vulnerability, investigating suspicious system activity, and analyzing evidence of cryptocurrency mining.

## Tools Used

- Nmap
- SearchSploit
- Metasploit Framework
- Meterpreter
- Linux command-line utilities
- grep, sed, xxd, and Base64

## Investigation Summary

### 1. Reconnaissance

Performed network scanning and discovered exposed services, including SSH, HTTP, HTTPS, and MySQL.

### 2. Vulnerability Identification

Identified CVE-2024-25600, a critical unauthenticated remote code execution vulnerability affecting WordPress Bricks Builder.

### 3. Exploitation

Used Metasploit to exploit the vulnerable application and establish a Meterpreter session under the apache account.

### 4. Post-Exploitation

Investigated accessible files, suspicious processes, and system services associated with potentially malicious activity.

### 5. Cryptocurrency Mining Investigation

Analyzed mining-related logs and decoded an embedded Bitcoin wallet address using hexadecimal and Base64 decoding.

## Key Takeaway

My biggest takeaway was understanding how reconnaissance, vulnerability research, exploitation, and post-exploitation investigation connect.

Every finding helped determine my next step. This exercise reinforced the importance of documenting evidence and understanding why a vulnerability exists instead of simply running an exploit.





<h2>Full Technical Report</h2>

<p>Read my complete 12-page Bricks Heist penetration testing report below.</p>

<iframe
  src="/A1Gh0st_Bricks_Heist_Penetration_Test_Report.pdf"
  width="100%"
  height="750"
  style="border:1px solid #00e5ff; border-radius:8px;"
  title="Bricks Heist Penetration Testing Report">
</iframe>

<p>
  <a href="/A1Gh0st_Bricks_Heist_Penetration_Test_Report.pdf"
     target="_blank" rel="noopener noreferrer">
    Open Full Report in New Tab
  </a>
</p>

## Download

[Download Full Penetration Testing Report (PDF)](/A1Gh0st_Bricks_Heist_Penetration_Test_Report.pdf)


