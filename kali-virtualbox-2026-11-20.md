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

**Udemy course progress (November 20, 2026):** **Section 3 of 25: Linux Operating System — Complete (5/5 items, 37 minutes of listed course content).** Sections 1 and 2 were also reported complete. That makes **3 of 25 course sections completed**; this is a section count, not an estimate of total course runtime completed. The screenshot establishes course completion status, while independent terminal practice is documented separately.

## What Has Been Verified

- **Oracle VirtualBox installed:** A local virtual machine platform is available.
- **Kali Linux installed:** The Kali guest operating system runs inside VirtualBox.
- **Graphical desktop accessible:** A user-provided screenshot confirms a successful desktop boot.

The screenshot was shared for project documentation but has not been published to the repository. No personal host information or private network details are included here.

## What Remains Unverified

The current record does **not** establish the Kali version, virtual hardware allocation, network adapter mode, internet access, package updates, snapshots, or success with security tools. Those topics can be documented in future dated threads after testing.

## Section 3 Completion Record

**Section:** Linux Operating System  
**Udemy completion evidence:** Screenshot showing **5/5 items** completed, with **37 minutes** listed for the section.  
**Recorded status:** Complete.

The visible lesson titles marked completed in the screenshot are:

- **20. Navigating Through Linux System** (11 minutes)
- **21. Creating Files & Managing Directories** (13 minutes)
- **22. Network Commands & Sudo Privileges In Kali** (11 minutes)

The screenshot displays three titled lessons and a total of five completed section items; the remaining two items are not identifiable from this image. The transcript supplied for **Navigating Through Linux System** supports the command explanations below. Detailed transcripts or independently captured practical results have not yet been supplied for the other two named lessons, so this entry does not invent their instructional content or claim hands-on verification.

## Udemy Lesson: Navigating the Linux Filesystem

**Course:** Complete Ethical Hacking Bootcamp (Udemy)  
**Section:** 3 of 25 — Linux Operating System  
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

