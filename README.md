# Exchange
Checkmk extensions for the public exchange

This is the official Checkmk Exchange from ITeratio.
The packages are sent through development with customers and are approved by them.
Comments and suggestions for improvement are very welcome.

Installation:
Deploy Package to Checkmk-Site
Run 
    mkp install PACK.mkp

* **Active Radius Check using pyrad**: Active Check for Radius Server. Tested with Windows Domain Controller acting as server. Original Project: https://exchange.checkmk.com/p/radius
* **Dell EMC ML3**: SNMP Checks for Dell Tape Drives
* **MSHPC special agent**: Special agent for MSHPC, checking jobs, nodes and node states. Will create piggyback data for nodes.
* **Notification Plugin for Cordaware bestinformed**: Send notification to your Screen. Tool see https://www.cordaware.com/deu/cordaware-bestinformed
* **Palo Alto PAN DDOS FLOW**: SNMP Checks 
* **PiHole**: Special Agent for query pihole, Checks, HW/SW Inventory
* **SAP MaxDB Plugin**: Checks the following things: General Status, Log/Database Utilization, Sessions, Backup Status for Checkmk 2.X
* **SNMP Systemtime**: Gets the Timestamp of an SNMP-Device and compair it with the checmk-Server Time
* **WSUS set downtime**: Gets patchdate and -time information of the Windows registry and sets an accordingly downtime


To check the content of the MKPs, you can simply unpack them. MKPs are nothing more than tar files
