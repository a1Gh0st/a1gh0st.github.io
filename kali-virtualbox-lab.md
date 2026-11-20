---
layout: default
title: Kali Linux VirtualBox Lab | A1Gh0st
permalink: /projects/kali-virtualbox-lab/
---

<link rel="stylesheet" href="/assets/main.css">

<nav aria-label="Portfolio navigation" style="background-color:#101827; padding:15px; border:1px solid #00e5ff; border-radius:6px;">
  <a href="/" style="color:#00e5ff; background:transparent; text-decoration:none;">Home</a>
  &nbsp; | &nbsp;
  <a href="/about/" style="color:#00e5ff; background:transparent; text-decoration:none;">About A1Gh0st</a>
  &nbsp; | &nbsp;
  <a href="/goals/" style="color:#00e5ff; background:transparent; text-decoration:none;">Goals</a>
  &nbsp; | &nbsp;
  <a href="/projects/" style="color:#00e5ff; background:transparent; text-decoration:none;">Projects</a>
  &nbsp; | &nbsp;
  <a href="/thm-writeups/" style="color:#00e5ff; background:transparent; text-decoration:none;">TryHackMe Write-ups</a>
</nav>

<div class="a1-projects a1-lab">
  <p class="a1-breadcrumb"><a href="/projects/">Projects</a> / Kali Linux VirtualBox Lab</p>
  <div class="a1-lab-header">
    <p class="a1-kicker">PROJECT 002 / VIRTUAL SECURITY LAB</p>
    <h1>Kali Linux VirtualBox Lab</h1>
    <span class="a1-status" style="background:#143a38;color:#86f1d4;border-color:#297e79;">In Progress</span>
    <p class="a1-lead">A working Kali Linux virtual machine created with Oracle VirtualBox for learning Linux, networking, and authorized penetration-testing workflows.</p>
    <div class="a1-tags">
      <span>VirtualBox</span><span>Kali Linux</span><span>Virtualization</span><span>Networking</span><span>Ethical Hacking</span>
    </div>
  </div>
</div>

## Project Overview

The goal of this project is to build a repeatable, isolated virtual learning environment where Linux administration and offensive-security techniques can be practiced safely.

**Verified so far:** Oracle VirtualBox has been installed, Kali Linux has been installed as a guest virtual machine, and the Kali graphical desktop boots successfully. This was confirmed by a desktop screenshot.

**Still to verify:** Network connectivity, system updates, virtual hardware configuration, snapshots, and security-tool operation. These are future steps, not completed results.

This VirtualBox project is separate from the [Linux Home Lab](/projects/linux-home-lab/), which concerns assessing and rebuilding a physical desktop computer.

## Project Objectives

1. Install a Linux guest operating system in an isolated virtual machine.
2. Record virtual machine specifications and network configuration.
3. Establish a clean, updated, recoverable baseline.
4. Explore Linux commands, tools, network behavior, and troubleshooting.
5. Document authorized exercises with repeatable steps and evidence.

## Environment Inventory