<div class="a1-command-grid" style="overflow-x:auto;max-width:100%;border:1px solid #36546a;border-radius:10px;margin:1rem 0 1.5rem;background-color:#101827 !important;">
  <div role="table" aria-label="Linux terminal commands covered in the lesson" style="width:100%;min-width:480px;background-color:#101827 !important;color:#e2e8f0 !important;">
    <div role="row" style="display:grid;grid-template-columns:minmax(150px,30%) minmax(0,1fr);width:100%;background-color:#173047 !important;border-bottom:1px solid #36546a;">
      <div role="columnheader" style="padding:12px 15px;border-right:1px solid #36546a;background-color:#173047 !important;color:#65f0ff !important;font-weight:700;">Command</div>
      <div role="columnheader" style="padding:12px 15px;background-color:#173047 !important;color:#65f0ff !important;font-weight:700;">What it does</div>
    </div>
    <div role="row" style="display:grid;grid-template-columns:minmax(150px,30%) minmax(0,1fr);width:100%;background-color:#101827 !important;border-bottom:1px solid #36546a;">
      <div role="cell" style="padding:11px 15px;border-right:1px solid #36546a;background-color:transparent !important;color:#60e8f5 !important;font-family:Consolas,Monaco,monospace;font-size:.91rem;overflow-wrap:anywhere;">pwd</div>
      <div role="cell" style="padding:11px 15px;background-color:transparent !important;color:#e1edf6 !important;line-height:1.55;">Prints the current working directory</div>
    </div>
    <div role="row" style="display:grid;grid-template-columns:minmax(150px,30%) minmax(0,1fr);width:100%;background-color:#142236 !important;border-bottom:1px solid #36546a;">
      <div role="cell" style="padding:11px 15px;border-right:1px solid #36546a;background-color:transparent !important;color:#60e8f5 !important;font-family:Consolas,Monaco,monospace;font-size:.91rem;overflow-wrap:anywhere;">ls</div>
      <div role="cell" style="padding:11px 15px;background-color:transparent !important;color:#e1edf6 !important;line-height:1.55;">Lists visible entries in the current directory</div>
    </div>
    <div role="row" style="display:grid;grid-template-columns:minmax(150px,30%) minmax(0,1fr);width:100%;background-color:#101827 !important;border-bottom:1px solid #36546a;">
      <div role="cell" style="padding:11px 15px;border-right:1px solid #36546a;background-color:transparent !important;color:#60e8f5 !important;font-family:Consolas,Monaco,monospace;font-size:.91rem;overflow-wrap:anywhere;">cd Documents</div>
      <div role="cell" style="padding:11px 15px;background-color:transparent !important;color:#e1edf6 !important;line-height:1.55;">Changes into a Documents folder relative to the current directory</div>
    </div>
    <div role="row" style="display:grid;grid-template-columns:minmax(150px,30%) minmax(0,1fr);width:100%;background-color:#142236 !important;border-bottom:1px solid #36546a;">
      <div role="cell" style="padding:11px 15px;border-right:1px solid #36546a;background-color:transparent !important;color:#60e8f5 !important;font-family:Consolas,Monaco,monospace;font-size:.91rem;overflow-wrap:anywhere;">cd ..</div>
      <div role="cell" style="padding:11px 15px;background-color:transparent !important;color:#e1edf6 !important;line-height:1.55;">Moves up one directory level</div>
    </div>
    <div role="row" style="display:grid;grid-template-columns:minmax(150px,30%) minmax(0,1fr);width:100%;background-color:#101827 !important;border-bottom:1px solid #36546a;">
      <div role="cell" style="padding:11px 15px;border-right:1px solid #36546a;background-color:transparent !important;color:#60e8f5 !important;font-family:Consolas,Monaco,monospace;font-size:.91rem;overflow-wrap:anywhere;">cd</div>
      <div role="cell" style="padding:11px 15px;background-color:transparent !important;color:#e1edf6 !important;line-height:1.55;">Returns to the current user's home directory</div>
    </div>
    <div role="row" style="display:grid;grid-template-columns:minmax(150px,30%) minmax(0,1fr);width:100%;background-color:#142236 !important;border-bottom:1px solid #36546a;">
      <div role="cell" style="padding:11px 15px;border-right:1px solid #36546a;background-color:transparent !important;color:#60e8f5 !important;font-family:Consolas,Monaco,monospace;font-size:.91rem;overflow-wrap:anywhere;">cd /</div>
      <div role="cell" style="padding:11px 15px;background-color:transparent !important;color:#e1edf6 !important;line-height:1.55;">Moves directly to the filesystem root</div>
    </div>
    <div role="row" style="display:grid;grid-template-columns:minmax(150px,30%) minmax(0,1fr);width:100%;background-color:#101827 !important;border-bottom:1px solid #36546a;">
      <div role="cell" style="padding:11px 15px;border-right:1px solid #36546a;background-color:transparent !important;color:#60e8f5 !important;font-family:Consolas,Monaco,monospace;font-size:.91rem;overflow-wrap:anywhere;">cd /etc</div>
      <div role="cell" style="padding:11px 15px;background-color:transparent !important;color:#e1edf6 !important;line-height:1.55;">Moves directly into the system's /etc directory</div>
    </div>
    <div role="row" style="display:grid;grid-template-columns:minmax(150px,30%) minmax(0,1fr);width:100%;background-color:#142236 !important;">
      <div role="cell" style="padding:11px 15px;border-right:1px solid #36546a;background-color:transparent !important;color:#60e8f5 !important;font-family:Consolas,Monaco,monospace;font-size:.91rem;overflow-wrap:anywhere;">cd ~/Desktop</div>
      <div role="cell" style="padding:11px 15px;background-color:transparent !important;color:#e1edf6 !important;line-height:1.55;">Moves directly to the current user's Desktop folder if it exists</div>
    </div>
  </div>
</div>

**Important distinction:** At `/`, `cd ..` stays at `/` because there is no parent directory. By contrast, running `cd` with no arguments returns to the user's home directory. Linux paths are usually case-sensitive, so `Desktop` and `desktop` may not refer to the same directory.

### Walkthrough Example

This is an **illustrative practice sequence based on the lesson**, not recorded output from the A1Gh0st VM:

<div class="a1-terminal-demo" style="margin:1rem 0 1.5rem;background-color:#0d1828 !important;border:1px solid #366178;border-radius:10px;overflow:hidden;box-shadow:0 4px 18px rgba(0,0,0,.13);">
  <div style="background-color:#173047 !important;color:#83ebf5 !important;padding:10px 16px;border-bottom:1px solid #366178;font-size:.75rem;letter-spacing:.09em;font-weight:700;">TERMINAL / ILLUSTRATIVE PRACTICE</div>
  <pre style="display:block;max-width:100%;box-sizing:border-box;overflow-x:auto;background-color:#0d1828 !important;color:#d7f7ff !important;border:0 !important;box-shadow:none !important;margin:0 !important;padding:18px 20px !important;font:500 .91rem/1.7 Consolas,Monaco,monospace !important;white-space:pre !important;"><code style="background-color:transparent !important;color:#d7f7ff !important;border:0 !important;padding:0 !important;font:inherit !important;">pwd
