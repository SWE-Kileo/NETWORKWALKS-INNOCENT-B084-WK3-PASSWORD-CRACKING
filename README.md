# Week 3: Password Cracking (John the Ripper & Networkwalks Tools)

**Networkwalks Cybersecurity Internship, Batch B084**  
**Author:** Innocent Kileo
## Overview

Project required to cracks the password of a locked PDF file using two different methods, John The Ripper and the Networkwalks tools.

## Modules Completed

| Module  | Tool                                                                 | Result              |
|---------|----------------------------------------------------------------------|---------------------|
| W3-PM1  | John the Ripper + Johnny (GUI), with `pdf2john.pl` to extract the hash | Password: `good-luck` |
| W3-PM2  | Networkwalks Hash Calculator + Password Cracker (browser-based, no install) | Password: `password1` |
| W3-PM1  | Networkwalks Hash Calculator + Password Cracker (browser-based, no install) | Password: `good-luck` |
## Key Finding

Both methods extracted different hash from different PDF, and both cracked it to the password, `good-luck` — and `password1` — confirming the extraction and cracking process is correct either way.  

The passwords was weak enough to be found almost instantly in a small built-in wordlist, which is the core lesson: **short, common, dictionary-style passwords offer almost no real protection**.

## Evidence

- Hash extracted with `pdf2john`
- Hash loaded in Johnny
- Cracked in Johnny
- ![Screenshot 202](screenshots/Screenshot%20(202).png)
  
- Flag captured
- Hash Calculator
- ![Screenshot 203](screenshots/Screenshot%20(203).png)
  
- Password Cracker result
  ![Screenshot 204](screenshots/Screenshot%20(204).png)
  
## Ethical Use

This file was provided for the course's own practice lab.  

**Only crack passwords on files and systems you own or have written permission to test.**
