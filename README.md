# Ansible 802.1X Lab

This project uses **Ansible** to automate **802.1X network access control** on Cisco switches.  
I built this lab to get hands-on experience with **network automation**, **AAA**, and **RADIUS-based authentication**, using **pfSense** as the RADIUS server.

The main goal was to understand how 802.1X is configured on switches and how automation makes managing secure networks easier and more consistent.

---

## What This Lab Does
- Removes existing **port-security** settings
- Configures **AAA authentication and authorization**
- Enables **802.1X (dot1x)** on switch interfaces
- Integrates Cisco IOS switches with a **RADIUS server**
- Applies **spanning-tree portfast** where appropriate

---

## Skills & Tools Used
- **Ansible** for automating switch configurations  
- **Cisco IOS** for AAA and 802.1X setup  
- **RADIUS** for centralized authentication  
- **Network security** concepts related to NAC  
- **Git and GitHub** for version control and documentation  

---

## What I Learned
This lab reflects how organizations control access at the **switch port level** using 802.1X and RADIUS.  
Through this project, I improved my ability to:
- Automate repetitive network configuration tasks
- Configure Cisco switches for AAA and 802.1X
- Integrate network devices with external authentication services
- Organize and document technical projects using GitHub

---

## Project Structure

```
ansible/
├── ansible.cfg
└── inventory/
 └── hosts.yml
└── playbooks/
 └── 1X.yml
 └── test.yml
```

---

## File Overview
- `1X.yml` – Main playbook that removes port-security and enables 802.1X  
- `test.yml` – Playbook used for testing and validation  
- `hosts.yml` – Inventory file for target switches  
- `ansible.cfg` – Ansible configuration settings  