ls
cd /etc
pwd
cd ..
pwd
cd ~/Desktop
pwd
ls</code></pre>
</div>

The lesson also challenged students to travel from `/etc` back to the Desktop using terminal navigation alone. The instructor demonstrated a step-by-step route through `/`, `/home`, and the example account's home directory. A direct alternative is `cd ~/Desktop` when that folder exists.

### Key Takeaway

**The terminal makes Linux navigation reproducible and precise.** Understanding `pwd`, `ls`, `cd`, and how paths are organized is foundational for working with Kali tools, running commands in the correct location, and eventually writing scripts.

### Evidence and Follow-Up

- **Learning evidence:** Course lesson completed and transcript reviewed.
- **Practical evidence:** No screenshots or terminal output from this specific exercise have been submitted.
- **Next practice:** In the Kali VM, demonstrate navigation from `/etc` to the Desktop, check each location with `pwd`, and record the actual result without publishing personal usernames or network information.

## Udemy Lesson: Creating Files & Managing Directories

**Course:** Complete Ethical Hacking Bootcamp (Udemy)  
**Section:** 3 of 25 — Linux Operating System  
**Lesson:** 21 — Creating Files &amp; Managing Directories (13 minutes)  
**Lesson status:** Completed as shown in the Section 3 course screenshot  
**Documentation source:** Instructor transcript supplied for this lesson; no individual command output from the A1Gh0st Kali VM has been submitted.

### Lesson Objective

Understand how to create, inspect, edit, copy, move, and remove files and directories using the Kali Linux terminal. The instructor builds on earlier navigation commands (`pwd`, `cd`, and `ls`) by showing how filesystem content is managed directly from the shell.

### Main Concepts

- **Creating and inspecting text files:** `touch` creates an empty file, `cat` displays its contents, and `echo` combined with `>` writes text to a file. The `>` operator replaces existing file contents, so its destination matters.
- **Editing with Nano:** `nano` is a terminal-based text editor. The instructor creates a text file and saves it using **Ctrl+O**, confirms the filename with **Enter**, then exits with **Ctrl+X**.
- **Creating and executing a Python script:** The lesson uses `nano` to save `file3.py` with a simple `print("Hello World")` statement, then demonstrates executing it with `python3 file3.py`. This is a basic example of editing and running source code from the terminal.
- **Creating directories:** `mkdir` creates a folder that can hold files and other subdirectories.
- **Moving versus copying:** `mv` transfers a file to another location, while `cp` preserves the original and creates another copy.
- **Deleting safely:** `rm` removes a file; recursive removal with `rm -r` can delete a folder and everything inside it. The instructor accidentally removed more than intended during the demonstration, reinforcing the need to inspect the current directory and target before any destructive command.

### Commands Covered

