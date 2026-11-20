---
layout: default
title: Kali VirtualBox Lab - Setup and Terminal Basics | A1Gh0st
permalink: /projects/kali-virtualbox-lab/2026-11-20/
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
  <p class="a1-breadcrumb"><a href="/projects/">Projects</a> / <a href="/projects/kali-virtualbox-lab/">Kali VirtualBox Lab</a> / November 20, 2026</p>
  <div class="a1-lab-header">
    <p class="a1-kicker">PROJECT 002 / DATED THREAD 001 / NOVEMBER 20, 2026</p>
    <h1>Kali Setup &amp; Terminal Basics</h1>
    <p class="a1-lead">Documenting the initial Kali Linux virtual machine and the first Linux terminal navigation lesson.</p>
    <span class="a1-status" style="background:#143a38;color:#86f1d4;border-color:#297e79;">Setup confirmed</span>
  </div>
</div>

## Summary

As of **November 20, 2026**, Oracle VirtualBox was installed, Kali Linux had been set up as a guest virtual machine, and the system successfully booted into its graphical desktop. The date on this entry is the date the setup was documented, not a claim that installation happened on that exact day.

The environment supports the hands-on portion of the **Complete Ethical Hacking Bootcamp** and provides a starting point for Linux administration, networking, and authorized security training.

**Udemy course progress (November 20, 2026):** Currently studying **Section 3 of 25**. Sections 1 and 2 were reported complete. Section 3 is **in progress**, not completed. This course-level status is separate from the completed terminal-navigation lesson documented below.

## What Has Been Verified

- **Oracle VirtualBox installed:** A local virtual machine platform is available.
- **Kali Linux installed:** The Kali guest operating system runs inside VirtualBox.
- **Graphical desktop accessible:** A user-provided screenshot confirms a successful desktop boot.

The screenshot was shared for project documentation but has not been published to the repository. No personal host information or private network details are included here.

## What Remains Unverified

The current record does **not** establish the Kali version, virtual hardware allocation, network adapter mode, internet access, package updates, snapshots, or success with security tools. Those topics can be documented in future dated threads after testing.

## Udemy Lesson: Navigating the Linux Filesystem

**Course:** Complete Ethical Hacking Bootcamp (Udemy)  
**Section:** Hacking Lab  
**Lesson status:** Completed November 20, 2026  
**Hands-on verification:** Individual commands have not yet been independently verified in the project record.

### Lesson Objective

Learn to navigate the Kali Linux filesystem through the **terminal** instead of relying on the graphical file manager. The terminal accepts commands for moving between directories, inspecting files, launching programs, and administering the system.

### Main Concepts

- **Working directory:** The folder in which the terminal session is currently operating. Opening a terminal inside a particular folder usually starts the session there.
- **Home directory (`~`):** A shortcut representing the current user's home folder, commonly `/home/<username>`.
- **Root directory (`/`):** The top of the Linux filesystem tree; it is not the same thing as the home directory or the root user account.
- **Relative and absolute paths:** `cd Documents` moves relative to the current directory, while `cd /etc` moves to an explicitly named location.
- **Files versus directories:** `cd` is for entering directories, not regular files. `ls` displays directory entries; colors may vary depending on the terminal configuration and file type.

### Commands Covered

| Command | What it does |
|:--|:--|
| `pwd` | Prints the current working directory |
| `ls` | Lists visible entries in the current directory |
| `cd Documents` | Changes into a `Documents` folder relative to the current directory |
| `cd ..` | Moves up one directory level |
| `cd` | Returns to the current user's home directory |
| `cd /` | Moves directly to the filesystem root |
| `cd /etc` | Moves directly into the system's `/etc` directory |
| `cd ~/Desktop` | Moves directly to the current user's Desktop folder if it exists |

**Important distinction:** At `/`, `cd ..` stays at `/` because there is no parent directory. By contrast, running `cd` with no arguments returns to the user's home directory. Linux paths are usually case-sensitive, so `Desktop` and `desktop` may not refer to the same directory.

### Walkthrough Example

This is an **illustrative practice sequence based on the lesson**, not recorded output from the A1Gh0st VM:

```bash
pwd
ls
cd /etc
pwd
cd ..
pwd
cd ~/Desktop
pwd
ls
```

The lesson also challenged students to travel from `/etc` back to the Desktop using terminal navigation alone. The instructor demonstrated a step-by-step route through `/`, `/home`, and the example account's home directory. A direct alternative is `cd ~/Desktop` when that folder exists.

### Key Takeaway

**The terminal makes Linux navigation reproducible and precise.** Understanding `pwd`, `ls`, `cd`, and how paths are organized is foundational for working with Kali tools, running commands in the correct location, and eventually writing scripts.

### Evidence and Follow-Up

- **Learning evidence:** Course lesson completed and transcript reviewed.
- **Practical evidence:** No screenshots or terminal output from this specific exercise have been submitted.
- **Next practice:** In the Kali VM, demonstrate navigation from `/etc` to the Desktop, check each location with `pwd`, and record the actual result without publishing personal usernames or network information.

## Reflection

Getting Kali Linux running inside VirtualBox establishes the foundation for an isolated training environment. The terminal navigation lesson provides a starting point for exploring the filesystem without the graphical file manager. Next steps are to verify commands in the VM and record a reproducible configuration.

---

[Back to the Kali Linux VirtualBox Lab](/projects/kali-virtualbox-lab/)

**A1Gh0st**  
*Learning. Practicing. Documenting.*
