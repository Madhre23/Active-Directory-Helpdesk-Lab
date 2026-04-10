# Active Directory Home Lab Setup Guide



## Step 1 – Created Virtual Machine

- Created a Windows Server virtual machine in VirtualBox
- Allocated system resources (RAM, CPU, storage)
- Provides an isolated server environment for the lab


## Step 2 – Installed Windows Server 2022

- Installed Windows Server 2022 (Desktop Experience) using an ISO file
- Configured the Administrator account
- Serves as the operating system required to run Active Directory services
<img width="700" height="723" alt="step1" src="https://github.com/user-attachments/assets/bfbfa186-d515-4f4a-8257-635bf5c7f619" />


## Step 3 – Installed Active Directory Domain Services

- Installed the Active Directory Domain Services (AD DS) role using Server Manager
- Enables centralized management of users, authentication, and access control

<img width="700" height="735" alt="server-manager" src="https://github.com/user-attachments/assets/0506125e-3fa3-49ef-9c64-83478a479b47" />


## Step 4 – Created Domain Controller

- Promoted the server to a Domain Controller
- Created a new forest with the domain:

```id="c6kv2l"
mylab.local
```
<img width="700" height="723" alt="step2" src="https://github.com/user-attachments/assets/8fa027d2-4f77-42ee-8151-d03555a0004a" />


## Step 5 – Created Users in Active Directory
- Created multiple user accounts for testing and simulation  
- These users will be used to simulate help desk scenarios
- John Smith, Gursimarjot Singh, and Mike Lee (users)

<img width="700" height="728" alt="Screenshot 2026-04-10 165310" src="https://github.com/user-attachments/assets/aecc3a1b-59d7-452a-b631-71e2e8ec79d6" />


## Step 6 – Simulated Help Desk Scenarios

- Performed common IT support tasks using Active Directory to simulate real-world help desk scenarios

### Case 1 – Password Reset

- User was unable to log in to their account
- Reset password in Active Directory to restore access

<img width="1020" height="729" alt="case1fix" src="https://github.com/user-attachments/assets/96cb2a76-b6af-48e3-804d-68e59b6b86ec" />


### Case 2 – Access Issue (Group Membership)

- User could not access required resources
-Added user to the appropriate security group to grant permissions

<img width="1022" height="735" alt="case2fix" src="https://github.com/user-attachments/assets/b547b93c-3d32-4648-b815-9ca6774d824a" />
### Case 3 – Account Disabled

- User account was not accessible
-Identified account as disabled and re-enabled it in Active Directory

<img width="1026" height="764" alt="case3fix" src="https://github.com/user-attachments/assets/cd6e54f1-418b-4753-b1cb-a2d49eb0e9e0" />

## Summary
- Built an Active Directory lab environment using Windows Server
- Simulated real help desk scenarios
- Resolved user issues using Active Directory
- Documented ticket-based workflow