<div class="a1-command-grid" style="max-width:100%;overflow-x:auto;border:1px solid #36546a;border-radius:10px;margin:1rem 0 1.5rem;background-color:#101827 !important;">
  <div role="table" aria-label="File and directory management commands from the Udemy lesson" style="width:100%;min-width:510px;background-color:#101827 !important;color:#e2e8f0 !important;">
    <div role="row" style="display:grid;grid-template-columns:minmax(190px,38%) minmax(0,1fr);background-color:#173047 !important;border-bottom:1px solid #36546a;">
      <div role="columnheader" style="padding:12px 15px;border-right:1px solid #36546a;color:#65f0ff !important;background-color:#173047 !important;font-weight:700;">Command</div>
      <div role="columnheader" style="padding:12px 15px;color:#65f0ff !important;background-color:#173047 !important;font-weight:700;">Purpose</div>
    </div>
    <div role="row" style="display:grid;grid-template-columns:minmax(190px,38%) minmax(0,1fr);background-color:#101827 !important;border-bottom:1px solid #36546a;">
      <div role="cell" style="min-width:0;overflow-wrap:anywhere;padding:11px 15px;border-right:1px solid #36546a;color:#60e8f5 !important;background-color:transparent !important;font:500 .86rem/1.55 Consolas,Monaco,monospace;">touch file1</div>
      <div role="cell" style="min-width:0;padding:11px 15px;color:#e1edf6 !important;background-color:transparent !important;line-height:1.55;">Creates an empty file if it does not exist</div>
    </div>
    <div role="row" style="display:grid;grid-template-columns:minmax(190px,38%) minmax(0,1fr);background-color:#142236 !important;border-bottom:1px solid #36546a;">
      <div role="cell" style="min-width:0;overflow-wrap:anywhere;padding:11px 15px;border-right:1px solid #36546a;color:#60e8f5 !important;background-color:transparent !important;font:500 .86rem/1.55 Consolas,Monaco,monospace;">cat file1</div>
      <div role="cell" style="min-width:0;padding:11px 15px;color:#e1edf6 !important;background-color:transparent !important;line-height:1.55;">Displays the file's current contents</div>
    </div>
    <div role="row" style="display:grid;grid-template-columns:minmax(190px,38%) minmax(0,1fr);background-color:#101827 !important;border-bottom:1px solid #36546a;">
      <div role="cell" style="min-width:0;overflow-wrap:anywhere;padding:11px 15px;border-right:1px solid #36546a;color:#60e8f5 !important;background-color:transparent !important;font:500 .86rem/1.55 Consolas,Monaco,monospace;">echo "Today is a good day" &gt; file1</div>
      <div role="cell" style="min-width:0;padding:11px 15px;color:#e1edf6 !important;background-color:transparent !important;line-height:1.55;">Writes text into a file using output redirection</div>
    </div>
    <div role="row" style="display:grid;grid-template-columns:minmax(190px,38%) minmax(0,1fr);background-color:#142236 !important;border-bottom:1px solid #36546a;">
      <div role="cell" style="min-width:0;overflow-wrap:anywhere;padding:11px 15px;border-right:1px solid #36546a;color:#60e8f5 !important;background-color:transparent !important;font:500 .86rem/1.55 Consolas,Monaco,monospace;">nano file2</div>
      <div role="cell" style="min-width:0;padding:11px 15px;color:#e1edf6 !important;background-color:transparent !important;line-height:1.55;">Opens a terminal text editor for editing or creating a file</div>
    </div>
    <div role="row" style="display:grid;grid-template-columns:minmax(190px,38%) minmax(0,1fr);background-color:#101827 !important;border-bottom:1px solid #36546a;">
      <div role="cell" style="min-width:0;overflow-wrap:anywhere;padding:11px 15px;border-right:1px solid #36546a;color:#60e8f5 !important;background-color:transparent !important;font:500 .86rem/1.55 Consolas,Monaco,monospace;">python3 file3.py</div>
      <div role="cell" style="min-width:0;padding:11px 15px;color:#e1edf6 !important;background-color:transparent !important;line-height:1.55;">Runs the saved Python script with Python 3</div>
    </div>
    <div role="row" style="display:grid;grid-template-columns:minmax(190px,38%) minmax(0,1fr);background-color:#142236 !important;border-bottom:1px solid #36546a;">
      <div role="cell" style="min-width:0;overflow-wrap:anywhere;padding:11px 15px;border-right:1px solid #36546a;color:#60e8f5 !important;background-color:transparent !important;font:500 .86rem/1.55 Consolas,Monaco,monospace;">mkdir folder</div>
      <div role="cell" style="min-width:0;padding:11px 15px;color:#e1edf6 !important;background-color:transparent !important;line-height:1.55;">Creates a directory named folder</div>
    </div>
    <div role="row" style="display:grid;grid-template-columns:minmax(190px,38%) minmax(0,1fr);background-color:#101827 !important;border-bottom:1px solid #36546a;">
      <div role="cell" style="min-width:0;overflow-wrap:anywhere;padding:11px 15px;border-right:1px solid #36546a;color:#60e8f5 !important;background-color:transparent !important;font:500 .86rem/1.55 Consolas,Monaco,monospace;">mv file3.py folder/</div>
      <div role="cell" style="min-width:0;padding:11px 15px;color:#e1edf6 !important;background-color:transparent !important;line-height:1.55;">Moves the Python file into the folder directory</div>
    </div>
    <div role="row" style="display:grid;grid-template-columns:minmax(190px,38%) minmax(0,1fr);background-color:#142236 !important;border-bottom:1px solid #36546a;">
      <div role="cell" style="min-width:0;overflow-wrap:anywhere;padding:11px 15px;border-right:1px solid #36546a;color:#60e8f5 !important;background-color:transparent !important;font:500 .86rem/1.55 Consolas,Monaco,monospace;">cp file3.py file4.py</div>
      <div role="cell" style="min-width:0;padding:11px 15px;color:#e1edf6 !important;background-color:transparent !important;line-height:1.55;">Creates a copy of a file under a new name</div>
    </div>
    <div role="row" style="display:grid;grid-template-columns:minmax(190px,38%) minmax(0,1fr);background-color:#101827 !important;border-bottom:1px solid #36546a;">
      <div role="cell" style="min-width:0;overflow-wrap:anywhere;padding:11px 15px;border-right:1px solid #36546a;color:#60e8f5 !important;background-color:transparent !important;font:500 .86rem/1.55 Consolas,Monaco,monospace;">rm file4.py</div>
      <div role="cell" style="min-width:0;padding:11px 15px;color:#e1edf6 !important;background-color:transparent !important;line-height:1.55;">Deletes a file; not sent to a graphical trash bin</div>
    </div>
    <div role="row" style="display:grid;grid-template-columns:minmax(190px,38%) minmax(0,1fr);background-color:#142236 !important;">
      <div role="cell" style="min-width:0;overflow-wrap:anywhere;padding:11px 15px;border-right:1px solid #36546a;color:#60e8f5 !important;background-color:transparent !important;font:500 .86rem/1.55 Consolas,Monaco,monospace;">rm -r folder2</div>
      <div role="cell" style="min-width:0;padding:11px 15px;color:#e1edf6 !important;background-color:transparent !important;line-height:1.55;">Recursively removes a directory and its contents; use with extreme care</div>
    </div>
  </div>
