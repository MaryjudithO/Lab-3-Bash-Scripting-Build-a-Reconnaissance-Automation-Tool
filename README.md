# Lab 3: Bash Scripting - Build a Reconnaissance Tool

## Student Information
- Name: Maryjudith Chidinma Ogunaka
- Programme: ICDFA Trainee | Cohort 11
- Lab: Lab 3 - Bash Scripting
- Authorised Target: 10.15.203.91

## Project Description
For this lab I built a Bash script that automates three reconnaissance tools  WhatWeb, Nmap, and DIRB  into one menu-driven tool. Instead of typing each command out separately, the script asks me for an authorised target, checks that something was actually entered, shows a menu, and runs whichever tool I pick against that target.

## Features
- Accepts user-supplied target input (never hardcoded)
- Validates that a target was entered before continuing
- Menu-driven interface
- Uses Bash conditionals (`if`)
- Uses Bash `case` statements to route the selected tool
- Executes WhatWeb, Nmap, or DIRB
- Checks required tools are installed before running them

## Tools Used
- Bash
- Nmap
- WhatWeb
- DIRB

## Usage
Make the script executable, then run it:
```bash
chmod +x recon_tool.sh
./recon_tool.sh
```

## ⚠️ Authorisation
This script must only be run against systems I'm explicitly authorised to test. It was built and tested against the authorised lab target above as part of the ICDFA Cybersecurity & Digital Forensics programme.
