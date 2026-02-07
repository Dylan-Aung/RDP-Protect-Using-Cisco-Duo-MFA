
## **Testing Cisco Duo MFA for Windows Server RDP Logon**

## 📖 Project Overview  
This lab validates that **Cisco Duo Multi-Factor Authentication (MFA)** is correctly enforced when users connect to a **Windows Server via Remote Desktop (RDP)**.

The goal is to confirm:
> A user cannot log in using only a password — Duo MFA must be approved.

---

## 🧪 Test Environment

| Component | Description |
|--------|-------------|
| Windows Server | RDP Enabled |
| Cisco Duo | Cloud MFA Service |
| Duo Agent | Installed on Windows |
| User | `demouser1` |
| Duo Group | `DemoCustomer_Gp1` |
| Protected App | Microsoft RDP |

---

## 🔄 Authentication Flow
<p align="center"><img src="https://github.com/user-attachments/assets/094bc45c-5860-4c60-bd9c-979ab0c364da"></p>

---

## Step 1 — Start RDP Session
> ## From a client machine: Type `Win+R` Enter `mstsc`
<p align="center"><img src="https://github.com/user-attachments/assets/6aa50049-b049-4314-97ab-c464dfa3f6b4"></p>

---
## Enter `IP Address`,`Username` and Click `Connect`
<p align="center"><img src="https://github.com/user-attachments/assets/842c001a-7c4f-463c-9094-249bbe83816c"></p>

---
## Fill the `Password` and Click `OK`
<p align="center"><img src="https://github.com/user-attachments/assets/e981550b-5c62-4c14-a866-54b1617bd9c4"></p>

---

## Click `Yes`
<p align="center"><img src="https://github.com/user-attachments/assets/8b0d632d-79dd-43ff-b319-22bbaa365c21"></p>

---

## Now Duo Security notification is pop up on Window Server and also the notification will pop up in your mobile duo application.
<p align="center"><img src="https://github.com/user-attachments/assets/7ce16edd-0e46-4668-b6b4-7e55cc4df730"></p>

---

## Now, you can control the Window Server
<p align="center"><img src="https://github.com/user-attachments/assets/7eef5dd3-111f-4d13-8580-6535aa11477a"></p>

---

# 🧠 Why This Matters
> ## RDP is one of the main ransomware entry points.
# Cisco Duo ensures:
> ## No MFA = No Access