</div>

### Terminal Walkthrough

The following sequence illustrates the **commands and workflow taught in the video**. It is **not** a record of commands personally executed in the A1Gh0st VM. It assumes the `~/Desktop` directory exists. After launching `nano file3.py`, the instructor enters `print("Hello World")`, saves using **Ctrl+O**, then exits using **Ctrl+X** before running the script.

<div class="a1-terminal-demo" style="margin:1rem 0 1.5rem;background-color:#0d1828 !important;border:1px solid #366178;border-radius:10px;overflow:hidden;">
  <div style="background-color:#173047 !important;color:#83ebf5 !important;padding:10px 16px;border-bottom:1px solid #366178;font-size:.75rem;letter-spacing:.09em;font-weight:700;">TERMINAL / EXAMPLE FROM COURSE CONCEPTS, NOT VERIFIED LAB OUTPUT</div>
  <pre style="display:block;box-sizing:border-box;max-width:100%;overflow-x:auto;background-color:#0d1828 !important;color:#d7f7ff !important;border:0 !important;box-shadow:none !important;margin:0 !important;padding:18px 20px !important;font:500 .91rem/1.7 Consolas,Monaco,monospace !important;white-space:pre !important;"><code style="background-color:transparent !important;color:#d7f7ff !important;border:0 !important;padding:0 !important;font:inherit !important;">cd ~/Desktop
touch file1
echo "Today is a good day" &gt; file1
cat file1
nano file2
nano file3.py
python3 file3.py
mkdir folder
mv file3.py folder/
cd folder
cp file3.py file4.py
ls</code></pre>
</div>

**Expected distinction:** `mv` removes the file from its original location by moving it, while `cp` leaves the source file in place. The example creates `file4.py` as a copy of `file3.py` after moving the original script into the folder.

### Deletion and Safety Notes

The lesson uses `rm` to delete a copied file and demonstrates recursive directory deletion. Unlike using a desktop file manager, ordinary shell deletion does not send files to a familiar Trash folder. A recursive deletion command aimed at the wrong path or combined with a wildcard can destroy important data.

**Recommended lab practice:** Before deleting anything, verify location with `pwd` and inspect the target with `ls`. No destructive deletion command is included in the illustrative walkthrough above.

### Instructor's Practice Challenge

Create a Python file named `file3.py` **inside a folder** and then copy it back to the Desktop using the commands covered. This was assigned in the lesson as practice. **Completion of the challenge has not yet been independently documented** for the A1Gh0st lab.

### Key Takeaway

The Linux terminal is not only for viewing folders. It can build and organize a working environment, edit source files, and execute programs. These file and directory operations are foundational for managing scripts, evidence, and other resources during authorized cybersecurity work.

### Evidence and Follow-Up

- **Learning evidence:** Section 3 completion screenshot and this lesson's provided transcript.
- **Practical evidence:** No separate terminal output or screenshot confirming this lesson's commands in the A1Gh0st VM.
- **Next step:** Repeat a safe file-management exercise, verify the results with `ls` and `cat`, and record the outcome in a dated thread.

## Udemy Lesson: Network Commands & Sudo Privileges in Kali

**Course:** Complete Ethical Hacking Bootcamp (Udemy)  
**Section:** 3 of 25 — Linux Operating System  
**Lesson:** 22 — Network Commands &amp; Sudo Privileges in Kali (11 minutes)  
**Lesson status:** Complete, based on the Section 3 completion screenshot  
**Documentation source:** User-supplied instructor transcript; no output from running these commands in the A1Gh0st Kali VM has been provided.

