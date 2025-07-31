# 🏦 Day 2 — AD Structure & PowerShell User Creation  
## Chicago Bank Branch Active Directory Lab (Hyper-V)  

### Welcome to Day 2 of my 5-Day Active Directory Lab project!  
Today I built the AD structure for the Chicago branch and used PowerShell to automate user creation. This helped simulate a real-world enterprise user provisioning workflow.

## 🛠️ Environment  
💻 Host OS: Windows 11 Pro with Hyper-V  
🖥️ VM: Windows Server 2022 (Domain Controller - CHICAGO-DC01)  
🌐 Domain: chicago.bankcorp.local  
📂 OUs: ChicagoBranch > Admins, HelpDesk, Employees  
👤 Users: 7 total (1 admin, 2 help desk, 4 employees)  
🧰 Tools: ADUC (Active Directory Users & Computers), PowerShell

| Full Name      | Username   | OU        | Email                        | 
|----------------|------------|-----------|------------------------------|
| Jose Guerrero  | jguerrero  | Admins    | jguerrero@chicago.bankcorp.local | 
| Angela Price   | aprice     | HelpDesk  | aprice@chicago.bankcorp.local    | 
| David Lin      | dlin       | HelpDesk  | dlin@chicago.bankcorp.local      | 
| Maria Lopez    | mlopez     | Employees | mlopez@chicago.bankcorp.local    | 
| Chris Young    | cyoung     | Employees | cyoung@chicago.bankcorp.local    | 
| Lisa Chen     | lchen      | Employees | lchen@chicago.bankcorp.local     | 
| Omar Brown     | obrown     | Employees | obrown@chicago.bankcorp.local    | 


## ✅ What I Did:

## 🏗️ Created Organizational Units (OUs)  Used ADUC GUI to build the ChicagoBranch structure with nested OUs: Admins, HelpDesk, and Employees.  

<img width="899" height="324" alt="AbotYLJ" src="https://github.com/user-attachments/assets/62e8d298-7397-418b-a45c-dd522e0cf9d4" />

<img width="905" height="444" alt="3T32v9F" src="https://github.com/user-attachments/assets/ce4fe6e2-2cfd-4f6f-ab5b-b35043807824" />

<img width="893" height="224" alt="5TFaApe" src="https://github.com/user-attachments/assets/aa08b901-805c-453c-99dd-4915deac9e6c" />

## 🧑‍💻 Opened PowerShell as Administrator  Launched PowerShell to begin automated user provisioning.  

<img width="771" height="496" alt="6k6b0Sd" src="https://github.com/user-attachments/assets/18ea474f-8a5a-4bec-8d3c-b723f7e63f92" />

## 📦 Imported Active Directory Module  Loaded the ActiveDirectory module successfully to enable AD cmdlets.  

<img width="980" height="199" alt="da9bXk5" src="https://github.com/user-attachments/assets/f5c56198-7583-4904-aa26-f38ebf419fbf" />

## ⚙️ Executed PowerShell Script to Create Users  Ran a PowerShell script to bulk-create 7 users with attributes, password settings, and OU placement.  

<img width="775" height="544" alt="TeoloZu" src="https://github.com/user-attachments/assets/576b7540-7a74-46ad-9107-e0a139934e30" />

## 🔍 Verified Users in ADUC  Opened each OU in ADUC to confirm correct user placement and account creation.  

<img width="899" height="228" alt="oQ4JKKF" src="https://github.com/user-attachments/assets/924681b1-3f04-46b4-b6c7-ab916935d5f8" />

<img width="907" height="210" alt="4AkvifM" src="https://github.com/user-attachments/assets/e3d7b837-1550-42f2-8441-732c75acba52" />

<img width="901" height="238" alt="ejfDb5z" src="https://github.com/user-attachments/assets/bee0a74d-0298-4ed5-8323-dc4ea698273f" />

## 🧾 Summary  
## Day 2 was all about structure and automation. I successfully organized the OU hierarchy and automated user creation using a clean PowerShell loop. This setup reflects a real enterprise onboarding process, and it's laying the foundation for upcoming Group Policy and user management tasks.

