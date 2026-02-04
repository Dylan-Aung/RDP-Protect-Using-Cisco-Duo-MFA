# 🛡️ Active Directory Domain Services (AD DS) Installation

**Active Directory Domain Services (AD DS)** is the foundation of Windows Server environments. It provides a centralized system for managing users, computers, and security policies, ensuring that authentication and authorization are handled securely across the enterprise. 

## In this demo, we will: 
> Install the **Active Directory Domain Services (AD DS)** role on Windows Server and promote the server to a **Domain Controller (DC)**.

### ⚙️ Launch to Server Manager, Top right corner you will see `Manage` > `Add Roles and Features` 
<p align="center"><img src="https://github.com/user-attachments/assets/e659c52b-679c-44e1-b54b-343d2e83a7f7"></p>

---

### ⚙️ Click `Next`
<p align="center"><img src="https://github.com/user-attachments/assets/18a88424-29ff-4366-8402-e1baf472fde3"></p>

---

### ⚙️ Select `"Role-based or feature-based installation"` and Click `Next`
<p align="center"><img src="https://github.com/user-attachments/assets/b36cd6db-3d6c-48a8-8608-f76d6de437b1"></p>

---

### ⚙️ Choose `WS2022-AD` and Click `Next`
<p align="center"><img src="https://github.com/user-attachments/assets/85bac9dc-fa70-4052-a618-3628a10f2ef1"></p>

---

### ⚙️ Check in the box `Active Directory Domain Services`, `Add Features` and Click `Next`
<p align="center"><img src="https://github.com/user-attachments/assets/668964c3-9028-4923-9801-6c95aa626bba"></p>

---

### ⚙️ No need to check any boxes and Click `Next`
<p align="center"><img src="https://github.com/user-attachments/assets/d7155648-c45d-4717-a62c-d1f1e87e2e05"></p>

---

### ⚙️ Just Click `Next`
<p align="center"><img src="https://github.com/user-attachments/assets/d116828d-43c3-42c9-84a8-7516121dbdf7"></p>

---

### ⚙️ Click `Install` and wait for it
<p align="center"><img src="https://github.com/user-attachments/assets/31b02fae-6762-422e-a003-90adba98bbe4"></p>

---

### ⚙️ When installation finished, you need to promote in Domian Controller and Click `Close`
<p align="center"><img src="https://github.com/user-attachments/assets/f147b949-020c-4f45-8692-e1428117501e"></p>

---

### ⚙️ Go back to Server Manager Dashboard, you will see the notification flag and Click `Promote this server to a domain controller`
<p align="center"><img src="https://github.com/user-attachments/assets/3d78f416-cdba-43da-a4b9-0211eb447898"></p>

---

### ⚙️ `Add a new forest` and give a top level domain name. `e.g - abcdefg.com, edu, org or something`
<p align="center"><img src="https://github.com/user-attachments/assets/3c28c3ea-071e-4059-ba8c-038af95d31fe"></p>

---

### ⚙️ Give a `password` and Click `Next`
<p align="center"><img src="https://github.com/user-attachments/assets/198796ec-b110-4f55-840c-b1e07d97b026"></p>

---

#### Click `Next`
<p align="center"><img src="https://github.com/user-attachments/assets/eec613f8-fad8-4eb4-a0a7-49d1e3f3c404"></p>

---

#### Click `Next`
<p align="center"><img src="https://github.com/user-attachments/assets/24028e60-cdde-46fe-9e82-507a614c05f8"></p>

---

### In this case, 
> I highly recommended to move the Database and Log files to a separate physical drive (other than the C: drive) to improve performance and prevent the system volume from running out of space. `But this is the lab envrionment, you can do whatever you want.`

* Database folder path: Stores the NTDS.dit file. This is the heart of Active Directory, containing all domain data, user objects, passwords, and group memberships.

* Log files folder path: Stores the transaction logs for the database. These logs record changes to the AD database before they are committed, ensuring data integrity in the event of a system crash.

* SYSVOL folder path: A shared directory that stores the domain’s public files, primarily Group Policy Objects (GPOs) and logon/logoff scripts. This folder is replicated to all other Domain Controllers in the domain.
### ⚙️ Click `Next`
<p align="center"><img src="https://github.com/user-attachments/assets/27d881b5-643a-4b84-8ef5-48663aa19cc4"></p>

---

### ⚙️ Click `Next`
<p align="center"><img src="https://github.com/user-attachments/assets/d13b8451-776a-4509-bceb-01cf38c6d4cc"></p>

---

### ⚙️ Click `Install`
<p align="center"><img src="https://github.com/user-attachments/assets/9ffa3502-96b7-4a68-ad03-534024f989e2"></p>

---









