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

## Reflection

Getting Kali Linux running inside VirtualBox establishes the foundation for an isolated training environment. The terminal-navigation and file-management lessons introduce how to move through the filesystem, create or edit files, organize directories, and run a simple Python script. The next step is to verify these commands directly in the VM and document actual results, including safe handling of commands that delete files.

---

[Back to the Kali Linux VirtualBox Lab](/projects/kali-virtualbox-lab/)

**A1Gh0st**  
*Learning. Practicing. Documenting.*
