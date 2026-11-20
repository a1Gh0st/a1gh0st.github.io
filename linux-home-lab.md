---
layout: default
title: Linux Home Lab | A1Gh0st
permalink: /projects/linux-home-lab/
---

<link rel="stylesheet" href="/assets/main.css">

<nav aria-label="Portfolio navigation" style="background-color:#101827; padding:15px; border:1px solid #00e5ff; border-radius:6px;">
  <a href="/" style="color:#00e5ff; background:transparent; text-decoration:none;">Home</a>
  &nbsp; | &nbsp;
  <a href="/about/" style="color:#00e5ff; background:transparent; text-decoration:none;">About A1Gh0st</a>
  &nbsp; | &nbsp;
  <a href="/projects/" style="color:#00e5ff; background:transparent; text-decoration:none;">Projects</a>
  &nbsp; | &nbsp;
  <a href="/thm-writeups/" style="color:#00e5ff; background:transparent; text-decoration:none;">TryHackMe Write-ups</a>
</nav>

<div class="a1-projects a1-lab">

<p class="a1-breadcrumb"><a href="/projects/">Projects</a> / Linux Home Lab</p>

<div class="a1-lab-header">
  <p class="a1-kicker">PROJECT 001 / BUILD LOG</p>
  <h1>Linux Home Lab</h1>
  <span class="a1-status a1-status-planning">Planning</span>
  <p class="a1-lead">A practical desktop rebuild that will become a Linux environment for system administration, networking, and authorized security exercises.</p>
  <div class="a1-tags"><span>Linux</span><span>Desktop Hardware</span><span>Networking</span><span>System Hardening</span></div>
</div>

</div>

## Project Overview

The starting point is an existing desktop computer with a usable-looking case and internal components that need inspection. Rather than assuming the machine is functional, this project begins with a hardware inventory and a decision about what can safely be reused.

The intended result is a reliable Linux system that supports repeatable experiments, documentation, and further cybersecurity learning.

**Current status:** Planning. Hardware specifications, replacement parts, operating system choice, and performance results have not yet been confirmed.

## Objectives

1. **Inspect the computer:** Identify and document installed components, missing parts, connections, and visible damage.
2. **Plan the rebuild:** Determine which parts can be retained and what needs replacement or testing.
3. **Install Linux:** Select a distribution appropriate for a general-purpose learning lab, complete installation, and record system configuration.
4. **Establish a baseline:** Configure updates, users, access controls, networking, backups, and basic system monitoring.
5. **Practice and document:** Use the finished system for owned or authorized networking and security exercises, recording what worked and what did not.

## Hardware Inventory