### Lesson Objective

Learn how to recognize local network interfaces, interpret IP and MAC addresses, understand Linux administrator permissions, and correctly copy files using explicit paths.

### Concepts Covered

- **Copying to the right location:** The lesson resolves the previous exercise. If `Desktop` is not an existing directory relative to the working folder, a command such as `cp file3.py Desktop` can create a *file* named `Desktop` rather than copy into the user's desktop folder. Specify the actual destination, such as `cp file3.py "$HOME/Desktop/copy.py"`, after checking that the folder exists. Linux paths are case-sensitive.
- **Network interfaces:** The instructor uses `ifconfig` to display interfaces, local IP addresses, and hardware addresses. An interface could have a name like `eth0` or `enp0s3` (depending on the VM and OS). The loopback interface `lo` usually includes the IPv4 address `127.0.0.1`.
- **Private versus public IP addresses:** An address such as `192.168.1.12` is a private IPv4 address used within networks. Such addresses can be reused by separate private networks; internet-facing connections may use a different public address and network address translation.
- **MAC addresses:** A MAC address identifies a network interface at the link layer, primarily on the local network segment. MAC addresses can be randomized, changed, or duplicated in virtual environments, so treating every MAC as a permanent worldwide-unique device identity is inaccurate.
- **Privilege elevation:** `sudo` permits authorized users to run particular commands with elevated privileges, typically as root. A root shell can be started with `sudo -i` when genuinely necessary and closed with `exit`. Working as an ordinary user by default limits the damage caused by mistakes.
- **File ownership and permissions:** Root-owned or otherwise restricted files may not be writable by the normal user. Use `ls -l` to inspect ownership and permissions before deciding which administrative action is appropriate.

### Commands Covered

