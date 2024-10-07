# Asterisk PBX Dial Plan Project

## Project Overview
This project implements a dial plan for an Asterisk-based PBX system. It includes two SIP subscribers and two IAX2 subscribers, each with specific functionality. The PBX system is set up using AsteriskNOW on a CentOS virtual machine, and the phones are managed using MicroSIP and ZoIPer software.

## Features
- SIP subscribers: Timeouts for calls
- IAX2 subscribers: Call recording
- Integration of SIP and IAX2 in call management
- Full support for DIAL, RINGING, ANSWER, and HANGUP functions

## Setup Instructions
1. Install Oracle VM VirtualBox and set up a CentOS virtual machine.
2. Download and install AsteriskNOW on the CentOS VM.
3. Install the necessary software phones:
  * MicroSIP 3.21.3
  * ZoIPer 5.6.4
4. Configure the dial plan in extensions.conf, sip.conf, and iax.conf.

## How to Use
+ After setting up AsteriskNOW and configuring the dial plan, use MicroSIP and ZoIPer to test calls between subscribers.
+ Follow the project's specific settings based on group 3 (x=3) and function 6 for SIP (Timeout) and 7 for IAX2 (Recording).

## Acknowledgments
The project follows guidelines from the course at [UTCluj](https://el.el.obs.utcluj.ro/scr/Teme_proiect.htm).

# Project location
Due to its substantial size, the project can be found at [my OneDrive](https://didatec-my.sharepoint.com/:u:/r/personal/bota_io_ioana_student_utcluj_ro/Documents/Proiect%20SCR/AsteriskNOW%20Clone%20SIP_IAX%20final1.0.zip?csf=1&web=1&e=CCvfbq).