<div style="overflow-x:auto;background-color:#101827 !important;border:1px solid #2a5368;border-radius:10px;margin:1rem 0 1.5rem;">
<table class="a1-hardware-inventory" style="width:100%;margin:0;border:0;border-collapse:collapse;background-color:#101827 !important;color:#e2e8f0 !important;">
  <thead style="background-color:#173047 !important;">
    <tr style="background-color:#173047 !important;">
    <th scope="col" style="background-color:#173047 !important;color:#00e5ff !important;padding:12px 15px !important;border:0 !important;border-bottom:1px solid #2b4056 !important;text-align:left;vertical-align:top;">Component</th>
    <th scope="col" style="background-color:#173047 !important;color:#00e5ff !important;padding:12px 15px !important;border:0 !important;border-bottom:1px solid #2b4056 !important;text-align:left;vertical-align:top;">Current record</th>
    </tr>
  </thead>
  <tbody style="background-color:#101827 !important;">
    <tr style="background-color:#101827 !important;">
    <th scope="row" style="background-color:#101827 !important;color:#c5e9f5 !important;padding:12px 15px !important;border:0 !important;border-bottom:1px solid #2b4056 !important;text-align:left;vertical-align:top;">Case / chassis</th>
    <td style="background-color:#101827 !important;color:#e2e8f0 !important;padding:12px 15px !important;border:0 !important;border-bottom:1px solid #2b4056 !important;text-align:left;vertical-align:top;">Existing case available; detailed inspection pending</td>
    </tr>
    <tr style="background-color:#142236 !important;">
    <th scope="row" style="background-color:#142236 !important;color:#c5e9f5 !important;padding:12px 15px !important;border:0 !important;border-bottom:1px solid #2b4056 !important;text-align:left;vertical-align:top;">Motherboard and CPU</th>
    <td style="background-color:#142236 !important;color:#e2e8f0 !important;padding:12px 15px !important;border:0 !important;border-bottom:1px solid #2b4056 !important;text-align:left;vertical-align:top;">Not yet verified</td>
    </tr>
    <tr style="background-color:#101827 !important;">
    <th scope="row" style="background-color:#101827 !important;color:#c5e9f5 !important;padding:12px 15px !important;border:0 !important;border-bottom:1px solid #2b4056 !important;text-align:left;vertical-align:top;">RAM</th>
    <td style="background-color:#101827 !important;color:#e2e8f0 !important;padding:12px 15px !important;border:0 !important;border-bottom:1px solid #2b4056 !important;text-align:left;vertical-align:top;">Not yet verified</td>
    </tr>
    <tr style="background-color:#142236 !important;">
    <th scope="row" style="background-color:#142236 !important;color:#c5e9f5 !important;padding:12px 15px !important;border:0 !important;border-bottom:1px solid #2b4056 !important;text-align:left;vertical-align:top;">Storage</th>
    <td style="background-color:#142236 !important;color:#e2e8f0 !important;padding:12px 15px !important;border:0 !important;border-bottom:1px solid #2b4056 !important;text-align:left;vertical-align:top;">Not yet verified</td>
    </tr>
    <tr style="background-color:#101827 !important;">
    <th scope="row" style="background-color:#101827 !important;color:#c5e9f5 !important;padding:12px 15px !important;border:0 !important;border-bottom:1px solid #2b4056 !important;text-align:left;vertical-align:top;">Power supply and cooling</th>
    <td style="background-color:#101827 !important;color:#e2e8f0 !important;padding:12px 15px !important;border:0 !important;border-bottom:1px solid #2b4056 !important;text-align:left;vertical-align:top;">Not yet verified</td>
    </tr>
    <tr style="background-color:#142236 !important;">
    <th scope="row" style="background-color:#142236 !important;color:#c5e9f5 !important;padding:12px 15px !important;border:0 !important;border-bottom:1px solid #2b4056 !important;text-align:left;vertical-align:top;">Network connectivity</th>
    <td style="background-color:#142236 !important;color:#e2e8f0 !important;padding:12px 15px !important;border:0 !important;border-bottom:1px solid #2b4056 !important;text-align:left;vertical-align:top;">Not yet verified</td>
    </tr>
    <tr style="background-color:#101827 !important;">
    <th scope="row" style="background-color:#101827 !important;color:#c5e9f5 !important;padding:12px 15px !important;border:0 !important;text-align:left;vertical-align:top;">Linux distribution</th>
    <td style="background-color:#101827 !important;color:#e2e8f0 !important;padding:12px 15px !important;border:0 !important;text-align:left;vertical-align:top;">To be selected after hardware assessment</td>
    </tr>
  </tbody>
</table>
</div>

*This inventory will be replaced with verified component names, specifications, and photos as the rebuild progresses.*

## Build Milestones

<div class="a1-projects a1-milestones">
  <div class="a1-milestone"><span>01</span><div><strong>Hardware assessment</strong><small>Photograph the system, identify parts, and make a reusable / replace list</small></div><em>Next</em></div>
  <div class="a1-milestone"><span>02</span><div><strong>Rebuild and validation</strong><small>Install required hardware and confirm that the system powers on reliably</small></div><em>Planned</em></div>
  <div class="a1-milestone"><span>03</span><div><strong>Linux installation</strong><small>Document installation, storage layout, networking, and essential commands</small></div><em>Planned</em></div>
  <div class="a1-milestone"><span>04</span><div><strong>Security baseline</strong><small>Document updates, user permissions, firewall settings, and recovery practices</small></div><em>Planned</em></div>
  <div class="a1-milestone"><span>05</span><div><strong>Lab exercises</strong><small>Publish controlled experiments with clearly stated scope and findings</small></div><em>Planned</em></div>
</div>

## Documentation Standards

When a milestone is completed, this page will record the **objective, hardware or tools used, steps taken, screenshots or command output, results, problems encountered, and lessons learned**. Any configurations or scripts suitable for sharing will be linked from the project.

Security testing will remain confined to systems owned by or explicitly authorized for the lab. Unnecessary exposure of test services to the public internet will be avoided.

## Project Log

**November 20, 2026:** Portfolio project log opened. Hardware assessment and build documentation are the next steps. No completed rebuild or lab results are claimed.

---

[Back to Projects](/projects/)

**A1Gh0st**  
*Learning. Practicing. Documenting.*
