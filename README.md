# Active-Directory-Deployment-


<img width="1536" height="1011" alt="image" src="https://github.com/user-attachments/assets/c86da1b0-e3d1-4be0-aa8d-6f5f573a57e3" />

<h2> Objective </h2>

- The main objective is to set up a basic Active Directory domain environment, including a domain controller, a domain administrator account, and a client machine joined to the domain.

<h2>Skills Used</h2>

- Active Directory Domain Services (AD DS) Installation & Configuration: Installing the AD DS role, promoting a server to a domain controller, and creating a new forest.

- Active Directory Users and Computers (ADUC) Management: Creating Organizational Units (OUs), creating new user accounts, and adding users to security groups.

- Network Configuration (DNS): Understanding and modifying DNS settings to point clients to the domain controller.

- Domain Joining: Joining client machines to an Active Directory domain.

- User Account Management: Logging in with different user accounts (local admin, domain user, domain admin) and understanding their permissions.

- Basic Troubleshooting/Verification: Verifying that a client machine has successfully joined the domain within ADUC.

- Azure Portal Navigation (Implied): Interacting with Azure Portal to modify VM settings like DNS and initiate restarts.


<h2>Services Used</h2>

- Active Directory Domain Services (AD DS): The core service for identity and access management.

- Azure Virtual Machines (VMs): The underlying cloud service hosting DC-1 and Client-1.

- Azure Networking (DNS settings): Utilized for configuring DNS resolution for the client machine


<b>


To start open server manager in start menu, once it's open you'll click on add roles and features -> next -> next, you should see in server selection, DC-1's private IP address, click next.

<img width="1301" height="681" alt="image" src="https://github.com/user-attachments/assets/bedaff51-5075-47d1-a443-ada09ea0280a" />


For Server Roles section click on "Active Directory Domain Services" and click on add features. On features and AD DS section just click next and skip. When you get to confirmation section click on "Restart the destination server automatically if required", and fianlly click install.

<img width="1121" height="612" alt="image" src="https://github.com/user-attachments/assets/9d78568f-5847-4145-b313-83cd2b3535f9" />


<img width="1190" height="672" alt="image" src="https://github.com/user-attachments/assets/e2279c0b-7929-4aca-897a-792752e41b30" />



<img width="977" height="616" alt="image" src="https://github.com/user-attachments/assets/77c8709f-e20f-4823-a367-5f1720db3b54" />


<img width="973" height="433" alt="image" src="https://github.com/user-attachments/assets/645149f0-a05b-4e93-acea-49587fe6a29f" />

<img width="1094" height="515" alt="image" src="https://github.com/user-attachments/assets/c39df8db-5e33-4cd7-bef0-c054c32fbbc4" />


<img width="919" height="570" alt="image" src="https://github.com/user-attachments/assets/4704338e-e191-4905-9059-33b85b95a223" />



<img width="1109" height="612" alt="image" src="https://github.com/user-attachments/assets/d59a98e2-1dd7-466e-9495-0b8ae32a5946" />


<img width="931" height="509" alt="image" src="https://github.com/user-attachments/assets/7daba2fe-eb98-4ddc-84bc-455127f0c887" />

<img width="1004" height="552" alt="image" src="https://github.com/user-attachments/assets/196ae605-5520-459f-bc68-ecb96633c997" />


<img width="638" height="390" alt="image" src="https://github.com/user-attachments/assets/e0a750ce-cefc-450d-8b57-fe848bd19530" />



<img width="1272" height="662" alt="image" src="https://github.com/user-attachments/assets/e5a5348a-1367-457b-a4d0-c254ab2f11b3" />


<img width="1244" height="596" alt="image" src="https://github.com/user-attachments/assets/5fcf39a8-5522-4f4e-8ec5-60e224ba0c90" />


<img width="975" height="584" alt="image" src="https://github.com/user-attachments/assets/848437e0-991c-47fc-b8e7-bb071ce2708e" />



























































































