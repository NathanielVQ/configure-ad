<p align="center">
  <img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1 align="center">On-premises Active Directory Deployed in the Cloud (Azure)</h1>

<p>
This project demonstrates the deployment and configuration of an on-premises-style Active Directory environment using Microsoft Azure Virtual Machines. The lab covers setting up a domain controller, configuring Active Directory Domain Services, and joining client machines to the domain.
</p>

---

<h2>Project Summary</h2>

<p>
This tutorial outlines how to build and configure an on-premises Active Directory environment using cloud-based virtual machines in Microsoft Azure. The project includes setting up a Windows Server domain controller, configuring Active Directory Domain Services (AD DS), and connecting Windows client machines to the domain.
</p>

<h3>Languages Used</h3>

- PowerShell

<h3>Environments Used</h3>

- Microsoft Azure (Virtual Machines)
- Windows Server 2022
- Windows 10 (21H2)
- Windows 11

<h3>Technologies / Applications Used</h3>

- Active Directory Domain Services (AD DS)
- Remote Desktop
- PowerShell
- Microsoft Azure Networking

---

<h2>High-Level Deployment Steps</h2>

- Create Virtual Machines in Azure
- Configure Domain Controller (Windows Server)
- Install and Configure Active Directory Domain Services
- Join Client Machine to Domain

---

<h2>Deployment and Configuration Steps</h2>

<h3>Step 1: Create Virtual Machines in Azure</h3>

<p align="center">
  <img width="762" height="836" alt="image" src="https://github.com/user-attachments/assets/28f1b76c-4540-401d-8021-a64f1d07175c" />
</p>

<p>
The first step involves creating virtual machines in Microsoft Azure. One VM is configured as a Windows Server domain controller, and another VM is set up as a Windows 10 client machine. Both machines are placed within the same virtual network to allow communication.
</p>

<br />

<h3>Step 2: Install Active Directory Domain Services</h3>

<p align="center">
  <img width="1217" height="816" alt="image" src="https://github.com/user-attachments/assets/668d47e2-0153-4412-a189-8be2feb14b94" />
</p>

<p>
Active Directory Domain Services (AD DS) is installed on the Windows Server machine. After installation, the server is promoted to a domain controller and a new forest is created to establish the domain environment.
</p>

<br />

<h3>Step 3: Configure Domain and Users</h3>

<p align="center">
  <img width="560" height="676" alt="image" src="https://github.com/user-attachments/assets/68a5d5ae-1387-4749-b7fa-def964fea273" />
</p>

<p>
Once the domain controller is configured, users and organizational units are created within Active Directory. This allows centralized management of users, groups, and permissions within the domain.
</p>

<br />

<h3>Step 4: Join Client Machine to Domain</h3>

<p align="center">
  <img width="1100" height="855" alt="image" src="https://github.com/user-attachments/assets/133cb994-7f45-4b6d-84d8-4f0cb861a877" />
</p>

<p>
The Windows 10 client machine is joined to the newly created domain. After joining, domain users can log in and access resources managed by the domain controller.
</p>

<br />

---

<h2>Conclusion</h2>

<p>
This project successfully demonstrated how to deploy and configure an on-premises-style Active Directory environment using Microsoft Azure. The lab provided hands-on experience with domain controllers, user management, and client domain joining in a virtualized IT environment.
</p>
