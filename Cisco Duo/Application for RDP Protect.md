# In this demo,

> ## how to protect **Microsoft Remote Desktop Protocol (RDP)** using **Cisco Duo Multi-Factor Authentication (MFA)**. The Duo Admin Panel is configured to enforce MFA before users are allowed to access a Windows system through RDP.

## Nevigate to `Applications` >> `Applications`
<p align="center"><img src="https://github.com/user-attachments/assets/20b24360-fb53-4e4f-bd82-f160e983a2f9"></p>

---

## Click `+ Add application`
<p align="center"><img src="https://github.com/user-attachments/assets/2b662227-0bfa-4f37-be70-065c046ce162"></p>

---

## Type `RDP` in search bar, Choose `Microsoft RDP` and Click `+ Add`
<p align="center"><img src="https://github.com/user-attachments/assets/fc185dd4-1ce2-47dd-aa5c-4348cde132b6"></p>

---

## Step 2 — Verify Application Details

After adding the app, you will see:

| Field | Value |
|------|-------|
| Application Name | Microsoft RDP |
| Application Type | Microsoft RDP |

This tells Duo:
> This application will protect Windows logon and Remote Desktop sessions.

## Step 3 — Configure User Access Policy

Under **User access**, select:

### 🔒 **Enable only for permitted groups**

This means:
> Only users inside this group can access RDP.

All other users are blocked—even if they know the password.
<p align="center"><img src="https://github.com/user-attachments/assets/a44eda87-0769-4016-9f0a-8b53e0b86ca5"></p>

---

# 🔑 Application Integration Details

These credentials are used by the **Duo Windows Logon Agent** to authenticate users.

| Field | Purpose |
|------|--------|
| Integration Key | Identifies the protected application |
| Secret Key | Cryptographic secret used to verify requests |
| API Hostname | Duo cloud endpoint for authentication |

These three values must be entered during **Duo agent installation** on the Windows server.

> ⚠️ The Secret Key must never be shared or stored in public repositories.
<p align="center"><img src="https://github.com/user-attachments/assets/4a3747c0-caee-4707-b95b-ede7a6ecd506"></p>

---
# 🛡️ Application Policy Configuration
> ## Policies define **who can authenticate** and **how MFA is enforced**.
> ## In this demo, I do not edit policies, if your organization required, you can define it.

<p align="center"><img src="https://github.com/user-attachments/assets/810b08fa-f203-4116-a8e6-81e91dd2449e"></p>


---

## All steps are done and `Save` it.

---

## 🛡️ Security Impact

This configuration ensures:
- Only authorized groups can access RDP
- MFA is enforced
- Windows is protected from password-based attacks
- All login attempts are logged for SOC monitoring

This completes the Zero Trust security model for RDP


