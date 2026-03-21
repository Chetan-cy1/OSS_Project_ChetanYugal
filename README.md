# OSS Capstone Project — The Open Source Audit

**Name:** Chetan Yugal  
**Reg No:** 24BSA10093  
**Slot:** F11  
**Course:** Open Source Software  
**College:** VIT Bhopal University  

---

## Software I Chose

**Git**

- Category: Version Control  
- License: GPL v2  
- Developed by Linus Torvalds in 2005  

I chose Git mainly because I already use it in my daily work.  
But honestly, before this project I was just using commands without
really knowing what’s happening behind the scenes.

So I thought this is a good chance to understand it better — how it
actually works, why it was created, and why it became so important
in open source.

---

## What's in This Repo

| File | What it does |
|------|-------------|
| `SystemIdentityReport.sh` | Shows system info like kernel, user, uptime |
| `FOSSPackageInspector.sh` | Checks if a package is installed and shows details |
| `PermissionAuditor.sh` | Shows permissions and size of key directories |
| `LogFile.sh` | Counts how many times a keyword appears in a log file |
| `Manifesto.sh` | Asks 3 questions and generates your open source statement |

---

## How to Run the Scripts

First, make all scripts executable:

```bash
chmod +x SystemIdentityReport.sh
chmod +x FOSSPackageInspector.sh
chmod +x PermissionAuditor.sh
chmod +x LogFile.sh
chmod +x Manifesto.sh



**Script 1**
```bash
./SystemIdentityReport.sh
```
This shows a kind of welcome screen with system details like OS,
kernel version, username, uptime, and some Git-related info.

**Script 2**
```bash
./FOSSPackageInspector.sh
./FOSSPackageInspector.sh git
```
You can pass any package name or leave it blank (it takes git by default).
It checks if the package is installed, shows version and location,
and also prints a small open source note.

**Script 3**
```bash
./PermissionAuditor.sh
```
This script checks important system directories like /etc, /var/log,
/usr/bin and shows:
	•	who owns them
	•	their permissions
	•	their size

It also checks if .gitconfig exists in your system.

**Script 4**
```bash
./LogFile.sh
./LogFile.sh /var/log/system.log error
```
Reads a log file line by line and counts how many times a keyword appears.
Also prints the last few matching lines so you can quickly see the result.

**Script 5**
```bash
./Manifesto.sh
```
This one is interactive.
It simply asks 3 simple questions and then generates your personal open
source manifesto in a .txt file.

---

## Requirements

- macOS Terminal or any Linux system
- Git installed — `brew install git` on Mac
- Bash shell (comes pre-installed)

---

## References

- gnu.org/philosophy/free-sw.html
- git-scm.com/book
- opensource.org/osd
- catb.org/~esr/writings/cathedral-bazaar
- survey.stackoverflow.co/2023
- spdx.org/licenses/GPL-2.0-only.html
- github.com/git/git
