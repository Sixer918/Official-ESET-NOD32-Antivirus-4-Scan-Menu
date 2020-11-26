# OFFICIAL ESET NOD32 Antivirus 4 Scan Menu for Linux KDE5
OFFICIAL - ESET Nod32 Linux Antivirus 4 Context Menu fix for Dolphin on KDE 5

---

## Description and Purpose

I was looking for a good AV for my Kubuntu distro where I fiddle around with multiple malware/payloads and HackTheBox labs. Finally found ESET which meets my exact needs :v: , sadly with KDE5 it seems that the integration is not working :rage1:
After some search I found https://www.opendesktop.org/p/1290369/ but it seems that is no longer updated, since location for ESET binaries have changed :finnadie: After fixing the issue myself and reporting it to the author (INTIKA), I've found that ESET itself has the integration for KDE3/4 but not 5 and the issue gets resolved by referencing those files to the correct folder location :feelsgood:

---

## Requirements are the following:

* ESET NOD32 ANTIVIRUS FOR LINUX DESKTOP 4
            
---
## Installation Procedure:

 1. Clone repo to your folder `git clone https://github.com/kiraitachi/Official-ESET-NOD32-Antivirus-4-Scan-Menu.git`
 2. Move to **Context Menu Files** folder
 3. Copy .desktop files depending on your KDE 5 platform to **/home/~~YOURUSER~~/.local/share/kservices5/ServiceMenus/**
 
## NOTE
I suggest only moving **eset_nod32_antivirus_options_no_scan_kde** since others will only scan but not clean. Choose whatever you need.
