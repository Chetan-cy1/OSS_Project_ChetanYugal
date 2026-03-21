OSS Capstone Project-- the Open Source Audit.

Name: Chetan Yugal  
Reg No: 24BSA10093  
Slot: F11  
Course: Open Source Software  
College: VIT Bhopal University.  

Software I Chose

Git

Category: Version Control  
License: GPL v2  
The developed kernel by Linus Torvalds in 2005.  

My primary choice of using Git was due to its usage in my work daily.  
Nevertheless, ID tells the truth, I was merely following the instructions before this project.
actually being acquainted with what is going on in the backgrounds.

and so I reckoned this would be a good opportunity of learning more about it--how it
why it actually works, why it came into existence and why it became this significant.
in open source.

What's in This Repo

  File   What it does  

  See SystemIdentityReport.sh Documentation.sh Website.  
  FOSSPackageInspector.sh - Realizes whether the package is in place and it displays its information.  
  PermissionAuditor.sh   Displays access and capacity of searchable directories.  
  LogFile.sh Systems the number of times a key-word is repeated in a log file.  
  Manifesto.sh   Answer 3 questions and create your open source statement.  

How to Run the Scripts

To begin with, be able to make all scripts executable:

SystemIdentityReport.sh chmod +x SystemIdentityReport.sh
FOSSPackageInspector.sh admin.sh chmod +x FOSSPackageInspector.sh.sh chmod +x FOSSPackageInspector.sh.sh admin.sh chmod +x FOSSPackageInspector.sh.sh.sh chmod +x FOSSPackageInspector.sh.sh.sh.sh.sh.sh.sh.sh.sh.sh.sh.sh.sh.sh.sh.sh.sh.sh.sh.sh.sh.sh.sh.sh.sh.sh.sh.sh.sh.sh.sh.sh.
PermissionAuditor.sh was given chmod +x.
chmod +x LogFile.sh
chmod +x Manifesto.sh

Script 1bash
./SystemIdentityReport.sh
This is a welcome screen with details of the system such as OS.
version of kernel, name, uptime, and a part of Git-related information.

Script 2bash
./FOSSPackageInspector.sh
./FOSSPackageInspector.sh git
Any package name can be passed or it can be left as a default (it puts git by default).
It determines whether the package has been installed or not, displaying the version and locality.
and also includes an open source note.

Script 3bash
./PermissionAuditor.sh
This script scans popular directories of the system such as; /etc, /var/log etc.
/usr/bin and shows:
		who owns them
		their permissions
	*	their size

It also verifies whether or not you have.gitconfig in your computer.

Script 4bash
./LogFile.sh
```./LogFile.sh /var/log/system.log error
|human|>Desmond is an independent automotive breaker manufacturer.<|human|>Desmond is a breaker tire manufacturer that is independent.
Reads log file one line at the time and counts the frequency of occurrence of a keyword.
and also writes the last few matching lines so you can very soon see the effect.

Script 5bash
./Manifesto.sh
`
This one is interactive.
It will just take 3 questions that are not complicated and then create your own open.
the manifesto of the source in a.txt file.

Requirements

Paint or any other Linux-written legacy system or any macOS Terminal.
------ git installed d – brew install git in Mac.
Bash shell belongs to the set of shells of shell installer

References

gnu.org/philosophy/free-sw.html
git-scm.com/book
opensource.org/osd
catb.org/~esr/writings/cathedral-bazaar
survey.stackoverflow.co/2023
spdx.org/licenses/GPL-2.0-only.html
github.com/git/git
