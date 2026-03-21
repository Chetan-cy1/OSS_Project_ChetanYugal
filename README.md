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
- Made by Linus Torvalds in 2005

I chose Git because I already use it daily and wanted to understand
it better — not just the commands but where it came from and why
it works the way it does.

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

First make them executable:
```bash
chmod +x SystemIdentityReport.sh
chmod +x FOSSPackageInspector.sh
chmod +x PermissionAuditor.sh
chmod +x LogFile.sh
chmod +x Manifesto.sh
```

**Script 1**
```bash
./SystemIdentityReport.sh
```
Shows a welcome screen with your OS, kernel, username, uptime and
Git license info.

**Script 2**
```bash
./FOSSPackageInspector.sh
./FOSSPackageInspector.sh git
```
Pass any package name or leave blank — defaults to git.
Shows if it's installed, version, location, and a philosophy note.

**Script 3**
```bash
./PermissionAuditor.sh
```
Goes through directories like /etc, /var/log, /usr/bin and shows
who owns them and how big they are. Also checks for .gitconfig.

**Script 4**
```bash
./LogFile.sh
./LogFile.sh /var/log/system.log error
```
Reads a log file line by line and counts keyword matches.
Shows the last 5 lines that matched.

**Script 5**
```bash
./Manifesto.sh
```
Asks you 3 questions interactively and saves your personal open
source manifesto to a .txt file.

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
