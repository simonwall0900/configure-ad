<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the of Active Directory within Azure Virtual Machines.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to Deploy on-premises Active Directory within Azure Compute](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 11 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Create a Windows Server Virtual Machine in Azure
- Install the Active Directory Domain Services Role
- Promote the server to a Domain Controller
- Configure networing and join devices to the domain

<h2>Deployment and Configuration Steps</h2>

<p>
<img width="1064" height="180" alt="IMG_5036" src="https://github.com/user-attachments/assets/26d1273e-3ebb-4e68-a543-b30053bf5757" />

</p>
<p>
Azure Virtual Machines (VMs) can provide the Windows Server environment needed to host Active Directory Domain Services (AD DS). This allows organizations to deploy and manage a domain controller within the Azure cloud environment.

Purpose

Using an Azure VM for Active Directory allows IT administrators to:

Deploy a Windows Server domain controller. Manage users and computer accounts. Create and manage security groups. Organize resources using Organizational Units (OUs). Manage authentication and access to network resources. Result

Deploying Active Directory on an Azure Virtual Machine provides a cloud-based environment for managing users, computers, and access to organizational resources. This demonstrates practical experience with Azure, Windows Server, and Active Directory administration.
</p>
<br />

<p>
<img width="1092" height="644" alt="IMG_5037" src="https://github.com/user-attachments/assets/e72a5b9b-8fb4-4117-9050-b734505f1449" />

</p>
<p>
PowerShell Integrated Scripting Environment (ISE) is a graphical tool that makes it easier for IT professionals to write, edit, test, and run PowerShell commands and scripts.

When used with Active Directory, PowerShell ISE can help administrators efficiently manage user accounts, groups, and other directory resources.

Common Active Directory Tasks

PowerShell ISE can be used to perform tasks such as:

Creating and managing user accounts. Creating and managing security groups. Resetting user passwords. Managing Organizational Units (OUs). Updating user account information. Troubleshooting account-related issues. Result

Using PowerShell ISE with Active Directory provides IT professionals with an efficient way to automate and manage common administrative tasks. This helps reduce repetitive work and allows administrators to manage multiple accounts more efficiently.
</p>
<br />

<p>
<img width="1096" height="409" alt="IMG_5038" src="https://github.com/user-attachments/assets/7fc03edd-011f-4c15-869b-3fe65bed2892" />

</p>
<p>
This process demonstrates how an IT Help Desk Technician or system administrator can assist users who have forgotten their password or are unable to access their account. PowerShell ISE can be used with the Active Directory module to locate users, reset passwords, and verify account access.

Password Reset Process

Step 1: Open PowerShell ISE

Open PowerShell ISE with the appropriate administrative permissions.

Step 2: Import the Active Directory Module

Load the Active Directory PowerShell module so that Active Directory accounts can be managed through PowerShell.

Step 3: Find the User

Search for and identify the user's Active Directory account. Verify that the correct user account has been selected before making any changes.

Step 4: Reset the User Password

Use PowerShell to reset the user's password according to the organization's password requirements and security policies.

Step 5: Verify User Access

After resetting the password, verify that the user's account is active and that the user can successfully sign in.

Result

Using PowerShell ISE provides an efficient way to manage Active Directory user accounts. This process demonstrates how IT personnel can assist with password resets and account access issues while maintaining proper account management procedures.


</p>
<br />
