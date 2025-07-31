# Azure--Labs-Portfolio
Hands-on Azure labs to build cloud skills and document technical projects
# Create and Configure a Virtual Machine on Azure

## Overview
This project demonstrates how to create and configure a virtual machine in Microsoft Azure using the Azure Portal. The goal is to become familiar with deploying virtual machines, setting admin credentials, and enabling RDP access.

## Tools Used
- Microsoft Azure Portal
- Azure Resource Groups
- Windows Server 2019
- Remote Desktop Protocol (RDP)
- Loom (for recording)

## Steps Performed
1. Navigated to the Azure Portal
2. Clicked on **Create a resource > Virtual Machine**
3. Selected resource group and region
4. Chose **Windows Server 2019** as the image
5. Configured admin username and password
6. Enabled RDP port 3389 for remote access
7. Clicked **Review + Create**
8. Deployed the virtual machine

## Video Demo
[Click to watch the walkthrough on Loom]  https://www.loom.com/share/9318521637bd476cb89710e5a6693a52

## Outcome
Successfully created a virtual machine and deployed it through the Azure Portal. This gave hands-on practice in basic Azure infrastructure setup.




## Project: Azure Blob Storage

### Overview
This lab demonstrates how to create a Storage Account, configure a secure Blob container, and upload a file to Azure Blob Storage.

### Steps Performed
1. Created a new Storage Account
2. Configured a private Blob Container
3. Uploaded a test file (Blob)
4. Viewed properties and access settings

### Tools Used
- Microsoft Azure Portal
- Azure Storage Account
- Blob Storage
- Loom (for video walkthrough)

### Video Demonstration
[Loom Video Link Here] https://www.loom.com/share/4b60350a230a4b49bed1ccb735402781


Title: Azure Virtual Network and Subnet Configuration

Tools Used: Azure Portal

Steps Performed:

1.Navigated to Virtual Networks → Clicked Create

2.Selected subscription, resource group

3.Named the virtual network and selected region

4.Configured address space (default: 10.0.0.0/16)

5.Added subnet ‘MySubnet’ with address range 10.0.0.0/24

6.Skipped optional security/DNS settings

7.Clicked Review + Create, then Create

8.Verified deployment and confirmed VNet and subnet created



Outcome:

Successfully deployed a basic Azure virtual network and subnet, which is foundational for networking in Azure.

### Video Demonstration
[Loom Video Link Here] https://www.loom.com/share/a5c04c1c6d584d09bd8a53adbd2cedbd






Title: Azure Active Directory Multi-Factor Authentication

Tools Used: Azure Portal, Azure AD

Steps Performed:

1.Navigated to Azure Active Directory → Users

2.Selected a user to enable MFA

3.Clicked Multi-Factor Authentication from the top menu

4.Located the user → Clicked Enable

5.Confirmed MFA enable prompt

6.Optionally clicked Enforce to require MFA setup at next login



Outcome:

Successfully enabled and enforced Multi-Factor Authentication for an Azure AD user to enhance identity security.

### Video Demonstration
[Loom Video Link Here] https://www.loom.com/share/15536070bd07447dbb46bcbbb0cdc17d?live_rewind=1






Lab Steps: Azure Policy


1.Search for “Policy” in the search bar.

2.On the left panel, click Assignments.

3.Click Assign Policy.

4.Under Basics:

Scope: Choose your Subscription or a Resource Group.

Policy definition: Click to browse and select Require a tag on resources.

5.Under Parameters, define:

Tag Name (e.g., Environment)

Tag Value (optional)

6.Click Review + Create, then Create.


### Video Demonstration
[Loom Video Link Here] https://www.loom.com/share/a94fe58cdff244a08ae64277bda1667b?live_rewind=1