<div style="overflow-x:auto;border:1px solid #35536a;border-radius:10px;margin:1rem 0 1.5rem;background:#101827;">
<div role="table" aria-label="Kali VirtualBox environment inventory" style="display:block;min-width:620px;width:100%;color:#e2e8f0;">
  <div role="row" style="display:grid;grid-template-columns:30% 46% 24%;background:#173047;border-bottom:1px solid #35536a;">
    <div role="columnheader" style="padding:12px 14px;border-right:1px solid #35536a;font-weight:700;color:#00e5ff;">Component</div>
    <div role="columnheader" style="padding:12px 14px;border-right:1px solid #35536a;font-weight:700;color:#00e5ff;">Current record</div>
    <div role="columnheader" style="padding:12px 14px;font-weight:700;color:#00e5ff;">Status</div>
  </div>
  <div role="row" style="display:grid;grid-template-columns:30% 46% 24%;background:#101827;border-bottom:1px solid #35536a;">
    <div role="rowheader" style="padding:12px 14px;border-right:1px solid #35536a;color:#c5e9f5;font-weight:700;">Virtualization software</div>
    <div role="cell" style="padding:12px 14px;border-right:1px solid #35536a;color:#e2e8f0;">Oracle VirtualBox</div>
    <div role="cell" style="padding:12px 14px;color:#c2d6df;">Installed</div>
  </div>
  <div role="row" style="display:grid;grid-template-columns:30% 46% 24%;background:#142236;border-bottom:1px solid #35536a;">
    <div role="rowheader" style="padding:12px 14px;border-right:1px solid #35536a;color:#c5e9f5;font-weight:700;">Guest operating system</div>
    <div role="cell" style="padding:12px 14px;border-right:1px solid #35536a;color:#e2e8f0;">Kali Linux</div>
    <div role="cell" style="padding:12px 14px;color:#c2d6df;">Installed; desktop boot confirmed</div>
  </div>
  <div role="row" style="display:grid;grid-template-columns:30% 46% 24%;background:#101827;border-bottom:1px solid #35536a;">
    <div role="rowheader" style="padding:12px 14px;border-right:1px solid #35536a;color:#c5e9f5;font-weight:700;">Virtual machine state</div>
    <div role="cell" style="padding:12px 14px;border-right:1px solid #35536a;color:#e2e8f0;">Boots into Kali graphical desktop</div>
    <div role="cell" style="padding:12px 14px;color:#c2d6df;">Verified</div>
  </div>
  <div role="row" style="display:grid;grid-template-columns:30% 46% 24%;background:#142236;border-bottom:1px solid #35536a;">
    <div role="rowheader" style="padding:12px 14px;border-right:1px solid #35536a;color:#c5e9f5;font-weight:700;">Kali release and kernel</div>
    <div role="cell" style="padding:12px 14px;border-right:1px solid #35536a;color:#e2e8f0;">Not yet recorded</div>
    <div role="cell" style="padding:12px 14px;color:#c2d6df;">To verify</div>
  </div>
  <div role="row" style="display:grid;grid-template-columns:30% 46% 24%;background:#101827;border-bottom:1px solid #35536a;">
    <div role="rowheader" style="padding:12px 14px;border-right:1px solid #35536a;color:#c5e9f5;font-weight:700;">Virtual CPU, RAM, disk</div>
    <div role="cell" style="padding:12px 14px;border-right:1px solid #35536a;color:#e2e8f0;">Specifications not yet recorded</div>
    <div role="cell" style="padding:12px 14px;color:#c2d6df;">To verify</div>
  </div>
  <div role="row" style="display:grid;grid-template-columns:30% 46% 24%;background:#142236;border-bottom:1px solid #35536a;">
    <div role="rowheader" style="padding:12px 14px;border-right:1px solid #35536a;color:#c5e9f5;font-weight:700;">Virtual network adapter mode</div>
    <div role="cell" style="padding:12px 14px;border-right:1px solid #35536a;color:#e2e8f0;">Not yet recorded</div>
    <div role="cell" style="padding:12px 14px;color:#c2d6df;">To verify</div>
  </div>
  <div role="row" style="display:grid;grid-template-columns:30% 46% 24%;background:#101827;border-bottom:1px solid #35536a;">
    <div role="rowheader" style="padding:12px 14px;border-right:1px solid #35536a;color:#c5e9f5;font-weight:700;">Internet / DNS connectivity</div>
    <div role="cell" style="padding:12px 14px;border-right:1px solid #35536a;color:#e2e8f0;">Not yet tested in this project log</div>
    <div role="cell" style="padding:12px 14px;color:#c2d6df;">Pending</div>
  </div>
  <div role="row" style="display:grid;grid-template-columns:30% 46% 24%;background:#142236;">
    <div role="rowheader" style="padding:12px 14px;border-right:1px solid #35536a;color:#c5e9f5;font-weight:700;">Updates, snapshots, tooling</div>
    <div role="cell" style="padding:12px 14px;border-right:1px solid #35536a;color:#e2e8f0;">Not yet verified</div>
    <div role="cell" style="padding:12px 14px;color:#c2d6df;">Pending</div>
  </div>
