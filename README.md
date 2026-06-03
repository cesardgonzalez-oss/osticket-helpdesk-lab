# Help Desk Ticketing System Lab (osTicket)

## Overview
A hands-on lab simulating a Tier 1 IT help desk environment. I built a Linux web server from scratch, deployed osTicket, configured it as a support desk, and worked support tickets through their full lifecycle.

## Environment / Tech Stack
- Ubuntu 24.04 Desktop (VirtualBox VM)
- LAMP stack: Apache 2.4, MariaDB, PHP 8.3
- osTicket v1.18.3

## What I Built
- Created and configured an Ubuntu VM in VirtualBox
- Installed and configured a LAMP stack (Apache web server, MariaDB database, PHP)
- Created a dedicated database and database user for osTicket
- Deployed osTicket, set secure file permissions, and removed installer files for security
- Configured the help desk: 5 help topics, multiple support agents, and canned responses

## Help Desk Operation
- Created 10+ support tickets covering common Tier 1 issues (account lockouts, password resets, printer/WiFi connectivity, software installation, VPN setup)
- Worked tickets through their full lifecycle: assignment, prioritization, customer response, internal troubleshooting notes, and resolution

## Screenshots

**1. Ubuntu VM running**
![Ubuntu desktop](Screenshot%202026-06-03%20120259.png)

**2. Apache web server live**
![Apache default page](Screenshot%202026-06-03%20120752.png)

**3. PHP and Apache installed**
![PHP and Apache versions](Screenshot%202026-06-03%20121408.png)

**4. osTicket database created**
![Database created](Screenshot%202026-06-03%20121740.png)

**5. osTicket installer (prerequisites passed)**
![osTicket installer](Screenshot%202026-06-03%20122539.png)

**6. Installation successful**
![Install success](Screenshot%202026-06-03%20122936.png)

**7. Admin panel**
![Admin panel](Screenshot%202026-06-03%20123215.png)

**8. Help topics configured**
![Help topics](Screenshot%202026-06-03%20123755.png)

**9. Support agents created**
![Agents](Screenshot%202026-06-03%20124120.png)

**10. Open ticket queue**
![Open queue](Screenshot%202026-06-03%20131239.png)

**11. Ticket worked through full lifecycle**
![Worked ticket](Screenshot%202026-06-03%20132800.png)

**12. Printer connectivity ticket resolved**
![Printer ticket](Screenshot%202026-06-03%20133644.png)

**13. VPN ticket resolved**
![VPN ticket](Screenshot%202026-06-03%20133950.png)

**14. All tickets resolved (closed queue)**
![Closed queue](Screenshot%202026-06-03%20134247.png)

## What I Learned
Throughout this project i learned how to build a Linux web server, setting up a LAMP stack on Ubuntu and deploying osTicket on top of it. I also learned how a real help desk operates through configuring help topics, agents, and canned responses then creating and working on support tickets through their full lifecycle: assigning them, setting priorities, responding to users, documenting troubleshooting in internal notes and resolving them. From this i've also learned troubleshooting such as diagnosing a corrupted Ubuntu ISO from read errors and re-downloading it, also resolved a VirtualBox graphic error by identifying an unstable Ubuntu release and switching to the stable 24.04 LTS, and fixed an osTicket ticket-locking issue by adjusting its settings.
