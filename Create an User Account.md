# In this demo,

<p align="center"><img src="https://github.com/user-attachments/assets/59963749-996e-40e2-9550-8743125574f2"></p>

---

<p align="center"><img src="https://github.com/user-attachments/assets/6a932214-473f-48c5-8d8e-fae73971dc53"></p>

---

<p align="center"><img src="https://github.com/user-attachments/assets/3c7ef77c-e8b0-4eb4-9545-dbdcabea6ea3"></p>

---


## Step 1 — Enroll the User’s Device
At the top of the page, the status shows:

> **Not enrolled**

Choose one of the following:

### Option A — Send Enrollment Email
1. Click **Send email**
2. The user receives a link to enroll their phone using Duo Mobile

### Option B — Generate Enrollment Code
1. Click **Generate code**
2. Copy the link
3. Send it to the user

The user installs **Duo Mobile** and scans the QR code to complete enrollment. In this option, I choose the `Option A`

<img width="822" height="411" alt="image" src="https://github.com/user-attachments/assets/dfb591d9-3086-4441-ac88-b2423d18cc7b" />

<img width="685" height="406" alt="image" src="https://github.com/user-attachments/assets/cd6d4e50-2a2c-47c0-bac9-f923eadb7dec" />

---

<img width="406" height="404" alt="image" src="https://github.com/user-attachments/assets/7c877883-122d-49b9-abce-d009992f5b69" />
<img width="289" height="379" alt="image" src="https://github.com/user-attachments/assets/6ae5071b-3314-4856-99be-e1a50f10d103" />
<img width="296" height="406" alt="image" src="https://github.com/user-attachments/assets/309b58ae-8b3c-4331-8d99-fb8340b5e568" />
<img width="291" height="382" alt="image" src="https://github.com/user-attachments/assets/342a8f4d-06e6-46ab-acf5-8334245f3bb5" />
<img width="289" height="366" alt="image" src="https://github.com/user-attachments/assets/5838aadc-0123-458a-adb4-6311ccbd689e" />
<img width="297" height="357" alt="image" src="https://github.com/user-attachments/assets/76b45c48-90e6-4568-a6ad-ef55d8583dee" />
<img width="563" height="433" alt="image" src="https://github.com/user-attachments/assets/07be6ce8-1781-4fed-bc7e-d30ba0568104" />



---

## Step 2 — Enter User Information

<p align="center"><img src="https://github.com/user-attachments/assets/3bd2c7d7-c815-4740-861c-172f68ee426a"></p>

---

## Step 7 — Assign the User to a Group
> Under **Groups**, select: **DemoCustomer_Gp1** This links the user to the group that enforces MFA policies.

<p align="center"><img src="https://github.com/user-attachments/assets/98b35f0c-795d-4eb6-be8b-97e800662447"></p>

## Step 8 — Save Changes
Click **Save Changes**

The user is now:
- Registered in Duo
- Assigned to a security group
- Ready for MFA

## 🛡️ Security Result

The user **demouser1** is now protected by:
- Duo MFA
- Group-based policy enforcement
- Device verification

Any login attempt will require **Duo push, passcode, or phone verification**, blocking unauthorized access.
