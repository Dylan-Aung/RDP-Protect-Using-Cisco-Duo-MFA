# In this demo,

> ## We are going to create a new user account by following step.

## Step 1 — Navigate to: `Users` >> `Users`
<p align="center"><img src="https://github.com/user-attachments/assets/59963749-996e-40e2-9550-8743125574f2"></p>

---

## Step 2 — Click `Add Users` on the right corner.
<p align="center"><img src="https://github.com/user-attachments/assets/6a932214-473f-48c5-8d8e-fae73971dc53"></p>

---

## Step 3 — Fill in the box, what you want. In this demo, I'm going to use `demouser1`.
<p align="center"><img src="https://github.com/user-attachments/assets/3c7ef77c-e8b0-4eb4-9545-dbdcabea6ea3"></p>

---

## Step 4 — Enroll the User’s Device
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

> ## The user installs **Duo Mobile** and scans the QR code to complete enrollment. In this option, I choose the `Option A`

<p align="center"><img src="https://github.com/user-attachments/assets/da459d55-9841-4038-bfdc-e759ddd7ebe8"></p>

> ## After clicked `Send email`, the enrollment will send in your email.

<img width="685" height="406" alt="image" src="https://github.com/user-attachments/assets/cd6d4e50-2a2c-47c0-bac9-f923eadb7dec" />

---
## Step 5 — Enrollment the User’s Device Step by Step and Scan QR code using Duo Mobile Application.
<p align="center"><img src="https://github.com/user-attachments/assets/52b32a6c-6871-4ff3-b224-e1d0af0619ef"></p>

> ## It is completed and show up `Enrolled` Status
<p align="center"><img src="https://github.com/user-attachments/assets/07be6ce8-1781-4fed-bc7e-d30ba0568104"></p>

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