<div class="a1-command-grid" style="overflow-x:auto;max-width:100%;margin:1rem 0 1.5rem;border:1px solid #36546a;border-radius:10px;background-color:#101827 !important;">
  <div role="table" aria-label="Linux networking and administrator command reference" style="min-width:560px;width:100%;background-color:#101827 !important;color:#e2e8f0 !important;">
    <div role="row" style="display:grid;grid-template-columns:minmax(195px,38%) minmax(0,1fr);background-color:#173047 !important;border-bottom:1px solid #36546a;">
      <div role="columnheader" style="padding:12px 15px;border-right:1px solid #36546a;color:#65f0ff !important;background-color:#173047 !important;font-weight:700;">Command</div>
      <div role="columnheader" style="padding:12px 15px;color:#65f0ff !important;background-color:#173047 !important;font-weight:700;">What it does</div>
    </div>
    <div role="row" style="display:grid;grid-template-columns:minmax(195px,38%) minmax(0,1fr);width:100%;background-color:#101827 !important;border-bottom:1px solid #36546a;">
      <div role="cell" style="padding:11px 15px;border-right:1px solid #36546a;min-width:0;overflow-wrap:anywhere;background-color:transparent !important;color:#60e8f5 !important;font:500 .86rem/1.55 Consolas,Monaco,monospace;">cp file3.py ~/Desktop/copy.py</div>
      <div role="cell" style="padding:11px 15px;min-width:0;background-color:transparent !important;color:#e1edf6 !important;line-height:1.55;">Copies a file to a specific destination path and filename, if that Desktop directory exists.</div>
    </div>
    <div role="row" style="display:grid;grid-template-columns:minmax(195px,38%) minmax(0,1fr);width:100%;background-color:#142236 !important;border-bottom:1px solid #36546a;">
      <div role="cell" style="padding:11px 15px;border-right:1px solid #36546a;min-width:0;overflow-wrap:anywhere;background-color:transparent !important;color:#60e8f5 !important;font:500 .86rem/1.55 Consolas,Monaco,monospace;">ifconfig</div>
      <div role="cell" style="padding:11px 15px;min-width:0;background-color:transparent !important;color:#e1edf6 !important;line-height:1.55;">Displays network interfaces and addressing information when net-tools is installed and available in PATH.</div>
    </div>
    <div role="row" style="display:grid;grid-template-columns:minmax(195px,38%) minmax(0,1fr);width:100%;background-color:#101827 !important;border-bottom:1px solid #36546a;">
      <div role="cell" style="padding:11px 15px;border-right:1px solid #36546a;min-width:0;overflow-wrap:anywhere;background-color:transparent !important;color:#60e8f5 !important;font:500 .86rem/1.55 Consolas,Monaco,monospace;">ip -brief address</div>
      <div role="cell" style="padding:11px 15px;min-width:0;background-color:transparent !important;color:#e1edf6 !important;line-height:1.55;">Modern alternative for reviewing local IP addresses assigned to interfaces.</div>
    </div>
    <div role="row" style="display:grid;grid-template-columns:minmax(195px,38%) minmax(0,1fr);width:100%;background-color:#142236 !important;border-bottom:1px solid #36546a;">
      <div role="cell" style="padding:11px 15px;border-right:1px solid #36546a;min-width:0;overflow-wrap:anywhere;background-color:transparent !important;color:#60e8f5 !important;font:500 .86rem/1.55 Consolas,Monaco,monospace;">ip link show</div>
      <div role="cell" style="padding:11px 15px;min-width:0;background-color:transparent !important;color:#e1edf6 !important;line-height:1.55;">Displays interfaces, link state, and hardware (MAC) addresses.</div>
    </div>
    <div role="row" style="display:grid;grid-template-columns:minmax(195px,38%) minmax(0,1fr);width:100%;background-color:#101827 !important;border-bottom:1px solid #36546a;">
      <div role="cell" style="padding:11px 15px;border-right:1px solid #36546a;min-width:0;overflow-wrap:anywhere;background-color:transparent !important;color:#60e8f5 !important;font:500 .86rem/1.55 Consolas,Monaco,monospace;">ip route</div>
      <div role="cell" style="padding:11px 15px;min-width:0;background-color:transparent !important;color:#e1edf6 !important;line-height:1.55;">Shows the routing table, including the default gateway if configured.</div>
    </div>
    <div role="row" style="display:grid;grid-template-columns:minmax(195px,38%) minmax(0,1fr);width:100%;background-color:#142236 !important;border-bottom:1px solid #36546a;">
      <div role="cell" style="padding:11px 15px;border-right:1px solid #36546a;min-width:0;overflow-wrap:anywhere;background-color:transparent !important;color:#60e8f5 !important;font:500 .86rem/1.55 Consolas,Monaco,monospace;">whoami</div>
      <div role="cell" style="padding:11px 15px;min-width:0;background-color:transparent !important;color:#e1edf6 !important;line-height:1.55;">Reports the effective username for the current shell.</div>
    </div>
    <div role="row" style="display:grid;grid-template-columns:minmax(195px,38%) minmax(0,1fr);width:100%;background-color:#101827 !important;border-bottom:1px solid #36546a;">
      <div role="cell" style="padding:11px 15px;border-right:1px solid #36546a;min-width:0;overflow-wrap:anywhere;background-color:transparent !important;color:#60e8f5 !important;font:500 .86rem/1.55 Consolas,Monaco,monospace;">sudo &lt;command&gt;</div>
      <div role="cell" style="padding:11px 15px;min-width:0;background-color:transparent !important;color:#e1edf6 !important;line-height:1.55;">Runs a specific permitted command with elevated privileges.</div>
    </div>
    <div role="row" style="display:grid;grid-template-columns:minmax(195px,38%) minmax(0,1fr);width:100%;background-color:#142236 !important;border-bottom:1px solid #36546a;">
      <div role="cell" style="padding:11px 15px;border-right:1px solid #36546a;min-width:0;overflow-wrap:anywhere;background-color:transparent !important;color:#60e8f5 !important;font:500 .86rem/1.55 Consolas,Monaco,monospace;">sudo -i</div>
      <div role="cell" style="padding:11px 15px;min-width:0;background-color:transparent !important;color:#e1edf6 !important;line-height:1.55;">Starts a root login shell for authorized administration; exit as soon as finished.</div>
    </div>
    <div role="row" style="display:grid;grid-template-columns:minmax(195px,38%) minmax(0,1fr);width:100%;background-color:#101827 !important;border-bottom:1px solid #36546a;">
      <div role="cell" style="padding:11px 15px;border-right:1px solid #36546a;min-width:0;overflow-wrap:anywhere;background-color:transparent !important;color:#60e8f5 !important;font:500 .86rem/1.55 Consolas,Monaco,monospace;">exit</div>
      <div role="cell" style="padding:11px 15px;min-width:0;background-color:transparent !important;color:#e1edf6 !important;line-height:1.55;">Leaves the current shell and returns to the prior shell or session.</div>
    </div>
    <div role="row" style="display:grid;grid-template-columns:minmax(195px,38%) minmax(0,1fr);width:100%;background-color:#142236 !important;">
      <div role="cell" style="padding:11px 15px;border-right:1px solid #36546a;min-width:0;overflow-wrap:anywhere;background-color:transparent !important;color:#60e8f5 !important;font:500 .86rem/1.55 Consolas,Monaco,monospace;">ls -l filename</div>
      <div role="cell" style="padding:11px 15px;min-width:0;background-color:transparent !important;color:#e1edf6 !important;line-height:1.55;">Shows file ownership and permissions for troubleshooting access.</div>
    </div>
  </div>
