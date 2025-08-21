# Ex-02 InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

## Architecture Diagram
```
                      +-------------------------+
                      |     Attacker System     |
                      |     (Kali Linux)        |
                      +-----------+-------------+
                                  |
                                  | Terminal / Browser
                                  | Executes Recon Tools
                                  v
      +------------------- Passive Recon --------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   WHOIS Query  | --> |    Domain Registrars    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   DNS Enum     | --> |     Public DNS Servers  |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      +-----------------------------------------------------+

                                  |
                                  v

      +------------------ Active Recon ----------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   Nmap Scan    | --> |  Target Host/Network    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | WhatWeb, Wapp | --> |   Target Web Application |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | theHarvester   | --> |     Search Engines      |  |
      |  +----------------+     +------------------------+  |
      +-----------------------------------------------------+

                                  |
                                  v
                    +-----------------------------+
                    |     Collected Information   |
                    | - IPs, Subdomains           |
                    | - Open Ports & Services     |
                    | - Technology Stack          |
                    | - Emails, Metadata          |
                    +-----------------------------+
```

## OUTPUT:
### Whois
<img width="1913" height="1007" alt="whois" src="https://github.com/user-attachments/assets/030d3f56-8b9e-4439-8345-2bf08dbbeaed" />

### Finding Hosting Company :


### History of the website :



### ping command :
"C:\Users\admin\VirtualBox VMs\kali\VirtualBox_kali_21_08_2025_09_16_20 ping.png"


### netcat :
"C:\Users\admin\VirtualBox VMs\kali\VirtualBox_kali_21_08_2025_08_35_56 net cat.png"

### nmap :
"C:\Users\admin\VirtualBox VMs\kali\VirtualBox_kali_21_08_2025_08_38_29 nmap.png"
### whatweb :
"C:\Users\admin\VirtualBox VMs\kali\VirtualBox_kali_21_08_2025_08_42_43 whtweb.png"

### httprint :


### TCP traceroute :
"C:\Users\admin\VirtualBox VMs\kali\VirtualBox_kali_21_08_2025_09_06_24 icp traceroute.png"

### UDP traceroute :
"C:\Users\admin\VirtualBox VMs\kali\VirtualBox_kali_21_08_2025_09_10_34 udp.png"

## RESULT:
The information gathering techniques tools/procedure were  identified successfully
