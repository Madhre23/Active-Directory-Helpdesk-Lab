Active Directory Home Lab Setup Guide


Step 1 - Created Virtual Machine
-Created a Windows Server virtual machine in VirtualBox and allocated system resources (RAM, CPU, storage).
-This virtual machine acts as a dedicated server environment for the lab.

Step 2 - Installed Windows Server 2022
-Installed Windows Server 2022 (Desktop Experience) using an ISO file and configured the Administrator account.
-Windows Server provides the platform required to run Active Directory services.

Step 3 - Installed Active Directory Domain Services
-Used Server Manager to install the Active Directory Domain Services (AD DS) role.
-AD DS enables centralized management of users, authentication, and access control.

Step 4 - Created Domain Controller
-Promoted the server to a Domain Controller by creating a new forest with the domain:
 mylab.local

The Domain Controller is responsible for:

Authenticating users
Managing permissions
Controlling access to resources


Successfully built a functioning Active Directory environment with:
-Windows Server 2022
-Active Directory Domain Services
-Domain Controller configured under:
 mylab.local
