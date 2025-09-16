# Ansible 802.1X Lab

This project automates the configuration of **802.1X Network Access Control (NAC)** on Cisco switches using **Ansible**.  
It was developed as part of a hands-on lab to gain practical experience with **network automation**, **AAA security**, and **RADIUS integration** (via pfSense as the RADIUS server).

---

## Features
- Removes existing **port-security** configurations
- Configures **AAA authentication and authorization** for 802.1X
- Applies **802.1X port-based authentication** on selected interfaces
- Integrates Cisco IOS devices with a **RADIUS server** (auth-port 1812, acct-port 1813)
- Supports **spanning-tree portfast** for faster port initialization

---

## Skills & Tools Demonstrated
- **Ansible Automation**: Writing playbooks and managing network configs  
- **Cisco IOS Networking**: Switch configuration, AAA, and dot1x setup  
- **RADIUS Authentication**: Centralized identity and access control  
- **Network Security**: Implementing NAC to secure switch ports  
- **Version Control**: Using Git/GitHub for project tracking  

---

## Learning Outcomes
This project simulates how enterprises secure access at the switch port level using **802.1X and RADIUS**.  
It strengthened my ability to:  
- Automate repetitive tasks with Ansible  
- Integrate Cisco switches with external authentication systems  
- Apply real-world security practices (NAC) in a lab environment  
- Use GitHub for professional project documentation and version control  

---

## Files
- `1X.yml` → Main playbook for removing port-security and enabling 802.1X  
- `test.yml` → Secondary playbook for testing configs  
- `hosts.yml` → Inventory file for target switches  
- `ansible.cfg` → Ansible configuration file  
- `.gitignore` → Ensures only relevant files are tracked  
- `README.md` → Project documentation (this file)  

---

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/khaliddagian/ANSIBLE-LAB.git
   cd ANSIBLE-LAB
