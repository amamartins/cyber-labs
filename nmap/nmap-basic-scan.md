# Nmap Basic Scan

11/16/25 
**Purpose:** Practice running basic Nmap scans in a safe lab environment.

Updated: 2/16/26 to test additional commands
---

## Command Used
nmap -sC -sV <target-ip>

<img width="281" height="19" alt="command" src="https://github.com/user-attachments/assets/811fb88f-bb21-4be2-b5d9-8e17ba13f093" />


## What Each Flag Means
- `-sC` : runs default scripts  
- `-sV` : detects service versions  
- `192.168.56.1` : the system being scanned (in my isolated lab)

---

## Output
<img width="401" height="188" alt="image" src="https://github.com/user-attachments/assets/1faba14a-c345-449e-8095-dee039ed4887" />


---
Update -- more commands I learned

nmap -A __targetip__
## Output

<img width="955" height="439" alt="nmap -A" src="https://github.com/user-attachments/assets/bb205beb-df90-493b-84a5-51544d88cb2d" />

nmap -p 22,80,443 __targetip__ - to view specific ports
## Output

<img width="566" height="170" alt="nmap -p" src="https://github.com/user-attachments/assets/6290ad71-16d2-4edd-bc12-2a406b2359b9" />

## What I Learned
- How to run a safe, basic Nmap scan
- How to complete an aggresive scan
- How to identify open ports  
- How to read service version info
- Enumerated exposed services and identified 