</div>
</div>

*Unverified specifications are intentionally left blank until they can be confirmed inside VirtualBox and Kali. Private host details and unnecessary network identifiers will not be published.*

## Build Milestones

<div class="a1-projects a1-milestones">
  <div class="a1-milestone" style="border-color:#297e79;">
    <span>01</span>
    <div><strong>Install VirtualBox</strong><small>A virtualization environment is available for the lab.</small></div>
    <em style="color:#65e6bf;">Complete</em>
  </div>
  <div class="a1-milestone" style="border-color:#297e79;">
    <span>02</span>
    <div><strong>Install Kali Linux VM</strong><small>Kali is installed as a guest operating system in VirtualBox.</small></div>
    <em style="color:#65e6bf;">Complete</em>
  </div>
  <div class="a1-milestone" style="border-color:#297e79;">
    <span>03</span>
    <div><strong>Boot into Kali desktop</strong><small>A screenshot confirms the Kali graphical desktop is running.</small></div>
    <em style="color:#65e6bf;">Complete</em>
  </div>
  <div class="a1-milestone" style="border-color:#2b3e50;">
    <span>04</span>
    <div><strong>Document VM configuration</strong><small>Record guest OS version, allocated memory, CPU, disk, and network mode.</small></div>
    <em style="color:#8beefa;">Next</em>
  </div>
  <div class="a1-milestone" style="border-color:#2b3e50;">
    <span>05</span>
    <div><strong>Validate networking and updates</strong><small>Test DNS and internet access; run and record system updates.</small></div>
    <em style="color:#b3c5d2;">Pending</em>
  </div>
  <div class="a1-milestone" style="border-color:#2b3e50;">
    <span>06</span>
    <div><strong>Create a clean snapshot</strong><small>Save a restore point after confirming the baseline is stable.</small></div>
    <em style="color:#b3c5d2;">Pending</em>
  </div>
  <div class="a1-milestone" style="border-color:#2b3e50;">
    <span>07</span>
    <div><strong>Baseline tools and authorized exercises</strong><small>Confirm tool versions, choose safe targets, and publish reproducible exercises.</small></div>
    <em style="color:#b3c5d2;">Pending</em>
  </div>
</div>

## Verification Plan

The following commands are examples for upcoming verification. **They have not yet been recorded as executed or successful.**

```bash
# Identify the Kali installation and running kernel
cat /etc/os-release
uname -r

# Inspect guest networking
ip -brief address
ip route

# Test basic networking and name resolution
ping -c 4 1.1.1.1
getent hosts kali.org
```

After connectivity and configuration checks, the plan is to update system packages, create a VirtualBox snapshot, and establish a known-good baseline before adding tools or conducting exercises.

## Lab Boundaries

Any penetration testing will be limited to intentionally vulnerable training targets, local machines owned by the lab, or systems with explicit authorization. The Kali VM itself does not imply that external targets are approved for testing.

For early experiments, an isolated or carefully configured virtual network is preferable to exposing vulnerable machines directly to a home or public network.

## Evidence and Documentation

**Initial evidence:** A screenshot of the Kali desktop demonstrates that the graphical guest environment is running. The screenshot has not yet been published as a repository asset; this page records the verified outcome without claiming additional configuration or testing.

Future updates will document VM settings, command output, changes made, errors encountered, and lessons learned. Screenshots will be reviewed for identifying information before publication.

## Project Log

**November 2026:** VirtualBox and Kali Linux installation confirmed. Kali successfully reached its graphical desktop. Environment inventory, networking checks, package updates, and snapshots remain to be documented.

---

[Back to Projects](/projects/)

**A1Gh0st**  
*Learning. Practicing. Documenting.*
