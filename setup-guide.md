# Active Directory Home Lab Setup Guide



## Step 1 – Created Virtual Machine

* Created a Windows Server virtual machine in VirtualBox
* Allocated system resources (RAM, CPU, storage)
* Provides an isolated server environment for the lab


## Step 2 – Installed Windows Server 2022

* Installed Windows Server 2022 (Desktop Experience) using an ISO file
* Configured the Administrator account
* Serves as the operating system required to run Active Directory services



## Step 3 – Installed Active Directory Domain Services

* Installed the Active Directory Domain Services (AD DS) role using Server Manager
* Enables centralized management of users, authentication, and access control

<img width="700" height="735" alt="server-manager" src="https://github.com/user-attachments/assets/0506125e-3fa3-49ef-9c64-83478a479b47" />


## Step 4 – Created Domain Controller

* Promoted the server to a Domain Controller
* Created a new forest with the domain:

```id="c6kv2l"
mylab.local
```