</div>

### Example: Copying a Script and Checking the Network

These examples summarize the demonstrated concepts and add current Kali-friendly alternatives. **They have not been independently executed or verified in this project's VM.** The copy example assumes `file3.py` exists in the current directory and a `~/Desktop` folder exists.

<div class="a1-terminal-demo" style="margin:1rem 0 1.5rem;background-color:#0d1828 !important;border:1px solid #366178;border-radius:10px;overflow:hidden;">
  <div style="background-color:#173047 !important;color:#83ebf5 !important;padding:10px 16px;border-bottom:1px solid #366178;font-size:.75rem;letter-spacing:.09em;font-weight:700;">TERMINAL / ILLUSTRATIVE PRACTICE — NOT VERIFIED LAB OUTPUT</div>
  <pre style="display:block;box-sizing:border-box;max-width:100%;overflow-x:auto;background-color:#0d1828 !important;color:#d7f7ff !important;border:0 !important;box-shadow:none !important;margin:0 !important;padding:18px 20px !important;font:500 .91rem/1.7 Consolas,Monaco,monospace !important;white-space:pre !important;"><code style="background-color:transparent !important;color:#d7f7ff !important;border:0 !important;padding:0 !important;font:inherit !important;"># If working inside the folder holding file3.py:
pwd
ls -ld "$HOME/Desktop"
cp file3.py "$HOME/Desktop/copy.py"
ls -l "$HOME/Desktop/copy.py"

# Read-only network and identity checks:
ip -brief address
ip link show
ip route
whoami</code></pre>
</div>

### Technical Corrections and Troubleshooting

**1. `ifconfig` is not inherently a root-only command.** Simply viewing interface configuration usually does not require `sudo`. If `ifconfig` returns *command not found*, the likely causes include the legacy `net-tools` package not being installed or the executable not being in the user's `PATH`. Using `sudo` can sometimes change the search path, but it does not solve a genuinely missing program. On modern Kali, `ip -brief address`, `ip link show`, and `ip route` are preferable for everyday network inspection.

**2. `sudo` is not the answer to every error.** *Command not found* and *permission denied* mean different things. Troubleshoot the error before escalating. A root shell is started with `sudo -i` (or another explicitly supported shell command), **not** by repeating `sudo sudo`.

**3. File editing depends on ownership and permissions.** Creating a *new* file using `sudo touch` commonly makes it root-owned; that is different from editing an existing file. Inspect permissions with `ls -l`. Use elevation only where required, and avoid casually producing root-owned files in the everyday working directory.

**4. Network identifiers are useful but not infallible.** The transcript's explanation of IP versus MAC addresses is a beginner-level analogy. IP addresses identify network-layer endpoints, while MAC addresses identify link-layer interfaces; both can change depending on the environment.

### Security Takeaway

**Understand the environment before changing it.** For effective troubleshooting and penetration-testing lab work, first identify the correct file paths, network interfaces, IP configuration, and current user privileges. Prefer read-only diagnostic commands, use administrative access sparingly, and avoid sharing real hostnames, private IP details, or hardware addresses in public screenshots when unnecessary.

### Evidence and Follow-Up

- **Learning evidence:** Section 3 completed on Udemy; this lesson's instructor transcript has been reviewed.
- **Hands-on evidence:** No output from the A1Gh0st VM confirming the lesson's network or permissions commands has been submitted.
- **Next validation:** Execute safe read-only checks in Kali, record sanitized output for `ip -brief address`, `ip route`, `whoami`, and `ls -l`, and confirm which network adapter VirtualBox is configured to use.

## Reflection

Getting Kali Linux running inside VirtualBox establishes the foundation for an isolated training environment. The three documented Linux Operating System lessons now cover terminal navigation, file and directory operations, and introductory network diagnostics and Linux privileges. The important next step is to verify commands directly in Kali, distinguish configuration problems from permissions errors, and document sanitized command output rather than relying only on course demonstrations.

---

[Back to the Kali Linux VirtualBox Lab](/projects/kali-virtualbox-lab/)

**A1Gh0st**  
*Learning. Practicing. Documenting.*
