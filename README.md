# 🧠 SOC Home Lab Using Microsoft Sentinel

A hands-on cybersecurity project that builds a **Home SOC (Security Operations Center)** in Microsoft Azure.

This lab demonstrates how to deploy a **honeypot virtual machine**, collect and analyze security logs with **Azure Log Analytics**, and visualize attacker activity using **Microsoft Sentinel**.

---

## 🧩 Project Overview

This project simulates a real-world SOC environment in the cloud.  
You will:
1. Deploy a **Windows 10 honeypot** on a free Azure account.
2. Expose it to the internet to attract live attack traffic.
3. Forward logs from the VM to **Log Analytics Workspace**.
4. Connect **Microsoft Sentinel (SIEM)** to analyze attack data.

---

## 🚀 Technologies Used

- **Microsoft Azure** (Free Subscription)
- **Virtual Machines (Windows 10)**
- **Azure Log Analytics Workspace**
- **Microsoft Sentinel (SIEM)**
- **Azure Monitoring Agent**
- **KQL (Kusto Query Language)** for querying logs
- **PowerShell / CMD**

---

## 🧱 Architecture

<img width="1361" height="782" alt="image" src="https://github.com/user-attachments/assets/7de1947b-c85e-4ab8-9909-60f0c91edbc0" />

## 📈 Results
- Captured thousands of real login attempts from global IPs  
- Identified brute-force patterns and common attacker regions  
- Created visual dashboards in Sentinel for analysis

---

## 🧩 Lessons Learned
- Exposed systems get attacked within minutes of going live.  
- Centralized logging and visibility are key to incident detection.  
- Cloud-native SIEMs like Sentinel make analysis efficient.



