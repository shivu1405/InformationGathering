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
<img width="1917" height="986" alt="ip2location" src="https://github.com/user-attachments/assets/a0f6eddb-8565-4b60-9dec-d7166eab013f" />


### History of the website :
<img width="1912" height="1047" alt="history" src="https://github.com/user-attachments/assets/7d65f67f-bd68-481e-92ed-40ba440fc331" />



### ping command :
<img width="1920" height="1057" alt="VirtualBox_kali_21_08_2025_09_16_20 ping" src="https://github.com/user-attachments/assets/31be61f8-7fbc-4b38-89fb-87ecf01afb6e" />


### netcat :
<img width="1920" height="1057" alt="VirtualBox_kali_21_08_2025_08_35_56 net cat" src="https://github.com/user-attachments/assets/6be3a043-15e7-4768-85a7-0cea88af8458" />


### nmap :
<img width="1920" height="1057" alt="VirtualBox_kali_21_08_2025_08_38_29 nmap" src="https://github.com/user-attachments/assets/2ac3ba23-4ec6-4ac6-b986-5b2a08cd4cb5" />


### whatweb :

<img width="1920" height="1057" alt="VirtualBox_kali_21_08_2025_08_42_43 whtweb" src="https://github.com/user-attachments/assets/c801d5fc-66f0-4db8-93f0-7476cd1c3db3" />

### httprint :
<img width="1920" height="1057" alt="VirtualBox_kali_21_08_2025_09_32_33 http" src="https://github.com/user-attachments/assets/7c50ef02-5f7d-431c-8f93-6638b6351054" />


### TCP traceroute :
<img width="1920" height="1057" alt="VirtualBox_kali_21_08_2025_09_06_24 icp traceroute" src="https://github.com/user-attachments/assets/b80d667c-74dc-4f8c-9360-86694cac944f" />



### UDP traceroute :
<img width="1920" height="1057" alt="VirtualBox_kali_21_08_2025_09_10_34 udp" src="https://github.com/user-attachments/assets/d94a1771-1c29-4aaa-a1fa-4f3a0c61f05b" />


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
