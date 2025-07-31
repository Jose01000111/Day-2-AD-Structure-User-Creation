# 🏦 Day 2 — AD Structure & PowerShell User Creation  
## Chicago Bank Branch Active Directory Lab (Hyper-V)  

### Welcome to Day 2 of my 5-Day Active Directory Lab project!  
Today I built the AD structure for the Chicago branch and used PowerShell to automate user creation. This helped simulate a real-world enterprise user provisioning workflow.

## 🛠️ Environment  
💻 Host OS: Windows 10 with Hyper-V  
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
📸 Screenshot: OU structure displayed in ADUC  
`ImgID1`

## 🧑‍💻 Opened PowerShell as Administrator  Launched PowerShell to begin automated user provisioning.  
📸 Screenshot: PowerShell running with admin privileges  
`ImgID2`

## 📦 Imported Active Directory Module  Loaded the ActiveDirectory module successfully to enable AD cmdlets.  
📸 Screenshot: Module imported with no errors  
`ImgID3`

## ⚙️ Executed PowerShell Script to Create Users  Ran a PowerShell script to bulk-create 7 users with attributes, password settings, and OU placement.  
📸 Screenshot: Script run successfully in PowerShell  
`ImgID4`

## 🔍 Verified Users in ADUC  Opened each OU in ADUC to confirm correct user placement and account creation.  
📸 Screenshot: Users in Admins OU  
`ImgID5`  
📸 Screenshot: Users in HelpDesk OU  
`ImgID6`  
📸 Screenshot: Users in Employees OU  
`ImgID7`

## 🧾 Summary  
## Day 2 was all about structure and automation. I successfully organized the OU hierarchy and automated user creation using a clean PowerShell loop. This setup reflects a real enterprise onboarding process, and it's laying the foundation for upcoming Group Policy and user management tasks.

