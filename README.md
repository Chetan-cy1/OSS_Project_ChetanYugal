# OSS_Project_ChetanYugal
A Capstone Project For Open Source Software_VITyarthi
# The Open Source Audit — Git
**Course:** Open Source Software (OSS NGMC)
**Student:** Chetan Yugal
**Registration Number:** 24BSA10093
**Slot:** F11
**Institution:** VIT Bhopal University

---

## Chosen Software
**Git** — Distributed Version Control System
**License:** GNU General Public License v2 (GPL v2)
**Created:** 2005 by Linus Torvalds

---

## Repository Contents

| File | Description |
|------|-------------|
| `SystemIdentityReport.sh` | Script 1 — Displays live system info as a welcome screen |
| `FOSSPackageInspector.sh` | Script 2 — Checks if a FOSS package is installed and prints a philosophy note |
| `PermissionAuditor.sh` | Script 3 — Audits key system directories for permissions and disk usage |
| `LogFile.sh` | Script 4 — Reads a log file line by line and counts keyword matches |
| `Manifesto.sh` | Script 5 — Interactively generates a personal open source manifesto |
| `README.md` | This file |

---

## How to Run Each Script

### Prerequisites
- macOS with Terminal or any Linux system
- Git installed (`brew install git` on macOS)
- Bash shell

### Setup — make all scripts executable
```bash
chmod +x SystemIdentityReport.sh
chmod +x FOSSPackageInspector.sh
chmod +x PermissionAuditor.sh
chmod +x LogFile.sh
chmod +x Manifesto.sh
```

### Script 1 — System Identity Report
```bash
./SystemIdentityReport.sh
```
Displays a formatted welcome screen showing OS, kernel version,
hostname, user, home directory, uptime, date/time, and license info.

### Script 2 — FOSS Package Inspector
```bash
./FOSSPackageInspector.sh
# or pass a package name:
./FOSSPackageInspector.sh git
```
Checks if the given package is installed, shows version and
location, and prints an open source philosophy note.

### Script 3 — Disk and Permission Auditor
```bash
./PermissionAuditor.sh
```
Loops through key system directories and reports permissions,
ownership, and disk usage. Also checks for Git global config.

### Script 4 — Log File Analyzer
```bash
./LogFile.sh
# or pass a custom log file and keyword:
./LogFile.sh /var/log/system.log error
```
Reads a log file line by line, counts how many lines contain
the keyword, and displays the last 5 matching lines.

### Script 5 — Open Source Manifesto Generator
```bash
./Manifesto.sh
```
Asks three interactive questions and generates a personalised
open source philosophy statement saved to a .txt file.

---

## Dependencies

| Tool | Purpose | Install |
|------|---------|---------|
| `bash` | Shell interpreter | Pre-installed on macOS/Linux |
| `git` | Chosen software | `brew install git` |
| `brew` | Package manager (macOS) | brew.sh |
| `awk` | Text processing in scripts | Pre-installed |
| `grep` | Pattern matching in scripts | Pre-installed |

---

## Project Report
The full project report PDF is submitted separately on the
VITyarthi portal as per submission requirements.

---

## References
- GNU Project — Free Software Definition: gnu.org/philosophy/free-sw.html
- Pro Git Book: git-scm.com/book
- Open Source Initiative: opensource.org/osd
- The Cathedral and the Bazaar: catb.org/~esr/writings/cathedral-bazaar
- Stack Overflow Developer Survey 2023: survey.stackoverflow.co/2023
```

---

## Step 4 — Commit the README

Scroll down → commit message:
`Add README with script documentation and run instructions`
→ Click **Commit changes**

---

## Step 5 — Get Your Submission Link

Your repo URL will be:
```
https://github.com/YOURUSERNAME/oss-audit-24BSA10093
