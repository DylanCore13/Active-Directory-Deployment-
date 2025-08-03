# Active-Directory-Deployment-


<img width="1536" height="1011" alt="image" src="https://github.com/user-attachments/assets/c86da1b0-e3d1-4be0-aa8d-6f5f573a57e3" />

<h2> Objective </h2>

- This setup guide outlines configuring an Azure-based Active Directory lab by first creating a resource group, virtual network, and a Windows Server 2022 VM named "DC-1" with a static private IP and disabled firewall. Subsequently, a Windows 10 VM named "Client-1" is provisioned within the same network, its DNS settings are configured to point to "DC-1"'s private IP, and connectivity is verified by pinging "DC-1" and checking the DNS settings via ipconfig /all on "Client-1".

<h2>Skills Used</h2>

- Azure Resource Management: Creating and managing resource groups, virtual machines (VMs), and virtual networks (VNets). This involves understanding how to provision and configure resources within the Azure cloud environment.

- Networking Concepts: Setting up and configuring virtual networks, subnets, and managing IP addressing (specifically assigning static IP addresses). Understanding DNS resolution is also crucial for the client-server communication.

- Windows Server Administration: Installing and configuring the Active Directory Domain Services (AD DS) role on a Windows Server VM, promoting it to a domain controller, and managing its DNS settings.

- Client-Server Connectivity: Troubleshooting network connectivity (ping) and verifying network configurations (ipconfig /all) on a client machine.


<h2>Services Used</h2>

- Azure Virtual Machines (VMs): Used to host both the Windows Server 2022 (DC-1) and Windows 10 (Client-1) operating systems.

- Azure Virtual Network (VNet): Provides the isolated and secure network environment for the VMs to communicate.

- Azure Subnets: Logical divisions within the VNet to organize and isolate resources.

- Azure Network Interface Cards (NICs): Components attached to VMs that enable network connectivity, and where static IP addresses are configured.




<img width="1301" height="681" alt="image" src="https://github.com/user-attachments/assets/bedaff51-5075-47d1-a443-ada09ea0280a" />




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



























































































