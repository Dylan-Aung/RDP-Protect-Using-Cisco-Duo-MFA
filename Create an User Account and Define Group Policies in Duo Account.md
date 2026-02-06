# Creating and Configuring Groups in Cisco Duo

## 🔐 In this demo, we will:
> ### how to create and configure a security group inside Cisco Duo Admin Panel to control Multi-Factor Authentication (MFA) behavior for users.

## Step 1 — Navigate to: `Users` >> `Groups`
<p align="center"><img src="https://github.com/user-attachments/assets/3fa1b63b-e9a5-42cd-a7bf-646462c34476"></p>

---

## Step2 — Click `+ Add group`
> ### This creates a logical container to control MFA policies for specific users.
<p align="center"><img src="https://github.com/user-attachments/assets/e6ecf0cc-3be9-4f74-8fd4-e32c9c60f393"></p>

---

## Step 3 — Define `Group name` and give `Description`
<p align="center"><img src="https://github.com/user-attachments/assets/92723e86-ba6d-4ce6-b486-4664aaf58445"></p>

---

## Step 4 — Verify Group Information
After the group is created, confirm the following fields on the group details page:

| Field | Purpose |
|------|--------|
| Group Name | Identifies the group |
| Description | Explains the group’s role |
| Group ID | Unique identifier assigned by Duo |

The Group ID is automatically generated and used internally by Duo.

## Step 5 — Configure Group Status

Under **Status**, select:

### ✅ **Active**
This enforces:
> **Two-Factor Authentication (MFA) is required for all users in this group**

Other options:
- **Bypass** – Allows login without MFA (not secure)
- **Disabled** – Blocks user access

Best practice: keep the group set to **Active**.
<p align="center"><img src="https://github.com/user-attachments/assets/d5bfcdf9-bf25-404a-901f-5ce16f2408d5"></p>

---

<p align="center"><img src="https://github.com/user-attachments/assets/59963749-996e-40e2-9550-8743125574f2"></p>

---

<p align="center"><img src="https://github.com/user-attachments/assets/6a932214-473f-48c5-8d8e-fae73971dc53"></p>

---

<p align="center"><img src="https://github.com/user-attachments/assets/3c7ef77c-e8b0-4eb4-9545-dbdcabea6ea3"></p>

---

