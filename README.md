# ⬆️ Microsoft Azure AZ-800 (Windows Server Hybrid Administrator) Practice Tests Exams Questions & Answers

![Promotional image](images/promotional.png)

## Table of Contents

### You have a server named Server1 that runs Windows Server. Server1 has the storage pools shown in the following table. You plan to create a virtual disk named VDisk1 that will use storage tiers.

![Question 1](images/question1.jpg)

- [x] Pool2 and Pool3 only.
- [ ] Pool2 only.
- [ ] Pool1 only.
- [ ] Pool1, Pool2, and Pool3.
- [ ] Pool1 and Pool2 only.
- [ ] Pool1 and Pool3 only.
- [ ] Pool3 only.

**[⬆ Back to Top](#table-of-contents)**

### Your network contains an Active Directory Domain Services (AD DS) domain named adatum.com. The domain contains a ‘He server named Server1 and three users named User1. User2 and User), Server1 contains a shared folder named Share1 that has the following configurations. The share permissions for Share1 are configured as shown in the Share Permissions exhibit. Share! contains a file named Filel.txt. The advanced security settings for Filel.txt are configured as shown in the File Permissions exhibit. When User1 connects to \\Server1.adatum.com\Share1\, the user can take ownership of File1.txt.

![Question 2 part 1](images/question2_3_4_1.jpg)
![Question 2 part 2](images/question2_3_4_2.jpg)
![Question 2 part 3](images/question2_3_4_3.jpg)

- [ ] Yes.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### Your network contains an Active Directory Domain Services (AD DS) domain named adatum.com. The domain contains a ‘He server named Server1 and three users named User1. User2 and User), Server1 contains a shared folder named Share1 that has the following configurations. The share permissions for Share1 are configured as shown in the Share Permissions exhibit. Share! contains a file named Filel.txt. The advanced security settings for Filel.txt are configured as shown in the File Permissions exhibit. When User2 connects to \\Server1.adatum.com\Share1\, File1.txt is visible.

![Question 3 part 1](images/question2_3_4_1.jpg)
![Question 3 part 2](images/question2_3_4_2.jpg)
![Question 3 part 3](images/question2_3_4_3.jpg)

- [x] Yes.
- [ ] No.

**[⬆ Back to Top](#table-of-contents)**

### Your network contains an Active Directory Domain Services (AD DS) domain named adatum.com. The domain contains a ‘He server named Server1 and three users named User1. User2 and User), Server1 contains a shared folder named Share1 that has the following configurations. The share permissions for Share1 are configured as shown in the Share Permissions exhibit. Share! contains a file named Filel.txt. The advanced security settings for Filel.txt are configured as shown in the File Permissions exhibit. When User3 connects to \\Server1.adatum.com\Share1\, File1.txt is visible.

![Question 4 part 1](images/question2_3_4_1.jpg)
![Question 4 part 2](images/question2_3_4_2.jpg)
![Question 4 part 3](images/question2_3_4_3.jpg)

- [x] Yes.
- [ ] No.

**[⬆ Back to Top](#table-of-contents)**

### Contoso, Ltd. is a company that has a main office in Seattle and two branch offices in Los Angeles and Montreal. The network contains an on premises Active Directory Domain Services (AD DS) forest named contoso.com. The forest contains two domains named contoso.com and canada.contoso.com. The forest contains the domain controllers shown in the following table. All the domain controllers are global catalog servers. The network contains the servers shown in the following table. A server named Server4 runs Windows Server and is in a workgroup. Windows Firewall on Server4 uses the private profile. Server2 hosts three virtual machines named VM1, VM2, and VM3. VM3 is a file server that stores data in the volumes shown in the following table. The contoso.com domain has the Group Policies Objects (GPOs) shown in the following table. The forest contains the users shown in the following table. The forest contains the groups shown in the following table. When an administrator signs in to the console of VM2 by using Virtual Machine Connection, and then disconnects from the session without signing out, another administrator can connect to the console session as the currently signed in user. Contoso identifies the following technical requirements: Change the replication schedule for all site links to 30 minutes. Promote Server1 to a domain controller in canada.contoso.com. Install and authorize Server3 as a DHCP server. Ensure that User1 can manage the membership of all the groups in Contoso\OU3. Ensure that you can manage Server4 from Server1 by using PowerShell remoting. Ensure that you can run virtual machines on VM1. Force users to provide credentials when they connect to VM2. On VM3, ensure that Data Deduplication on all volumes is possible. You need to meet the technical requirements for the site links. Which users can perform the required tasks?

![Question 5 part 1](images/question5_8_9_20_33_38_39_43_1.jpg)
![Question 5 part 2](images/question5_8_9_20_33_38_39_43_2.jpg)
![Question 5 part 3](images/question5_8_9_20_33_38_39_43_3.jpg)
![Question 5 part 4](images/question5_8_9_20_33_38_39_43_4.jpg)
![Question 5 part 5](images/question5_8_9_20_33_38_39_43_5.jpg)
![Question 5 part 6](images/question5_8_9_20_33_38_39_43_6.jpg)

- [x] Admin1 only.
- [ ] Admin1 and Admin3 only.
- [ ] Admin1 and Admin2 only.
- [ ] Admin3 only.
- [ ] Admin1, Adrrun2. and Admin3.

**[⬆ Back to Top](#table-of-contents)**

### You have a server named Server1 that hosts Windows containers. You plan to deploy an application that will have multiple containers. Each container will be You need to create a Docker network that supports the deployment of the application. Which type of network should you create?

- [x] transparent.
- [ ] I2bridge.
- [ ] NAT.
- [ ] I2tunnel.

**[⬆ Back to Top](#table-of-contents)**

### Fabrikam, Inc is a manufacturing company that has a main office in New York and a branch office in Seattle. The on-premises network contains servers that run Windows Server as shown in the following table. DC1 hosts all the operation master roles. VM1 and VM2 are connected to the internet. WEB1 and WEB2 run an Internet Information Services (IIS) web app named Webapp1. The New York and Seattle offices are connected by using redundant WAN links. The client computers in each office get IP addresses from their local DHCP server. DHCP1 contains a scope named Scope1 that has addresses for the New York office, DHCP2 contains a scope named Scope2 that has addresses for the Seattle office. The network contains a single on-premises Active Directory Domain Services (AD DS) domain named corp.falbrikam.com. Currently, all the service accounts use individual domain user accounts. All domain controllers have the DNS Server role installed and host a copy of the Active Directory integrated DNS zone of corp.fabrikam.com. The corp.fabrikam.com AD DS domain syncs with an Azure Active Directory (Azure AD) tenant. The corp.fabrikam.com domain contains the organizational units (OUs) and custom Group Policy Objects (GPOs) shown in the following table. Fabrikam identifies the following planned changes: Create a single Azure subscription named Sub1 that will contain a single Azure virtual network named Vnet1. Replace the WAN links between the Seattle and New York offices by using Azure Virtual WAN and FxpressRoute. Both on premises offices will be connected to Vnet1 by using ExpressRoute. Create three Azure file shares named newyorkfiles, seattlefiles, and companyfiles. Create a domain controller named dc3.corp.fabrikam.com in Vnet1. Deploy an Azure Virtual Desktop host pool to Vnet1. The Azure Virtual Desktop session hosts will be hybrid Azure AD-joined. License all servers for Microsoft Defender for servers. Use Azure Policy to enforce configuration management policies on the servers in Azure and on-premises. Fabrikam identifies the following networking requirements: Implement Virtual WAN and ensure that all the network traffic between the sites uses Virtual WAN. All communications must occur over ExpressRoute. If a DHCP server fails, ensure that the client computers can continue to receive their dynamic IP address and renew their existing lease. Ensure that the resources in Vnet1 can resolve the names of the on-premises servers in the corp.fabrikam.com domain. Fabrikam identifies the following security requirements: Apply GPO4 to the Azure Virtual Desktop session hosts. Ensure that Azure Virtual Desktop user sessions lock after being idle for 10 minutes. Users must be able to control the lockout time manually from their client computer. Ensure that server administrators request approval before they can establish a Remote Desktop connection to an Azure virtual machine. If the request is approved, the connection must be established within two hours. Prevent user passwords from containing all or part of words that are based on the company name, such as Fab, f@br1kAm or fabr!|. Ensure that all instances of Webapp1 use the same service account. The password of the service account must change automatically every 30 days. Prevent domain controllers from directly contacting hosts on the internet. You need to configure the synchronization of Azure files to meet the following requirements: Ensure that seattlefiles syncs to FS2. Ensure that newyorkfiles syncs to FS1. Ensure that companyfiles syncs to both FS1 and FS2. You need to configure remote administration to meet the security requirements. What should you use?

![Question 7 part 1](images/question7_16_17_19_22_29_45_1.jpg)
![Question 7 part 2](images/question7_16_17_19_22_29_45_2.jpg)

- [x] Just in time (JIT) VM access.
- [ ] Azure AD Privileged Identity Management (PIM).
- [ ] Remote Desktop extension for Azure Cloud Services.
- [ ] Azure Bastion host.

**[⬆ Back to Top](#table-of-contents)**

### Contoso, Ltd. is a company that has a main office in Seattle and two branch offices in Los Angeles and Montreal. The network contains an on premises Active Directory Domain Services (AD DS) forest named contoso.com. The forest contains two domains named contoso.com and canada.contoso.com. The forest contains the domain controllers shown in the following table. All the domain controllers are global catalog servers. The network contains the servers shown in the following table. A server named Server4 runs Windows Server and is in a workgroup. Windows Firewall on Server4 uses the private profile. Server2 hosts three virtual machines named VM1, VM2, and VM3. VM3 is a file server that stores data in the volumes shown in the following table. The contoso.com domain has the Group Policies Objects (GPOs) shown in the following table. The forest contains the users shown in the following table. The forest contains the groups shown in the following table. When an administrator signs in to the console of VM2 by using Virtual Machine Connection, and then disconnects from the session without signing out, another administrator can connect to the console session as the currently signed in user. Contoso identifies the following technical requirements: Change the replication schedule for all site links to 30 minutes. Promote Server1 to a domain controller in canada.contoso.com. Install and authorize Server3 as a DHCP server. Ensure that User1 can manage the membership of all the groups in Contoso\OU3. Ensure that you can manage Server4 from Server1 by using PowerShell remoting. Ensure that you can run virtual machines on VM1. Force users to provide credentials when they connect to VM2. On VM3, ensure that Data Deduplication on all volumes is possible. Admin1 must use a password that has at least 14 characters.

![Question 8 part 1](images/question5_8_9_20_33_38_39_43_1.jpg)
![Question 8 part 2](images/question5_8_9_20_33_38_39_43_2.jpg)
![Question 8 part 3](images/question5_8_9_20_33_38_39_43_3.jpg)
![Question 8 part 4](images/question5_8_9_20_33_38_39_43_4.jpg)
![Question 8 part 5](images/question5_8_9_20_33_38_39_43_5.jpg)
![Question 8 part 6](images/question5_8_9_20_33_38_39_43_6.jpg)

- [ ] Yes.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### Contoso, Ltd. is a company that has a main office in Seattle and two branch offices in Los Angeles and Montreal. The network contains an on premises Active Directory Domain Services (AD DS) forest named contoso.com. The forest contains two domains named contoso.com and canada.contoso.com. The forest contains the domain controllers shown in the following table. All the domain controllers are global catalog servers. The network contains the servers shown in the following table. A server named Server4 runs Windows Server and is in a workgroup. Windows Firewall on Server4 uses the private profile. Server2 hosts three virtual machines named VM1, VM2, and VM3. VM3 is a file server that stores data in the volumes shown in the following table. The contoso.com domain has the Group Policies Objects (GPOs) shown in the following table. The forest contains the users shown in the following table. The forest contains the groups shown in the following table. When an administrator signs in to the console of VM2 by using Virtual Machine Connection, and then disconnects from the session without signing out, another administrator can connect to the console session as the currently signed in user. Contoso identifies the following technical requirements: Change the replication schedule for all site links to 30 minutes. Promote Server1 to a domain controller in canada.contoso.com. Install and authorize Server3 as a DHCP server. Ensure that User1 can manage the membership of all the groups in Contoso\OU3. Ensure that you can manage Server4 from Server1 by using PowerShell remoting. Ensure that you can run virtual machines on VM1. Force users to provide credentials when they connect to VM2. On VM3, ensure that Data Deduplication on all volumes is possible. User1 must use a password that has at least 10 characters.

![Question 9 part 1](images/question5_8_9_20_33_38_39_43_1.jpg)
![Question 9 part 2](images/question5_8_9_20_33_38_39_43_2.jpg)
![Question 9 part 3](images/question5_8_9_20_33_38_39_43_3.jpg)
![Question 9 part 4](images/question5_8_9_20_33_38_39_43_4.jpg)
![Question 9 part 5](images/question5_8_9_20_33_38_39_43_5.jpg)
![Question 9 part 6](images/question5_8_9_20_33_38_39_43_6.jpg)

- [x] Yes.
- [ ] No.

**[⬆ Back to Top](#table-of-contents)**

### If Admin1 creates a new local user on Server1 the password for the new user must be at least eight characters.

- [ ] Yes.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### You have an Azure virtual machine named VM1 that runs Windows Server. You need to configure the management of VM1 to meet the following requirements: Require administrators to request access to VM1 before establishing a Remote Desktop connection. Limit access to VM1 from specific source IP addresses. Limit access to VMI to a specific management port. What should you configure?

- [ ] Network Security Group (NSG).
- [ ] Azure Active Directory (Azure AD) Privileged identity Management (PIM).
- [ ] Azure Front Door.
- [x] Microsoft Defender for Cloud.

**[⬆ Back to Top](#table-of-contents)**

### You plan to deploy a containerized application that requires .NET Core. You need to create a container image for the application. The image must be as small as possible. Which base image should you use?

- [x] Nano Server.
- [ ] Server Cote.
- [ ] Windows Server.
- [ ] Windows.

**[⬆ Back to Top](#table-of-contents)**

### You need to configure Azure File Sync to meet the file sharing requirements. What should you do?

![Question 13](images/question13.jpg)

- [ ] Minimum number of sync groups to create: 2. Minimum number of Storage Sync Services to create: 2.
- [ ] Minimum number of sync groups to create: 1. Minimum number of Storage Sync Services to create: 3.
- [x] Minimum number of sync groups to create: 3. Minimum number of Storage Sync Services to create: 1.
- [ ] Minimum number of sync groups to create: 2. Minimum number of Storage Sync Services to create: 4.

**[⬆ Back to Top](#table-of-contents)**

### You need to implement an availability solution for DHCP that meets the networking requirements. Which two actions should you perform?

- [ ] On DHCP1. create a scope that contains 25 percent of the IP addresses from Scope2.
- [x] On the router in each office, configure a DHCP relay.
- [ ] DHCP2. configure a scope that contains 25 percent of the IP addresses from Scope 1.
- [ ] On each DHCP server, install the Failover Clustering feature and add the DHCP cluster role.
- [x] On each DHCP scope, configure DHCP failover.

**[⬆ Back to Top](#table-of-contents)**

### You have a server named Host! that has the Hyper-V server role installed. Host! hosts a virtual machine named VM1. You have a management server named Server! that runs Windows Server. You remotely manage Host1 from Server1 by using Hyper-V Manager. You need to ensure that you can access a USB hard drive connected to Server1 when you connect to VM1 by using Virtual Machine Connection. Which two actions should you perform?

- [x] From the Hyper-V Settings of Host1, select Allow enhanced session mode.
- [ ] From Disk Management on Host1. attach a virtual hard disk.
- [ ] From Virtual Machine Connection, switch to a basic session.
- [x] From Virtual Machine Connection select Show Options and then select the USB hard drive.
- [ ] From Disk Management on Host1, select Rescan Disks.

**[⬆ Back to Top](#table-of-contents)**

### Fabrikam, Inc is a manufacturing company that has a main office in New York and a branch office in Seattle. The on-premises network contains servers that run Windows Server as shown in the following table. DC1 hosts all the operation master roles. VM1 and VM2 are connected to the internet. WEB1 and WEB2 run an Internet Information Services (IIS) web app named Webapp1. The New York and Seattle offices are connected by using redundant WAN links. The client computers in each office get IP addresses from their local DHCP server. DHCP1 contains a scope named Scope1 that has addresses for the New York office, DHCP2 contains a scope named Scope2 that has addresses for the Seattle office. The network contains a single on-premises Active Directory Domain Services (AD DS) domain named corp.falbrikam.com. Currently, all the service accounts use individual domain user accounts. All domain controllers have the DNS Server role installed and host a copy of the Active Directory integrated DNS zone of corp.fabrikam.com. The corp.fabrikam.com AD DS domain syncs with an Azure Active Directory (Azure AD) tenant. The corp.fabrikam.com domain contains the organizational units (OUs) and custom Group Policy Objects (GPOs) shown in the following table. Fabrikam identifies the following planned changes: Create a single Azure subscription named Sub1 that will contain a single Azure virtual network named Vnet1. Replace the WAN links between the Seattle and New York offices by using Azure Virtual WAN and FxpressRoute. Both on premises offices will be connected to Vnet1 by using ExpressRoute. Create three Azure file shares named newyorkfiles, seattlefiles, and companyfiles. Create a domain controller named dc3.corp.fabrikam.com in Vnet1. Deploy an Azure Virtual Desktop host pool to Vnet1. The Azure Virtual Desktop session hosts will be hybrid Azure AD-joined. License all servers for Microsoft Defender for servers. Use Azure Policy to enforce configuration management policies on the servers in Azure and on-premises. Fabrikam identifies the following networking requirements: Implement Virtual WAN and ensure that all the network traffic between the sites uses Virtual WAN. All communications must occur over ExpressRoute. If a DHCP server fails, ensure that the client computers can continue to receive their dynamic IP address and renew their existing lease. Ensure that the resources in Vnet1 can resolve the names of the on-premises servers in the corp.fabrikam.com domain. Fabrikam identifies the following security requirements: Apply GPO4 to the Azure Virtual Desktop session hosts. Ensure that Azure Virtual Desktop user sessions lock after being idle for 10 minutes. Users must be able to control the lockout time manually from their client computer. Ensure that server administrators request approval before they can establish a Remote Desktop connection to an Azure virtual machine. If the request is approved, the connection must be established within two hours. Prevent user passwords from containing all or part of words that are based on the company name, such as Fab, f@br1kAm or fabr!|. Ensure that all instances of Webapp1 use the same service account. The password of the service account must change automatically every 30 days. Prevent domain controllers from directly contacting hosts on the internet. You need to configure the synchronization of Azure files to meet the following requirements: Ensure that seattlefiles syncs to FS2. Ensure that newyorkfiles syncs to FS1. Ensure that companyfiles syncs to both FS1 and FS2. What should you implement for the deployment of DC3?

![Question 16 part 1](images/question7_16_17_19_22_29_45_1.jpg)
![Question 16 part 2](images/question7_16_17_19_22_29_45_2.jpg)

- [ ] Azure Active Directory Domain Services (Azure AD DS).
- [ ] Azure AD Application Proxy.
- [x] Azure virtual machine.
- [ ] Azure AD administrative unit.

**[⬆ Back to Top](#table-of-contents)**

### Fabrikam, Inc is a manufacturing company that has a main office in New York and a branch office in Seattle. The on-premises network contains servers that run Windows Server as shown in the following table. DC1 hosts all the operation master roles. VM1 and VM2 are connected to the internet. WEB1 and WEB2 run an Internet Information Services (IIS) web app named Webapp1. The New York and Seattle offices are connected by using redundant WAN links. The client computers in each office get IP addresses from their local DHCP server. DHCP1 contains a scope named Scope1 that has addresses for the New York office, DHCP2 contains a scope named Scope2 that has addresses for the Seattle office. The network contains a single on-premises Active Directory Domain Services (AD DS) domain named corp.falbrikam.com. Currently, all the service accounts use individual domain user accounts. All domain controllers have the DNS Server role installed and host a copy of the Active Directory integrated DNS zone of corp.fabrikam.com. The corp.fabrikam.com AD DS domain syncs with an Azure Active Directory (Azure AD) tenant. The corp.fabrikam.com domain contains the organizational units (OUs) and custom Group Policy Objects (GPOs) shown in the following table. Fabrikam identifies the following planned changes: Create a single Azure subscription named Sub1 that will contain a single Azure virtual network named Vnet1. Replace the WAN links between the Seattle and New York offices by using Azure Virtual WAN and FxpressRoute. Both on premises offices will be connected to Vnet1 by using ExpressRoute. Create three Azure file shares named newyorkfiles, seattlefiles, and companyfiles. Create a domain controller named dc3.corp.fabrikam.com in Vnet1. Deploy an Azure Virtual Desktop host pool to Vnet1. The Azure Virtual Desktop session hosts will be hybrid Azure AD-joined. License all servers for Microsoft Defender for servers. Use Azure Policy to enforce configuration management policies on the servers in Azure and on-premises. Fabrikam identifies the following networking requirements: Implement Virtual WAN and ensure that all the network traffic between the sites uses Virtual WAN. All communications must occur over ExpressRoute. If a DHCP server fails, ensure that the client computers can continue to receive their dynamic IP address and renew their existing lease. Ensure that the resources in Vnet1 can resolve the names of the on-premises servers in the corp.fabrikam.com domain. Fabrikam identifies the following security requirements: Apply GPO4 to the Azure Virtual Desktop session hosts. Ensure that Azure Virtual Desktop user sessions lock after being idle for 10 minutes. Users must be able to control the lockout time manually from their client computer. Ensure that server administrators request approval before they can establish a Remote Desktop connection to an Azure virtual machine. If the request is approved, the connection must be established within two hours. Prevent user passwords from containing all or part of words that are based on the company name, such as Fab, f@br1kAm or fabr!|. Ensure that all instances of Webapp1 use the same service account. The password of the service account must change automatically every 30 days. Prevent domain controllers from directly contacting hosts on the internet. You need to configure the synchronization of Azure files to meet the following requirements: Ensure that seattlefiles syncs to FS2. Ensure that newyorkfiles syncs to FS1. Ensure that companyfiles syncs to both FS1 and FS2. You need to meet the security requirements for passwords. Where should you configure the components for Azure AD Password Protection?

![Question 17 part 1](images/question7_16_17_19_22_29_45_1.jpg)
![Question 17 part 2](images/question7_16_17_19_22_29_45_2.jpg)
![Question 17 part 3](images/question17_3.jpg)

- [x] The Azure AD Password Protection DC agent: All the domain controllers. The Azure AD Password Protection proxy service: VM1 and VM2. A custom banned password list: The Azure AD tenant.
- [ ] The Azure AD Password Protection DC agent: DC1 only. The Azure AD Password Protection proxy service: The Azure AD tenant. A custom banned password list: VM1 and VM2.
- [ ] The Azure AD Password Protection DC agent: VM1 and VM2. The Azure AD Password Protection proxy service: All the domain controllers. A custom banned password list: DC1 only.
- [ ] The Azure AD Password Protection DC agent: All the domain controllers. The Azure AD Password Protection proxy service: The Azure AD tenant. A custom banned password list: VM1 and VM2.

**[⬆ Back to Top](#table-of-contents)**

### You have an Azure virtual machine named VM1 that runs Windows Server. You perform the following actions on VM1: Create a folder named Folder1 on volume C. Create a folder named Folder2 on volume D. Add a new data disk to VM1 and create a new volume that is assigned drive letter E. Install an app named App1 on volume E. You plan to resize VM1. Which objects will present after you resize VM1?

- [ ] Folder1 and Folder2 only.
- [x] Folder1, volume E, and App1 only.
- [ ] Folder1 only.
- [ ] Folder1, Folder2, App1, and volume E.

**[⬆ Back to Top](#table-of-contents)**

### Fabrikam, Inc is a manufacturing company that has a main office in New York and a branch office in Seattle. The on-premises network contains servers that run Windows Server as shown in the following table. DC1 hosts all the operation master roles. VM1 and VM2 are connected to the internet. WEB1 and WEB2 run an Internet Information Services (IIS) web app named Webapp1. The New York and Seattle offices are connected by using redundant WAN links. The client computers in each office get IP addresses from their local DHCP server. DHCP1 contains a scope named Scope1 that has addresses for the New York office, DHCP2 contains a scope named Scope2 that has addresses for the Seattle office. The network contains a single on-premises Active Directory Domain Services (AD DS) domain named corp.falbrikam.com. Currently, all the service accounts use individual domain user accounts. All domain controllers have the DNS Server role installed and host a copy of the Active Directory integrated DNS zone of corp.fabrikam.com. The corp.fabrikam.com AD DS domain syncs with an Azure Active Directory (Azure AD) tenant. The corp.fabrikam.com domain contains the organizational units (OUs) and custom Group Policy Objects (GPOs) shown in the following table. Fabrikam identifies the following planned changes: Create a single Azure subscription named Sub1 that will contain a single Azure virtual network named Vnet1. Replace the WAN links between the Seattle and New York offices by using Azure Virtual WAN and FxpressRoute. Both on premises offices will be connected to Vnet1 by using ExpressRoute. Create three Azure file shares named newyorkfiles, seattlefiles, and companyfiles. Create a domain controller named dc3.corp.fabrikam.com in Vnet1. Deploy an Azure Virtual Desktop host pool to Vnet1. The Azure Virtual Desktop session hosts will be hybrid Azure AD-joined. License all servers for Microsoft Defender for servers. Use Azure Policy to enforce configuration management policies on the servers in Azure and on-premises. Fabrikam identifies the following networking requirements: Implement Virtual WAN and ensure that all the network traffic between the sites uses Virtual WAN. All communications must occur over ExpressRoute. If a DHCP server fails, ensure that the client computers can continue to receive their dynamic IP address and renew their existing lease. Ensure that the resources in Vnet1 can resolve the names of the on-premises servers in the corp.fabrikam.com domain. Fabrikam identifies the following security requirements: Apply GPO4 to the Azure Virtual Desktop session hosts. Ensure that Azure Virtual Desktop user sessions lock after being idle for 10 minutes. Users must be able to control the lockout time manually from their client computer. Ensure that server administrators request approval before they can establish a Remote Desktop connection to an Azure virtual machine. If the request is approved, the connection must be established within two hours. Prevent user passwords from containing all or part of words that are based on the company name, such as Fab, f@br1kAm or fabr!|. Ensure that all instances of Webapp1 use the same service account. The password of the service account must change automatically every 30 days. Prevent domain controllers from directly contacting hosts on the internet. You need to configure the synchronization of Azure files to meet the following requirements: Ensure that seattlefiles syncs to FS2. Ensure that newyorkfiles syncs to FS1. Ensure that companyfiles syncs to both FS1 and FS2. Which three actions should you perform in sequence to meet the security requirements for Webapp1?

![Question 19 part 1](images/question7_16_17_19_22_29_45_1.jpg)
![Question 19 part 2](images/question7_16_17_19_22_29_45_2.jpg)
![Question 19 part 3](images/question19_3.jpeg)

- [ ] Box 1: Configure the IIS application pool to run as Network Service. Box 2: Create a group managed service account (gMSA) in Active Directory. Box 3: Create the Key Distribution Services (KDS) root key in AD DS.
- [x] Box 1: Create the Key Distribution Services (KDS) root key in AD DS. Box 2: Create a group managed service account (gMSA) in Active Directory. Box 3: Configure the IIS application pool to run as Network Service.
- [ ] Box 1: Create a standalone managed service account (sMSA) in AD DS. Box 2: Create a group managed service account (gMSA) in Active Directory. Box 3: Configure the IIS application pool to run as Network Service.
- [ ] Box 1: Create a system-assigned managed identity in Azure AD. Box 2: Create a group managed service account (gMSA) in Active Directory. Box 3: Create the Key Distribution Services (KDS) root key in AD DS.

**[⬆ Back to Top](#table-of-contents)**

### Contoso, Ltd. is a company that has a main office in Seattle and two branch offices in Los Angeles and Montreal. The network contains an on premises Active Directory Domain Services (AD DS) forest named contoso.com. The forest contains two domains named contoso.com and canada.contoso.com. The forest contains the domain controllers shown in the following table. All the domain controllers are global catalog servers. The network contains the servers shown in the following table. A server named Server4 runs Windows Server and is in a workgroup. Windows Firewall on Server4 uses the private profile. Server2 hosts three virtual machines named VM1, VM2, and VM3. VM3 is a file server that stores data in the volumes shown in the following table. The contoso.com domain has the Group Policies Objects (GPOs) shown in the following table. The forest contains the users shown in the following table. The forest contains the groups shown in the following table. When an administrator signs in to the console of VM2 by using Virtual Machine Connection, and then disconnects from the session without signing out, another administrator can connect to the console session as the currently signed in user. Contoso identifies the following technical requirements: Change the replication schedule for all site links to 30 minutes. Promote Server1 to a domain controller in canada.contoso.com. Install and authorize Server3 as a DHCP server. Ensure that User1 can manage the membership of all the groups in Contoso\OU3. Ensure that you can manage Server4 from Server1 by using PowerShell remoting. Ensure that you can run virtual machines on VM1. Force users to provide credentials when they connect to VM2. On VM3, ensure that Data Deduplication on all volumes is possible. You need to meet the technical requirements for Server4. Which cmdlets should you run on Server1 and Server4?

![Question 20 part 1](images/question5_8_9_20_33_38_39_43_1.jpg)
![Question 20 part 2](images/question5_8_9_20_33_38_39_43_2.jpg)
![Question 20 part 3](images/question5_8_9_20_33_38_39_43_3.jpg)
![Question 20 part 4](images/question5_8_9_20_33_38_39_43_4.jpg)
![Question 20 part 5](images/question5_8_9_20_33_38_39_43_5.jpg)
![Question 20 part 6](images/question5_8_9_20_33_38_39_43_6.jpg)
![Question 20 part 7](images/question20_7.jpg)

- [ ] Server1: Enable-ServerManagerStandardUserRemoting. Server4: Enable-PSRemoting.
- [ ] Server1: Enable-PSRemoting. Server4: Enable-ServerManagerStandardUserRemoting.
- [ ] Server1: Set-Item. Server4: Enable-PSRemoting.
- [x] Server1: Start-Service. Server4: Enable-PSRemoting.

**[⬆ Back to Top](#table-of-contents)**

### You have a file server named Server1 that runs Windows Server and contains the volumes shown in the following table. On which volumes can you use BitLocker Drive Encryption (BitLocker) and disk quotas?

![Question 21 part 1](images/question21_1.jpg)
![Question 21 part 2](images/question21_2.jpg)

- [ ] BitLocker: C, D, and E. Disk quotas: C and D only.
- [ ] BitLocker: C and D only. Disk quotas: C, D, and E.
- [ ] BitLocker: C only. Disk quotas: D only.
- [ ] BitLocker: D only. Disk quotas: C only.

**[⬆ Back to Top](#table-of-contents)**

### Fabrikam, Inc is a manufacturing company that has a main office in New York and a branch office in Seattle. The on-premises network contains servers that run Windows Server as shown in the following table. DC1 hosts all the operation master roles. VM1 and VM2 are connected to the internet. WEB1 and WEB2 run an Internet Information Services (IIS) web app named Webapp1. The New York and Seattle offices are connected by using redundant WAN links. The client computers in each office get IP addresses from their local DHCP server. DHCP1 contains a scope named Scope1 that has addresses for the New York office, DHCP2 contains a scope named Scope2 that has addresses for the Seattle office. The network contains a single on-premises Active Directory Domain Services (AD DS) domain named corp.falbrikam.com. Currently, all the service accounts use individual domain user accounts. All domain controllers have the DNS Server role installed and host a copy of the Active Directory integrated DNS zone of corp.fabrikam.com. The corp.fabrikam.com AD DS domain syncs with an Azure Active Directory (Azure AD) tenant. The corp.fabrikam.com domain contains the organizational units (OUs) and custom Group Policy Objects (GPOs) shown in the following table. Fabrikam identifies the following planned changes: Create a single Azure subscription named Sub1 that will contain a single Azure virtual network named Vnet1. Replace the WAN links between the Seattle and New York offices by using Azure Virtual WAN and FxpressRoute. Both on premises offices will be connected to Vnet1 by using ExpressRoute. Create three Azure file shares named newyorkfiles, seattlefiles, and companyfiles. Create a domain controller named dc3.corp.fabrikam.com in Vnet1. Deploy an Azure Virtual Desktop host pool to Vnet1. The Azure Virtual Desktop session hosts will be hybrid Azure AD-joined. License all servers for Microsoft Defender for servers. Use Azure Policy to enforce configuration management policies on the servers in Azure and on-premises. Fabrikam identifies the following networking requirements: Implement Virtual WAN and ensure that all the network traffic between the sites uses Virtual WAN. All communications must occur over ExpressRoute. If a DHCP server fails, ensure that the client computers can continue to receive their dynamic IP address and renew their existing lease. Ensure that the resources in Vnet1 can resolve the names of the on-premises servers in the corp.fabrikam.com domain. Fabrikam identifies the following security requirements: Apply GPO4 to the Azure Virtual Desktop session hosts. Ensure that Azure Virtual Desktop user sessions lock after being idle for 10 minutes. Users must be able to control the lockout time manually from their client computer. Ensure that server administrators request approval before they can establish a Remote Desktop connection to an Azure virtual machine. If the request is approved, the connection must be established within two hours. Prevent user passwords from containing all or part of words that are based on the company name, such as Fab, f@br1kAm or fabr!|. Ensure that all instances of Webapp1 use the same service account. The password of the service account must change automatically every 30 days. Prevent domain controllers from directly contacting hosts on the internet. You need to configure the synchronization of Azure files to meet the following requirements: Ensure that seattlefiles syncs to FS2. Ensure that newyorkfiles syncs to FS1. Ensure that companyfiles syncs to both FS1 and FS2. You need to configure the Group Policy settings to ensure that the Azure Virtual Desktop session hosts meet the security requirements. What should you configure?

![Question 22 part 1](images/question7_16_17_19_22_29_45_1.jpg)
![Question 22 part 2](images/question7_16_17_19_22_29_45_2.jpg)

- [ ] Security filtering for the link of GP04.
- [ ] Security filtering for the link of GPO1.
- [x] Loopback processing in GPO4.
- [ ] Enforced property for the link of GP01.
- [ ] Loopback processing in GPO1.
- [ ] Enforced property for the link of GP04.

**[⬆ Back to Top](#table-of-contents)**

### You have two on-premises servers named Server1 and Servet2 that run Windows Server. You have an Azure Storage account named storage1 that contains a file share named share. Server1 syncs with share1 by using Azure File Sync You need to configure Server2 to sync with share1. Which three actions should you perform in sequence?

![Question 23](images/question23.jpeg)

- [ ] Box 1: Add a Storage Sync Service to the Azure Subscription. Box 2: Add a server endpoint to the sync group. Box 3: On Server2, install the Azure File Sync agent.
- [ ] Box 1: Add a server endpoint to the sync group. Box 2: On Server2, install the Azure File Sync agent. Box 3: Add a cloud endpoint to the sync group.
- [ ] Box 1: On Server2, install the Azure File Sync agent. Box 2: Add a cloud endpoint to the sync group. Box 3: Register Server2 with the Storage Sync Service.
- [x] Box 1: On Server2, install the Azure File Sync agent. Box 2: Register Server2 with the Storage Sync Service. Box 3: Add a server endpoint to the sync group.

**[⬆ Back to Top](#table-of-contents)**

### Which groups can you add to Group3 and Group5?

![Question 24](images/question24.jpg)

- [ ] Group3: Group1 and Group2 only. Group5: Group4 only.
- [ ] Group3: Group1 and Group4 only. Group5: Group6 only.
- [x] Group3: Group1, Group2, Group4, and Group5 only. Group5: Group4 only.
- [ ] Group3: Group6 only. Group5: Group4 and Group6 only.

**[⬆ Back to Top](#table-of-contents)**

### You have five tile servers that run Windows Server. You need to block users from uploading video files that have the .mov extension to shared folders on the file servers. All other types of files must be allowed. The solution must minimize administrative effort. What should you create?

- [ ] Dynamic Access Control central access policy.
- [x] File screen.
- [ ] Dynamic Access Control central access rule.
- [ ] Data loss prevention (DLP) policy.

**[⬆ Back to Top](#table-of-contents)**

### Your network contains an Active Directory Domain Services (AD DS) domain named adatum.com. The domain contains a server named Server1 and the users shown in the following table. Server1 contains a folder named D:Folder1. The advanced security settings for Folder 1 are configured as shown in the Permissions exhibit. Folder1 is shared by using the following configurations. The share permissions for Share1 are shown in the following table. User1 can read the files in Share1.

![Question 26 part 1](images/question26_27_28_1.jpg)
![Question 26 part 2](images/question26_27_28_2.png)
![Question 26 part 3](images/question26_27_28_3.png)
![Question 26 part 4](images/question26_27_28_4.png)

- [x] Yes.
- [ ] No.

**[⬆ Back to Top](#table-of-contents)**

### Your network contains an Active Directory Domain Services (AD DS) domain named adatum.com. The domain contains a server named Server1 and the users shown in the following table. Server1 contains a folder named D:Folder1. The advanced security settings for Folder 1 are configured as shown in the Permissions exhibit. Folder1 is shared by using the following configurations. The share permissions for Share1 are shown in the following table. User3 can delete files in Share1.

![Question 27 part 1](images/question26_27_28_1.jpg)
![Question 27 part 2](images/question26_27_28_2.png)
![Question 27 part 3](images/question26_27_28_3.png)
![Question 27 part 4](images/question26_27_28_4.png)

- [ ] Yes.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### Your network contains an Active Directory Domain Services (AD DS) domain named adatum.com. The domain contains a server named Server1 and the users shown in the following table. Server1 contains a folder named D:Folder1. The advanced security settings for Folder 1 are configured as shown in the Permissions exhibit. Folder1 is shared by using the following configurations. The share permissions for Share1 are shown in the following table. If User2 connects to \\Server1.adatum.com from File Explorer, Share1 will be listed.

![Question 28 part 1](images/question26_27_28_1.jpg)
![Question 28 part 2](images/question26_27_28_2.png)
![Question 28 part 3](images/question26_27_28_3.png)
![Question 28 part 4](images/question26_27_28_4.png)

- [x] Yes.
- [ ] No.

**[⬆ Back to Top](#table-of-contents)**

### Fabrikam, Inc is a manufacturing company that has a main office in New York and a branch office in Seattle. The on-premises network contains servers that run Windows Server as shown in the following table. DC1 hosts all the operation master roles. VM1 and VM2 are connected to the internet. WEB1 and WEB2 run an Internet Information Services (IIS) web app named Webapp1. The New York and Seattle offices are connected by using redundant WAN links. The client computers in each office get IP addresses from their local DHCP server. DHCP1 contains a scope named Scope1 that has addresses for the New York office, DHCP2 contains a scope named Scope2 that has addresses for the Seattle office. The network contains a single on-premises Active Directory Domain Services (AD DS) domain named corp.falbrikam.com. Currently, all the service accounts use individual domain user accounts. All domain controllers have the DNS Server role installed and host a copy of the Active Directory integrated DNS zone of corp.fabrikam.com. The corp.fabrikam.com AD DS domain syncs with an Azure Active Directory (Azure AD) tenant. The corp.fabrikam.com domain contains the organizational units (OUs) and custom Group Policy Objects (GPOs) shown in the following table. Fabrikam identifies the following planned changes: Create a single Azure subscription named Sub1 that will contain a single Azure virtual network named Vnet1. Replace the WAN links between the Seattle and New York offices by using Azure Virtual WAN and FxpressRoute. Both on premises offices will be connected to Vnet1 by using ExpressRoute. Create three Azure file shares named newyorkfiles, seattlefiles, and companyfiles. Create a domain controller named dc3.corp.fabrikam.com in Vnet1. Deploy an Azure Virtual Desktop host pool to Vnet1. The Azure Virtual Desktop session hosts will be hybrid Azure AD-joined. License all servers for Microsoft Defender for servers. Use Azure Policy to enforce configuration management policies on the servers in Azure and on-premises. Fabrikam identifies the following networking requirements: Implement Virtual WAN and ensure that all the network traffic between the sites uses Virtual WAN. All communications must occur over ExpressRoute. If a DHCP server fails, ensure that the client computers can continue to receive their dynamic IP address and renew their existing lease. Ensure that the resources in Vnet1 can resolve the names of the on-premises servers in the corp.fabrikam.com domain. Fabrikam identifies the following security requirements: Apply GPO4 to the Azure Virtual Desktop session hosts. Ensure that Azure Virtual Desktop user sessions lock after being idle for 10 minutes. Users must be able to control the lockout time manually from their client computer. Ensure that server administrators request approval before they can establish a Remote Desktop connection to an Azure virtual machine. If the request is approved, the connection must be established within two hours. Prevent user passwords from containing all or part of words that are based on the company name, such as Fab, f@br1kAm or fabr!|. Ensure that all instances of Webapp1 use the same service account. The password of the service account must change automatically every 30 days. Prevent domain controllers from directly contacting hosts on the internet. You need to configure the synchronization of Azure files to meet the following requirements: Ensure that seattlefiles syncs to FS2. Ensure that newyorkfiles syncs to FS1. Ensure that companyfiles syncs to both FS1 and FS2. You are planning the implementation Azure Arc to support the planned changes. You need to configure the environment to support configuration management policies. What should you do?

![Question 29 part 1](images/question7_16_17_19_22_29_45_1.jpg)
![Question 29 part 2](images/question7_16_17_19_22_29_45_2.jpg)

- [ ] Hybrid Azure AD join all the servers.
- [ ] Create a hybrid runbook worker m Azure Automation.
- [x] Deploy the Azure Connected Machine agent to all the servers.
- [ ] Deploy the Azure Monitor agent to all the servers.

**[⬆ Back to Top](#table-of-contents)**

### You have a Windows Server container host named Server 1 and a container image named Image1. You need to start a container from image1. The solution must run the container on a Hyper-V virtual machine. Which parameter should you specify when you run the docker run command?

- [ ] –expose.
- [ ] –privileged.
- [ ] –runtime.
- [ ] –entrypoint.
- [x] –isolation.

**[⬆ Back to Top](#table-of-contents)**

### You have an on-premises Active Directory Domain Services (AD DS) domain that syncs with an Azure Active Directory (Azure AD) tenant. You plan deploy 100 new Azure virtual machines that will run Windows Server. You need to ensure that each new virtual machine is joined to the AD DS domain. What should you use?

- [ ] Azure AD Connect.
- [ ] Group Policy Object (GPO).
- [x] Azure Resource Manager (ARM) template.
- [ ] Azure management group.

**[⬆ Back to Top](#table-of-contents)**

### You have an on-premises Active Directory Domain Services (AD DS) domain that syncs with an Azure Active Directory (Azure AD) tenant. You have several Windows 10 devices that are Azure AD hybrid-joined. You need to ensure that when users sign in to the devices, they can use Windows Hello for Business. Which optional feature should you select in Azure AD Connect?

- [x] Device writeback.
- [ ] Group writeback.
- [ ] Password writeback.
- [ ] Directory extension attribute sync.
- [ ] Azure AD app and attribute filtering.

**[⬆ Back to Top](#table-of-contents)**

### Contoso, Ltd. is a company that has a main office in Seattle and two branch offices in Los Angeles and Montreal. The network contains an on premises Active Directory Domain Services (AD DS) forest named contoso.com. The forest contains two domains named contoso.com and canada.contoso.com. The forest contains the domain controllers shown in the following table. All the domain controllers are global catalog servers. The network contains the servers shown in the following table. A server named Server4 runs Windows Server and is in a workgroup. Windows Firewall on Server4 uses the private profile. Server2 hosts three virtual machines named VM1, VM2, and VM3. VM3 is a file server that stores data in the volumes shown in the following table. The contoso.com domain has the Group Policies Objects (GPOs) shown in the following table. The forest contains the users shown in the following table. The forest contains the groups shown in the following table. When an administrator signs in to the console of VM2 by using Virtual Machine Connection, and then disconnects from the session without signing out, another administrator can connect to the console session as the currently signed in user. Contoso identifies the following technical requirements: Change the replication schedule for all site links to 30 minutes. Promote Server1 to a domain controller in canada.contoso.com. Install and authorize Server3 as a DHCP server. Ensure that User1 can manage the membership of all the groups in Contoso\OU3. Ensure that you can manage Server4 from Server1 by using PowerShell remoting. Ensure that you can run virtual machines on VM1. Force users to provide credentials when they connect to VM2. On VM3, ensure that Data Deduplication on all volumes is possible. You need to meet the technical requirements for VM1. Which cmdlet should you run first?

![Question 33 part 1](images/question5_8_9_20_33_38_39_43_1.jpg)
![Question 33 part 2](images/question5_8_9_20_33_38_39_43_2.jpg)
![Question 33 part 3](images/question5_8_9_20_33_38_39_43_3.jpg)
![Question 33 part 4](images/question5_8_9_20_33_38_39_43_4.jpg)
![Question 33 part 5](images/question5_8_9_20_33_38_39_43_5.jpg)
![Question 33 part 6](images/question5_8_9_20_33_38_39_43_6.jpg)
![Question 33 part 7](images/question33_7.jpg)

- [ ] Box 1: Set-VMProcessor. Box 2: -EnableHostResourceProtection.
- [ ] Box 1: Set-VM. Box 2: -ExposeVirtualizationExtensions.
- [x] Box 1: Set-VMProcessor. Box 2: -ExposeVirtualizationExtensions.
- [ ] Box 1: Set-VMHost. Box 2: -NewVMName.

**[⬆ Back to Top](#table-of-contents)**

### You need to meet the technical requirements for User1. The solution must use the principle of least privilege. What should you do?

- [ ] Add Users1 to the Server Operators group in contoso.com.
- [ ] Create a delegation on contoso.com.
- [ ] Add Users1 to the Account Operators group in contoso.com.
- [x] Create a delegation on OU3.

**[⬆ Back to Top](#table-of-contents)**

### Your network contains an Active Directory Domain Services (AD DS) domain named contoso.com. The domain contains a server named Server1 that has the DFS Namespaces role service installed. Server! hosts a domain-based Distributed File System (DFS) Namespace named Files. The domain contains a tile server named Server2. Seiver2 contains a shared folder named Share1. Share1 contains a subfolder named Folder 1. In the Files namespace, you create a folder named Folder! that has a target of \Server2.contoso.comShare1Folder1. You need to configure a logon script that will map drive letter M to Folder1. The solution must use the path of the DFS Namespace. How should you complete the command to map the drive letter?

![Question 35](images/question35.jpg)

- [x] Box 1: \\contoso.com. Box 2: \files\folder1.
- [ ] Box 1: \\files.contoso.com. Box 2: \share1\folder1.
- [ ] Box 1: \\Server1.contoso.com. Box 2: \files\share1\folder1.
- [ ] Box 1: \\Server2.contoso.com. Box 2: \files\folder1.

**[⬆ Back to Top](#table-of-contents)**

### You have a Windows Server container host named Server1 and an Azure subscription. You deploy an Azure container registry named Registry1 to the subscription. On Server1, you create a container image named image1. You need to store imager in Registry1. Which command should you run on Server1?

![Question 36](images/question36.jpg)

- [ ] Box 1: docker. Box 2: pull.
- [x] Box 1: docker. Box 2: push.
- [ ] Box 1: azcopy. Box 2: push.
- [ ] Box 1: git. Box 2: pull.

**[⬆ Back to Top](#table-of-contents)**

### Your network contains an on-premises Active Directory Domain Services (AD DS) domain named contoso.com The domain contains three servers that run Windows Server and have the Hyper-V server rote installed. Each server has a Switch Embedded Teaming (SET) team. You need to verity that Remote Direct Memory Access (RDMA) and all the required Windows Server settings are configured properly on each server. What should you use?

- [ ] Server Manager.
- [x] Validate-DCB cmdtet.
- [ ] Get-NetAdaptor cmdlet.
- [ ] Failover Cluster Manager.

**[⬆ Back to Top](#table-of-contents)**

### Contoso, Ltd. is a company that has a main office in Seattle and two branch offices in Los Angeles and Montreal. The network contains an on premises Active Directory Domain Services (AD DS) forest named contoso.com. The forest contains two domains named contoso.com and canada.contoso.com. The forest contains the domain controllers shown in the following table. All the domain controllers are global catalog servers. The network contains the servers shown in the following table. A server named Server4 runs Windows Server and is in a workgroup. Windows Firewall on Server4 uses the private profile. Server2 hosts three virtual machines named VM1, VM2, and VM3. VM3 is a file server that stores data in the volumes shown in the following table. The contoso.com domain has the Group Policies Objects (GPOs) shown in the following table. The forest contains the users shown in the following table. The forest contains the groups shown in the following table. When an administrator signs in to the console of VM2 by using Virtual Machine Connection, and then disconnects from the session without signing out, another administrator can connect to the console session as the currently signed in user. Contoso identifies the following technical requirements: Change the replication schedule for all site links to 30 minutes. Promote Server1 to a domain controller in canada.contoso.com. Install and authorize Server3 as a DHCP server. Ensure that User1 can manage the membership of all the groups in Contoso\OU3. Ensure that you can manage Server4 from Server1 by using PowerShell remoting. Ensure that you can run virtual machines on VM1. Force users to provide credentials when they connect to VM2. On VM3, ensure that Data Deduplication on all volumes is possible. You need to meet the technical requirements for VM3. On which volumes can you enable Data Deduplication?

![Question 38 part 1](images/question5_8_9_20_33_38_39_43_1.jpg)
![Question 38 part 2](images/question5_8_9_20_33_38_39_43_2.jpg)
![Question 38 part 3](images/question5_8_9_20_33_38_39_43_3.jpg)
![Question 38 part 4](images/question5_8_9_20_33_38_39_43_4.jpg)
![Question 38 part 5](images/question5_8_9_20_33_38_39_43_5.jpg)
![Question 38 part 6](images/question5_8_9_20_33_38_39_43_6.jpg)

- [x] D and E only.
- [ ] C, D, E, and F.
- [ ] D only.
- [ ] C and D only.
- [ ] D, E, and F only.

**[⬆ Back to Top](#table-of-contents)**

### Contoso, Ltd. is a company that has a main office in Seattle and two branch offices in Los Angeles and Montreal. The network contains an on premises Active Directory Domain Services (AD DS) forest named contoso.com. The forest contains two domains named contoso.com and canada.contoso.com. The forest contains the domain controllers shown in the following table. All the domain controllers are global catalog servers. The network contains the servers shown in the following table. A server named Server4 runs Windows Server and is in a workgroup. Windows Firewall on Server4 uses the private profile. Server2 hosts three virtual machines named VM1, VM2, and VM3. VM3 is a file server that stores data in the volumes shown in the following table. The contoso.com domain has the Group Policies Objects (GPOs) shown in the following table. The forest contains the users shown in the following table. The forest contains the groups shown in the following table. When an administrator signs in to the console of VM2 by using Virtual Machine Connection, and then disconnects from the session without signing out, another administrator can connect to the console session as the currently signed in user. Contoso identifies the following technical requirements: Change the replication schedule for all site links to 30 minutes. Promote Server1 to a domain controller in canada.contoso.com. Install and authorize Server3 as a DHCP server. Ensure that User1 can manage the membership of all the groups in Contoso\OU3. Ensure that you can manage Server4 from Server1 by using PowerShell remoting. Ensure that you can run virtual machines on VM1. Force users to provide credentials when they connect to VM2. On VM3, ensure that Data Deduplication on all volumes is possible. You need to meet the technical requirements for VM2. What should you do?

![Question 39 part 1](images/question5_8_9_20_33_38_39_43_1.jpg)
![Question 39 part 2](images/question5_8_9_20_33_38_39_43_2.jpg)
![Question 39 part 3](images/question5_8_9_20_33_38_39_43_3.jpg)
![Question 39 part 4](images/question5_8_9_20_33_38_39_43_4.jpg)
![Question 39 part 5](images/question5_8_9_20_33_38_39_43_5.jpg)
![Question 39 part 6](images/question5_8_9_20_33_38_39_43_6.jpg)

- [ ] Implement shielded virtual machines.
- [ ] Enable the Guest services integration service.
- [ ] Implement Credential Guard.
- [x] Enable enhanced session mode.

**[⬆ Back to Top](#table-of-contents)**

### You plan to deploy an Azure virtual machine that will run Windows Server. You need to ensure that an Azure Active Directory (Azure AD) user nameduserl@contoso.com can connect 10 the virtual machine by using the Azure Serial Console. What should you do?

![Question 40](images/question40.jpeg)

- [x] Configure on the Azure virtual machine: Boot diagnostics with a custom storage account. Assign the following role to User1: Virtual Machine Contributor.
- [ ] Configure on the Azure virtual machine: A system-assigned managed identity. Assign the following role to User1: Virtual Machine Administrator Login.
- [ ] Configure on the Azure virtual machine: Boot diagnostics with a custom storage account. Assign the following role to User1: Virtual Machine User Login.
- [ ] Configure on the Azure virtual machine: Operating system guest diagnostics. Assign the following role to User1: Virtual Machine Contributor.

**[⬆ Back to Top](#table-of-contents)**

### ...

### Fabrikam, Inc is a manufacturing company that has a main office in New York and a branch office in Seattle. The on-premises network contains servers that run Windows Server as shown in the following table. DC1 hosts all the operation master roles. VM1 and VM2 are connected to the internet. WEB1 and WEB2 run an Internet Information Services (IIS) web app named Webapp1. The New York and Seattle offices are connected by using redundant WAN links. The client computers in each office get IP addresses from their local DHCP server. DHCP1 contains a scope named Scope1 that has addresses for the New York office, DHCP2 contains a scope named Scope2 that has addresses for the Seattle office. The network contains a single on-premises Active Directory Domain Services (AD DS) domain named corp.falbrikam.com. Currently, all the service accounts use individual domain user accounts. All domain controllers have the DNS Server role installed and host a copy of the Active Directory integrated DNS zone of corp.fabrikam.com. The corp.fabrikam.com AD DS domain syncs with an Azure Active Directory (Azure AD) tenant. The corp.fabrikam.com domain contains the organizational units (OUs) and custom Group Policy Objects (GPOs) shown in the following table. Fabrikam identifies the following planned changes: Create a single Azure subscription named Sub1 that will contain a single Azure virtual network named Vnet1. Replace the WAN links between the Seattle and New York offices by using Azure Virtual WAN and FxpressRoute. Both on premises offices will be connected to Vnet1 by using ExpressRoute. Create three Azure file shares named newyorkfiles, seattlefiles, and companyfiles. Create a domain controller named dc3.corp.fabrikam.com in Vnet1. Deploy an Azure Virtual Desktop host pool to Vnet1. The Azure Virtual Desktop session hosts will be hybrid Azure AD-joined. License all servers for Microsoft Defender for servers. Use Azure Policy to enforce configuration management policies on the servers in Azure and on-premises. Fabrikam identifies the following networking requirements: Implement Virtual WAN and ensure that all the network traffic between the sites uses Virtual WAN. All communications must occur over ExpressRoute. If a DHCP server fails, ensure that the client computers can continue to receive their dynamic IP address and renew their existing lease. Ensure that the resources in Vnet1 can resolve the names of the on-premises servers in the corp.fabrikam.com domain. Fabrikam identifies the following security requirements: Apply GPO4 to the Azure Virtual Desktop session hosts. Ensure that Azure Virtual Desktop user sessions lock after being idle for 10 minutes. Users must be able to control the lockout time manually from their client computer. Ensure that server administrators request approval before they can establish a Remote Desktop connection to an Azure virtual machine. If the request is approved, the connection must be established within two hours. Prevent user passwords from containing all or part of words that are based on the company name, such as Fab, f@br1kAm or fabr!|. Ensure that all instances of Webapp1 use the same service account. The password of the service account must change automatically every 30 days. Prevent domain controllers from directly contacting hosts on the internet. You need to configure the synchronization of Azure files to meet the following requirements: Ensure that seattlefiles syncs to FS2. Ensure that newyorkfiles syncs to FS1. Ensure that companyfiles syncs to both FS1 and FS2. You need to implement a name resolution solution that meets the networking requirements. Which two actions should you perform?

- [ ] Create an Azure private DNS zone named corp.fabhkam.com.
- [ ] Create a virtual network link in the coip.fabnkam.com Azure private DNS zone.
- [ ] Create an Azure DNS zone named corp.fabrikam.com.
- [x] Configure the DNS Servers settings for Vnet1.
- [ ] Enable autoregistration in the corp.fabnkam.com Azure private DNS zone.
- [x] On DC3, install the DNS Server role.
- [ ] Configure a conditional forwarder on DC3.

**[⬆ Back to Top](#table-of-contents)**

### Contoso, Ltd. is a company that has a main office in Seattle and two branch offices in Los Angeles and Montreal. The network contains an on premises Active Directory Domain Services (AD DS) forest named contoso.com. The forest contains two domains named contoso.com and canada.contoso.com. The forest contains the domain controllers shown in the following table. All the domain controllers are global catalog servers. The network contains the servers shown in the following table. A server named Server4 runs Windows Server and is in a workgroup. Windows Firewall on Server4 uses the private profile. Server2 hosts three virtual machines named VM1, VM2, and VM3. VM3 is a file server that stores data in the volumes shown in the following table. The contoso.com domain has the Group Policies Objects (GPOs) shown in the following table. The forest contains the users shown in the following table. The forest contains the groups shown in the following table. When an administrator signs in to the console of VM2 by using Virtual Machine Connection, and then disconnects from the session without signing out, another administrator can connect to the console session as the currently signed in user. Contoso identifies the following technical requirements: Change the replication schedule for all site links to 30 minutes. Promote Server1 to a domain controller in canada.contoso.com. Install and authorize Server3 as a DHCP server. Ensure that User1 can manage the membership of all the groups in Contoso\OU3. Ensure that you can manage Server4 from Server1 by using PowerShell remoting. Ensure that you can run virtual machines on VM1. Force users to provide credentials when they connect to VM2. On VM3, ensure that Data Deduplication on all volumes is possible. You need to meet the technical requirements for Server1. Which users can currently perform the required tasks?

![Question 43 part 1](images/question5_8_9_20_33_38_39_43_1.jpg)
![Question 43 part 2](images/question5_8_9_20_33_38_39_43_2.jpg)
![Question 43 part 3](images/question5_8_9_20_33_38_39_43_3.jpg)
![Question 43 part 4](images/question5_8_9_20_33_38_39_43_4.jpg)
![Question 43 part 5](images/question5_8_9_20_33_38_39_43_5.jpg)
![Question 43 part 6](images/question5_8_9_20_33_38_39_43_6.jpg)

- [ ] Admin1 only.
- [ ] Admin3 only.
- [x] Admin1 and Admin3 only.
- [ ] Admin1 Admin2 and Admin3.

**[⬆ Back to Top](#table-of-contents)**

### You need to sync files from an on-premises server named Server1 to Azure by using Azure File Sync. You have a cloud tiering policy that is configured for 30 percent free space and 70 days. Volume f on Server1 is 500 GB. A year ago. you configured E:Oata on Server1 to sync by using Azure File Sync.  The files that are visible in E:Data are shown in the following table. Volume E does NOT contain any other files. Where are File1 and flle3 located?

![Question 44 part 1](images/question44_1.png)
![Question 44 part 2](images/question44_2.png)

- [ ] File1: The Azure file share only. File3: Server1 and the Azure file share.
- [ ] File1: Server1 and the Azure file share. File3: The Azure file share only.
- [x] File1: Server1 and the Azure file share. File3: The Azure file share only.
- [ ] File1: Server1 only. File3: Server1 and the Azure file share.

**[⬆ Back to Top](#table-of-contents)**

### Fabrikam, Inc is a manufacturing company that has a main office in New York and a branch office in Seattle. The on-premises network contains servers that run Windows Server as shown in the following table. DC1 hosts all the operation master roles. VM1 and VM2 are connected to the internet. WEB1 and WEB2 run an Internet Information Services (IIS) web app named Webapp1. The New York and Seattle offices are connected by using redundant WAN links. The client computers in each office get IP addresses from their local DHCP server. DHCP1 contains a scope named Scope1 that has addresses for the New York office, DHCP2 contains a scope named Scope2 that has addresses for the Seattle office. The network contains a single on-premises Active Directory Domain Services (AD DS) domain named corp.falbrikam.com. Currently, all the service accounts use individual domain user accounts. All domain controllers have the DNS Server role installed and host a copy of the Active Directory integrated DNS zone of corp.fabrikam.com. The corp.fabrikam.com AD DS domain syncs with an Azure Active Directory (Azure AD) tenant. The corp.fabrikam.com domain contains the organizational units (OUs) and custom Group Policy Objects (GPOs) shown in the following table. Fabrikam identifies the following planned changes: Create a single Azure subscription named Sub1 that will contain a single Azure virtual network named Vnet1. Replace the WAN links between the Seattle and New York offices by using Azure Virtual WAN and FxpressRoute. Both on premises offices will be connected to Vnet1 by using ExpressRoute. Create three Azure file shares named newyorkfiles, seattlefiles, and companyfiles. Create a domain controller named dc3.corp.fabrikam.com in Vnet1. Deploy an Azure Virtual Desktop host pool to Vnet1. The Azure Virtual Desktop session hosts will be hybrid Azure AD-joined. License all servers for Microsoft Defender for servers. Use Azure Policy to enforce configuration management policies on the servers in Azure and on-premises. Fabrikam identifies the following networking requirements: Implement Virtual WAN and ensure that all the network traffic between the sites uses Virtual WAN. All communications must occur over ExpressRoute. If a DHCP server fails, ensure that the client computers can continue to receive their dynamic IP address and renew their existing lease. Ensure that the resources in Vnet1 can resolve the names of the on-premises servers in the corp.fabrikam.com domain. Fabrikam identifies the following security requirements: Apply GPO4 to the Azure Virtual Desktop session hosts. Ensure that Azure Virtual Desktop user sessions lock after being idle for 10 minutes. Users must be able to control the lockout time manually from their client computer. Ensure that server administrators request approval before they can establish a Remote Desktop connection to an Azure virtual machine. If the request is approved, the connection must be established within two hours. Prevent user passwords from containing all or part of words that are based on the company name, such as Fab, f@br1kAm or fabr!|. Ensure that all instances of Webapp1 use the same service account. The password of the service account must change automatically every 30 days. Prevent domain controllers from directly contacting hosts on the internet. You need to configure the synchronization of Azure files to meet the following requirements: Ensure that seattlefiles syncs to FS2. Ensure that newyorkfiles syncs to FS1. Ensure that companyfiles syncs to both FS1 and FS2. You need to configure network communication between the Seattle and New York offices. The solution must meet the networking requirements. What should you configure?

![Question 45 part 1](images/question7_16_17_19_22_29_45_1.jpg)
![Question 45 part 2](images/question7_16_17_19_22_29_45_2.jpg)
![Question 45 part 3](images/question45_3.jpg)

- [ ] On a Virtual WAN hub: An ExpressRoute gateway. In the offices: A Site-to-Site VPN.
- [ ] On a Virtual WAN hub: A virtual network gateway. In the offices: An on premises data gateway.
- [x] On a Virtual WAN hub: An ExpressRoute gateway. In the offices: An ExpressRoute circuit connection.
- [ ] On a Virtual WAN hub: An ExpressRoute circuit connection. In the offices: A Site-to-Site VPN.

**[⬆ Back to Top](#table-of-contents)**

### You have an on-premises Active Directory Domain Services (AD DS) domain that syncs with an Azure Active Directory (Azure AD) tenant. The on-premises network is connected to Azure by using a Site-to-Site VPN. You have the DNS zones shown in the following table. You need to ensure that names from fabrikam.com can be resolved from the on-premises network. Which two actions should you perform?

![Question 46](images/question46.png)

- [ ] Create a stub zone for fabrikam.com on DC1.
- [x] Create a conditional forwarder for fabrikam.com on DC1.
- [ ] Create a secondary zone for fabrikam.com on DC1.
- [ ] Deploy an Azure virtual machine that runs Windows Server. Modify the DNS Servers settings for the virtual network.
- [x] Deploy an Azure virtual machine that runs Windows Server. Configure the virtual machine as a DNS forwarder.

**[⬆ Back to Top](#table-of-contents)**

### ...

**[⬆ Back to Top](#table-of-contents)**

### You have an on premises Active Directory Domain Services (AD DS) domain that syncs with an Azure Active Directory (Azure AD) tenant. The domain contains two servers named Server1 and Server2. A user named Admin1 is a member of the local Administrators group on Server1 and Server2. You plan to manage Server1 and Server2 by using Azure Arc. Azure Arc objects will be added to a resource group named RG1. You need to ensure that Admin1 can configure Server1 and Server2 to be managed by using Azure Arc. What should you do first?

- [ ] From the Azure portal, generate a new onboarding script.
- [x] Assign Admin1 the Azure Connected Machine Onboarding role for RG1.
- [ ] Hybrid Azure AD join Server1 and Server2.
- [ ] Create an Azure cloud-only account for Admin1.

**[⬆ Back to Top](#table-of-contents)**

### Your network contains an Active Directory Domain Services (AD DS) forest. The forest contains three Active Directory sites named Site1, Site2, and Site3. Each site contains two domain controllers. The sites are connected by using DEFAULTIPSITELINK. You open a new branch office that contains only client computers. You need to ensure that the client computers in the new office are primarily authenticated by the domain controllers in Site1. Solution: You create a new subnet object that is associated to Site1. Does this meet the goal?

- [ ] Yes.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### You have an Azure virtual machine named VM1 that runs Windows Server and has the following configurations: ✑ Size: D2s_v4 ✑ Operating system disk: 127-GiB standard SSD ✑ Data disk 128-GiB standard SSD ✑ Virtual machine generation: Gen 2 You plan to perform the following changes to VM1: ✑ Change the virtual machine size to D4s_v4. ✑ Detach the data disk. ✑ Add a new standard SSD. Which changes require downtime for VM1?

- [ ] Detaching the data disk only and adding a new standard SSD.
- [ ] Detaching the data disk only.
- [x] Changing the virtual machine size only.
- [ ] Adding a new standard SSD only.

**[⬆ Back to Top](#table-of-contents)**

### Your network contains an Active Directory Domain Services (AD DS) domain named contoso.com. The domain contains two servers named Server1 and Server2. Server1 contains a disk named Disk2. Disk2 contains a folder named UserData. UserData is shared to the Domain Users group. Disk2 is configured for deduplication. Server1 is protected by using Azure Backup. Server1 fails. You connect Disk2 to Server2. You need to ensure that you can access all the files on Disk2 as quickly as possible. What should you do?

- [ ] Create a storage pool.
- [ ] Restore files from Azure Backup.
- [ ] Install the File Server Resource Manager server role.
- [x] Install the Data Deduplication server role.

**[⬆ Back to Top](#table-of-contents)**

### Your network contains an Active Directory Domain Services (AD DS) domain named contoso.com. You need to identify which server is the PDC emulator for the domain. Solution: From a command prompt, you run netdom.exe query fsmo. Does this meet the goal?

- [x] Yes.
- [ ] No.

**[⬆ Back to Top](#table-of-contents)**

### You have an Azure virtual machine named Server1 that runs a network management application. Server1 has the following network configuration. * Network interface.Nic1 * IP address 10.1.1.1/24 * Connected to: Vnet1/Subnet1 You need connect Server1 to an additional subnet named Vnet1/Subnet2. What should you do?

- [ ] Create a private endpoint on Subnet2
- [x] Add a network interface to server1.
- [ ] Modify the IP configurations of Nic1.
- [ ] Add an IP configuration to Nic1.

**[⬆ Back to Top](#table-of-contents)**

### Your network contains a two-domain on-premises Active Directory Domain Services (AD DS) forest named Contoso.com. The forest contains the domain controllers shown in the following table. You create an Active Directory site named Site3. Site1, Site2 and Site3 each has a dedicated site link to the Hub site. In Site3, you install a new server named Server1. You need to promote Server1 to an ROOC in child.contoso.com by using the install from Media (IFM) option. The solution must minimize network traffic. What should you do?

![Question 54](images/question54.png)

Server to use to create the IFM source:
- [x] DC1.
- [ ] DC2.
- [ ] Server1.
- [ ] RODC3.

Tool to use to create the IFM source:
- [ ] Azure Backup.
- [ ] Dcdiag.exe.
- [x] Ntdsutil.exe.
- [ ] Repadmin.exe.
- [ ] Windows Server Backup.

**[⬆ Back to Top](#table-of-contents)**

### You have a server named Server1 that runs Windows Server and contains three volumes named C, D, and E. Files are stored on Server1 as shown in the following table. For volume D, Data Deduplication is enabled and set to General purpose file server. You perform the following actions: Move File1 to volume D. Copy File2 to volume D and name the copy File4. Move File3 to volume E.

![Question 55](images/question55.png)

File1 is deduplicated after the deduplication job runs:
- [x] Yes.
- [ ] No.

File3 is deduplicated after the deduplication job runs:
- [ ] Yes.
- [x] No.

File4 is deduplicated after the deduplication job runs:
- [x] Yes.
- [ ] No.

**[⬆ Back to Top](#table-of-contents)**

### You have an Azure subscription that contains a virtual machine named VM1 as shown in the following exhibit. The subscription has the disks shown in the following table. Which disks can you attach as data disks to VM1?

![Question 56 part 1](images/question56_1.jpg)
![Question 56 part 2](images/question56_2.jpg)

- [ ] Disk2 only.
- [ ] Disk4 only.
- [x] Disk1 and Disk2 only.
- [ ] Disk2 and Disk4 only.
- [ ] Disk1, Disk3, and Disk4 only.
- [ ] Disk1, Disk2, Disk3. and Disk4.

**[⬆ Back to Top](#table-of-contents)**

### Your network contains an Active Directory Domain Services (AD DS) forest named contoso.com. The root domain contains the domain controllers shown in the following table. A failure of which domain controller will prevent you from creating application partitions?

![Question 57](images/question57.jpg)

- [x] DC1.
- [ ] DC2.
- [ ] DC3.
- [ ] DC4.
- [ ] DC5.

**[⬆ Back to Top](#table-of-contents)**

### You are planning the deployment of DNS to a new network. You have three internal DNS servers as shown in the following table. The contoso.local zone contains zone delegations for east.conloso.local and west.contoso.local. All the DNS servers use root hints. You need to ensure that all the DNS servers can resolve the names of all the internal namespaces and internet hosts. Solution: On Server2 and Server3, you configure a conditional forwarder for contoso.local. Does this meet the goal?

![Question 58](images/question58.jpg)

- [x] Yes.
- [ ] No.

**[⬆ Back to Top](#table-of-contents)**

### You have an on-premises server named Server1 that runs Windows Server. You have an Azure virtual network that contains an Azure virtual network gateway. You need to connect only Server1 to the Azure virtual network. What should you use?

- [x] Azure Network Adapter.
- [ ] a Site-to-SiteVPN.
- [ ] an ExpressRoute circuit.
- [ ] Azure Extended Network.

### ...

**[⬆ Back to Top](#table-of-contents)**

### Your network contains a multi-site Active Directory Domain Services (AD DS) forest. Each Active Directory site is connected by using manually configured site links and automatically generated connections. You need to minimize the convergence time for changes to Active Directory. What should you do?

- [x] For each site link, modify the options attribute.
- [ ] For each site link, modify the site link costs.
- [ ] For each site link, modify the replication schedule.
- [ ] Create a site link bridge that contains all the site links.

**[⬆ Back to Top](#table-of-contents)**

### Your company has a main office and a branch office. The two offices are connected by using a WAN link. Each office contains a firewall that filters WAN traffic. The network in the branch office contains 10 servers that run Windows Server. All servers are administered from the main office only. You plan to manage the servers in the branch office by using a Windows Admin Center gateway. On a server in the branch office, you install the Windows Admin Center gateway by using the defaults settings. You need to configure the firewall in the branch office to allow the required inbound connection to the Windows Admin Center gateway. Which inbound TCP port should you allow?

- [x] 443.
- [ ] 3389.
- [ ] 5985.
- [ ] 6516.

**[⬆ Back to Top](#table-of-contents)**

### Your network contains an Active Directory Domain Services (AD DS) domain- The domain contains 10 servers that run Windows Server. The servers have static IP addresses. You plan to use DHCP to assign IP addresses to the servers. You need to ensure that each server always receives the same IP address. Which type of identifier should you use to create a DHCP reservation for each server?

- [ ] universally unique identifier (UUID).
- [ ] fully qualified domain name (FQDN).
- [ ] NetBIOS name.
- [x] MAC address.

**[⬆ Back to Top](#table-of-contents)**

### You have an Azure virtual machine named VM1 that has a private IP address only. You configure the Windows Admin Center extension on VM1. You have an on-premises computer that runs Windows 11. You use the computer for server management. You need to ensure that you can use Windows Admin Center from the Azure portal to manage VM1. What should you configure?

- [ ] an Azure Bastion host on the virtual network that contains VM1.
- [x] a VPN connection to the virtual network that contains VM1.
- [ ] a network security group 1NSG) rule that allows inbound traffic on port 443.
- [ ] a private endpoint on the virtual network that contains VM1.

**[⬆ Back to Top](#table-of-contents)**

### You have a server that runs Windows Server and has the DHCP Server role installed. The server has a scope named Scope! that has the following configurations: Address range: 192.168.0.2 to 192.16B.1.2M. Mask 255.255.254.0. Router: 192.168.0.1. Lease duration: 3 days. DNS server 172.16.0.254 You have 50 Microsoft Teams Phone devices from the same vendor. All the devices have MAC addresses within the same range. You need to ensure that all the Teams Phone devices that receive a lease from Scope1 have IP addresses in the range of 192.168.1.100 to 192.168.1.200. The solution must NOT affect other DHCP clients that receive IP configurations from Scope1. What should you create?

- [x] a policy.
- [ ] a scope.
- [ ] a fitter.
- [ ] scope options.

**[⬆ Back to Top](#table-of-contents)**

### You have an Azure subscription that contains the following resources: An Azure Log Analytics workspace. An Azure Automation account. Azure Arc. You have an on-premises server named Server1 that is onboaraed to Azure Arc You need to manage Microsoft updates on Server! by using Azure Arc Which two actions should you perform? Each correct answer presents part of the solution.

- [ ] Add Microsoft Sentinel to the Log Analytics workspace.
- [x] On Server1, install the Azure Monitor agent.
- [x] From the Automation account, enable Update Management for Server1.
- [ ] From the Virtual machines data source of the Log Analytics workspace, connect Server1.

**[⬆ Back to Top](#table-of-contents)**

### Your network contains two VLANs for client computers and one VLAN for a datacenter Each VLAN is assigned an IPv4 subnet Currently, all the client computers use static IP addresses. You plan to deploy a DHCP server to the VLAN in the datacenter. You need to use the DHCP server to provide IP configurations to all the client computers. What is the minimum number of scopes and DHCP relays you should create?

![Question 67](images/question67.png)

DHCP scopes:
- [ ] 1.
- [ ] 2.
- [x] 3.
- [ ] 4.

DHCP relays:
- [ ] 1.
- [x] 2.
- [ ] 3.
- [ ] 4.

**[⬆ Back to Top](#table-of-contents)**

### You have an on premises Active Directory Domain Services (AD DS) domain that syncs with an Azure Active Directory (Azure AD) tenant. You plan to implement self-service password reset (SSPR) in Azure AD. You need to ensure that users that reset their passwords by using SSPR can use the new password resources in the AD DS domain. What should you do?

- [ ] Deploy the Azure AD Password Protection proxy service to the on premises network.
- [x] Run the Microsoft Azure Active Directory Connect wizard and select Password writeback.
- [ ] Grant the Change password permission for the domain to the Azure AD Connect service account.
- [ ] Grant the impersonate a client after authentication user right to the Azure AD Connect service account.

**[⬆ Back to Top](#table-of-contents)**

### You have an Azure Active Directory Domain Services (Azure AD DS) domain named contoso.com. You need to provide an administrator with the ability to manage Group Policy Objects (GPOs). The solution must use the principle of least privilege. To which group should you add the administrator?

- [x] AAD DC Administrators.
- [ ] Domain Admins.
- [ ] Schema Admins.
- [ ] Enterprise Admins.
- [ ] Group Policy Creator Owners.

**[⬆ Back to Top](#table-of-contents)**

### You have an Azure subscription named sub1 and 500 on-premises virtual machines that run Windows Server. You plan to onboard the on-premises virtual machines to Azure Arc by running the Azure Arc deployment script You need to create an identity that mil be used by the script to authenticate access to sub1. The solution must use the principle of least privilege. How should you complete the command?

![Question 70](images/question70.jpg)

- [ ] New-AzADAppCredential.
- [x] New-AZADServicePrincipal.
- [ ] New-AZUserAssignedIdentity.
- [ ] DisplayName 'Arc-for-servers' -Role
- [ ] Azure Connected Machine Onboarding.
- [x] Virtual Machine Contributor.
- [ ] Virtual Machine User Login.

**[⬆ Back to Top](#table-of-contents)**

### You have an on premises Active Directory Domain Services (AD DS) domain that syncs with an Azure Active Directory (Azure AD) tenant. You plan to implement self-service password reset (SSPR) in Azure AD.You need to ensure that users that reset their passwords by using SSPR can use the new password resources in the AD DS domain. What should you do?

- [ ] Deploy the Azure AD Password Protection proxy service to the on premises network.
- [x] Run the Microsoft Azure Active Directory Connect wizard and select Password writeback.
- [ ] Grant the Change password permission for the domain to the Azure AD Connect service account.
- [ ] Grant the impersonate a client after authentication user right to the Azure AD Connect service account.

### ...

### You create a new Azure subscription. You plan to deploy Azure Active Directory Domain Services (Azure AD DS) and Azure virtual machines. You need to ensure that the virtual machines can join to Azure AD DS. Which three actions should you perform in sequence?

![Question 73](images/question73.jpg)

- [ ] Box 1: Modify the settings of the Azure virtual network. Box 2: Install the Active Direcotry Domain Services role. Box 3: Install Azure AD Connect.
- [ ] Box 1: Install the Active Direcotry Domain Services role. Box 2: Install Azure AD Connect. Box 3: Install the Active Direcotry Domain Services role.
- [x] Box 1: Create an Azure virtual network. Box 2: Create an Azure AD DS instance. Box 3: Modify the settings of the Azure virtual network.
- [ ] Box 1: Create an Azure AD DS instance. Box 2: Run the Active Directory Domain Service installation Wizard. Box 3: Install Azure AD Connect.

### You have an Azure Active Directory Domain Services (Azure AD DS) domain. You create a new user named Admin1. You need Admin1 to deploy custom Group Policy settings to all the computers in the domain. The solution must use the principle of least privilege. What should you include in the solution? Add Admin1 to the following group:

- [x] AAD DC Administrators.
- [ ] Domain Admins.
- [ ] Group Policy Creator Oweners.

### You have an Azure Active Directory Domain Services (Azure AD DS) domain. You create a new user named Admin1. You need Admin1 to deploy custom Group Policy settings to all the computers in the domain. The solution must use the principle of least privilege. What should you include in the solution? Instruct Admin1 apply the custom Groupp Policy settings by:

- [ ] Creating a new Group Policy Object (GPO) and linking the GPO to the domain.
- [x] Modifying AADDC Compputers GPO.
- [ ] Modifying the default domain GPO.

### ...

### Your network contains a single domain Active Directory Domain Services (AD DS) forest named contoso.com. The forest contains a single Active Directory site. You plan to deploy a read only domain controller (RODC) to a new datacenter on a server named Server1. A user named User1 is a member of the local Administrators group on Server1. You need to recommend a deployment plan that meets the following requirements: Ensures that a user named User1 can perform the RODC installation on Server1 Ensures that you can control the AD DS replication schedule to the Server1 Ensures that Server1 is in a new site named RemoteSite1Uses the principle of least privilege. Which three actions should you recommend performing in sequence?

![Question 77](images/question77.jpg)

- [ ] Box 1: Instruct User1 to run the Active Directory Domain Services installation Wizard on Server Box 2: Create a site link. Box 3: Pre-create an RODOC account.
- [ ] Box 1: Create a site and a subnet. Box 2: Pre-create an RODOC account. Box 3: Instruct User1 to run the Active Directory Domain Services installation Wizard on Server1.
- [ ] Box 1: Create a site link. Box 2: Pre-create an RODOC account. Box 3: Add User1 to the Contoso\Administstrators group.
- [x] Box 1: Pre-create an RODOC account. Box 2: Create a site and a subnet. Box 3: Instruct User1 to run the Active Directory Domain Services installation Wizard on Server1.

### Your network contains an Active Directory Domain Services (AD DS) domain. The network also contains 20 domain controllers, 100 member servers, and 100 client computers. You have a Group Policy Object (GPO) named GPO1 that contains Group Policy preferences. You plan to link GPO1 to the domain. You need to ensure that the preference in GPO1 apply only to domain member servers and NOT to domain controllers or client computers. All the other Group Policy settings in GPO1 must apply to all the computers. The solution must minimize administrative effort. Which type of item level targeting should you use?

- [ ] Domain.
- [x] Operating System.
- [ ] Security Group.
- [ ] Environment Variable.

### Events from Windows event logs:

- [ ] AzureActivity.
- [ ] AzureDiagnostics.
- [x] Event.
- [ ] Syslog.

### Key Vault ppermissions for the managed identity:

- [ ] Keys: Gey.
- [ ] Keys: List and Get.
- [x] Secrets: Get.
- [ ] Secrets: List and Get.

### To provide access to virtual machines on VNET1, use: [...].

- [ ] Azure Bastion.
- [x] Just-in-time (JIT) VM access.
- [ ] Azure Web Appplication Firewall (WAF) in Azure Front Doctor.

### To enforce Azure MFA, use:

- [ ] An Azure Identity Governance access package.
- [x] A Conditional Access policy that has the Cloud apps assignment set to Azure Windows Vm Sing-In.
- [ ] A Conditional Access ppolicy that has the Cloud apps assignment set to Microsoft Azure Management.

### User1 can create a new virtual machine in RG1.

- [x] Yes.
- [ ] No.

### Your network contains an Active Directory Domain Services (AD DS) forest named contoso.com. You create the resources shown in the following table.You create the Group Policy Objects (GPOs) shown in the following table. You configure the Group Policy Preferences shown in the following table. If User3 signs in to Comp1, a shortcut named Link2 will appear on the computer's desktop.

- [ ] Yes.
- [x] No.

### ...

### Your network contains an on-premises Active Directory Domain Services (AD DS) domain named contoso.com. The domain contains the objects shown in the following table. You plan to sync contoso.com with an Azure Active Directory (Azure AD) tenant by using Azure AD Connect. You need to ensure that all the objects can be used in Conditional Access policies. What should you do?

![Question 87](images/question87.jpg)

- [x] Select the Configure Hybrid Azure AD join option.
- [ ] Change the scope of Group1 and Group2 to Global.
- [ ] Clear the Configure device writeback option.
- [ ] Change the scope of Group2 to Universal.

### ...

### Your network contains three Active Directory Domain Services (AD DS) forests as shown in the following exhibit. The network contains the users shown in the following table. The network contains the security groups shown in the following table. You can add User2 to Group3 [...].

- [ ] Yes.
- [x] No.

### Your network contains three Active Directory Domain Services (AD DS) forests as shown in the following exhibit. The network contains the users shown in the following table. The network contains the security groups shown in the following table.You can grant Group2 permissions to the resources in the fabrikam.com domain [...].

- [x] Yes.
- [ ] No.

### Your network contains an Active Directory Domain Services (AD DS) forest named contoso.com. The forest root domain contains a server named server1.contoso.com. A two-way forest trust exists between the contoso.com forest and an AD DS forest named fabrikam.com. The fabrikam.com forest contains 10 child domains. You need to ensure that only the members of a group named fabrikam\Group1 can authenticate to server1.contoso.com. What should you do first?

- [ ] Add fabrikam\Group1 to the local Users group on server1.contoso.com.
- [ ] Enable SID filtering for the trust.
- [x] Enable Selective authentication for the trust.
- [ ] Change the trust to a one-way external trust.

### Your network contains an Active Directory forest. The forest contains two domains named contoso.com and east.contoso.com and the servers shown in the following table. Contoso.com contains a user named User1. You add User1 to the built-in Backup Operators group in contoso.com. Which servers can User1 back up?

![Question 92](images/question92.jpg)

- [x] DC1 only.
- [ ] Server1 only.
- [ ] DC1 and DC2 only.
- [ ] DC1 and Server1 only.
- [ ] DC1, DC2, Server1, and Server2.

### Your network contains an Azure Active Directory Domain Services (Azure AD DS) domain named contoso.com. You need to configure a password policy for the local user accounts on the Azure virtual machines joined to contoso.com. What should you do? Sign in by using a user account that is a member of the[...]:

- [x] AAD DC Administrators group.
- [ ] Administrators group.
- [ ] Domain Admins group.

### You need to configure a Group Policy preference to ensure that users in the organizational unit (OU) named Server Admins have a shortcut to a folder named \\srv1.contoso.com\data on their desktop when they sign in to the computers in the domain. To complete this task, sign in the required computer or computers.

- [x] Create Desktop Shortcuts on Domain Computers via GPO Step 1: Open the Group Policy Management Console (gpmc.msc). Step 2: Right-click an AD container (Organizational Unit) you want to apply a shortcut creation policy. In this case, right-click on the OU Server Admins. Step 3: Select Create a GPO in this domain, and Link it here.. Step 4: Go to the Group Policy Preferences section: User Configuration -> Preferences -> Windows Settings -> Shortcuts. Click it and select New -> Shortcut.Step 5: Create a new shortcut item with the following settings: Name: Something Target Type: File System Object (you can select a URL or a Shell object here) Location: Desktop Target Path: \\\\srv1.contoso.com\\data
srv1.contoso.com

### You plan to promote a domain controller named DC3 in a site in Seattle. You need to ensure that DC3 only replicates with DC1 and DC2 between 8 PM and 6 AM. To complete this task, sign in the required computer or computers.

- [x] Step 1: Create a site link between Seattle and the site in which DC1 and DC2 are located (if the site link does not already exist. If the site link already exists, then skip Step 1). Step 2: To open Active Directory Sites and Services, click Start, click Administrative Tools, and then click Active Directory Sites and Services. Step 3: In the console tree, click the intersite transport folder that contains the site link for which you are configuring intersite replication availability. Step 4: In the details pane, right-click the site link whose schedule you want to configure, and then click Properties. Step 5: Click Change Schedule. Step 6: Select the block of time during which you want replication to be either available or not available, and then click Replication Not Available or Replication Available, respectively. Change the schedule to: from 8 PM to 6 AM.

### You need to ensure that DC2 is the schema master for contoso.com. To complete this task, sign in the required computer or computers.

-[x] Seize operations master roles You cannot use AD DS snap-ins to seize operations master roles. Instead, you must use either the ntdsutil.execommand-line tool or Windows PowerShell to seize roles. To seize or transfer the FSMO roles by using the Ntdsutil utility, follow these steps: Step 1: Sign in to a member computer, in our case DC2, that has the AD RSAT tools installed, or a DC that is located in the forest where FSMO roles are being transferred. Step 2: Select Start > Run, type ntdsutil in the Open box, and then select OK. Step 3: Type roles, and then press Enter. Note: To see a list of available commands at any one of the prompts in the Ntdsutil utility, type ?, and then press Enter. Step 4: Type connections, and then press Enter. Step 5: Type connect to server <servername>, and then press Enter. Step 6: At the server connections prompt, type q, and then press Enter. Step 7: To seize the role: Type seize <role>, and then press Enter. In our case we type: seize schema master. Step 8: At the fsmo maintenance prompt, type q, and then press Enter to gain access to the ntdsutil prompt. Type q, and then press Enter to quit the Ntdsutil utility.

### Your network contains an Active Directory Domain Services (AD DS) forest. The forest contains three domains. Each domain contains 10 domain controllers. You plan to store a DNS zone in a custom Active Directory partition. You need to create the Active Directory partition for the zone. The partition must replicate to only four of the domain controllers. What should you use?

- [ ] Windows Admin Center.
- [ ] DNS Manager.
- [ ] Active Directory Sites and Services.
- [x] ntdsutil.exe.

### You need to provide users in the contoso.com forest with access to the resources in the fabrikam.com forest. The solution must meet the following requirements: Users in contoso.com must only be added directly to groups in the contoso.com forest. Permissions to access the resources in fabrikam.com must only be granted directly to groups in the fabrikam.com forest. The number of groups must be minimized. Which type of groups should you use to organize the users and to assign permissions? Organize users:

- [x] Domain global.
- [ ] Domain local.
- [ ] Universal.

### You need to provide users in the contoso.com forest with access to the resources in the fabrikam.com forest. The solution must meet the following requirements: Users in contoso.com must only be added directly to groups in the contoso.com forest. Permissions to access the resources in fabrikam.com must only be granted directly to groups in the fabrikam.com forest. The number of groups must be minimized. Which type of groups should you use to organize the users and to assign permissions? Assign permissions:

- [ ] Domain global.
- [x] Domain local.
- [ ] Universal.

### Your network contains two Active Directory forests and a domain trust as shown in the following exhibit. The domain trust has the following configurations: Name: adatum.co Type: External Direction: One-way, outgoing Outgoing trust authentication level: Domain-wide authentication The forests contain the users shown in the following table. The forests contain the network shares shown in the following table. User1 can be assigned permissions for Share3.

![Question 100](images/question100_101_102_1.png)
![Question 100](images/question100_101_102_2.png)
![Question 100](images/question100_101_102_3.png)

- [x] Yes.
- [ ] No.

### Your network contains two Active Directory forests and a domain trust as shown in the following exhibit. The domain trust has the following configurations: Name: adatum.co Type: External Direction: One-way, outgoing Outgoing trust authentication level: Domain-wide authentication The forests contain the users shown in the following table. The forests contain the network shares shown in the following table. User2 can be assigned permissions for Share1.

- [ ] Yes.
- [x] No.

### Your network contains two Active  irectory forests and a domain trust as shown in the following exhibit. The domain trust has the following configurations: Name: adatum.co Type: External Direction: One-way, outgoing Outgoing trust authentication level: Domain-wide authentication The forests contain the users shown in the following table. The forests contain the network shares shown in the following table. User3 can be assigned permissions for Share1.

- [ ] Yes.
- [x] No.

### Your network contains an Active Directory domain named contoso.com. The domain contains group managed service accounts (gMSAs). You have a server named Server1 that runs Windows Server and is in a workgroup. Server1 hosts Windows containers. You need to ensure that the Windows containers can authenticate to contoso.com. Which three actions should you perform in sequence?

![Question 103](images/question103.png)

- [x] Box 1: In contoso.com, generate the Key Distribution Service (KDS) root key. Box 2: On Server1, run New-CredentialSpec. Box 3: On Server1, install and run ccg.exe.
- [ ] Box 1: In contoso.com, generate the Key Distribution Service (KDS) root key. Box 2: On Server1, run New-CredentialSpec. Box 3: From a domain-joined computer, create the credential spec file and copy it to Server1.
- [ ] Box 1: In contoso.com, create the gMSA and a standard user account. Box 2: In contoso.com, generate the Key Distribution Service (KDS) root key. Box 3: On Server1, install and run ccg.exe.
- [ ] Box 1: From a domain-joined computer, create the credential spec file and copy it to Server1. Box 2: In contoso.com, create the gMSA and a standard user account. Box 3:  On Server1, run New-CredentialSpec.
- [ ] Box 1: On Server1, install and run ccg.exe. Box 2: From a domain-joined computer, create the credential spec file and copy it to Server1. Box 3: On Server1, run New-CredentialSpec.

### Your on-premises network contains an Active Directory domain named contoso.com. You have an Azure AD tenant. You plan to sync contoso.com with the Azure AD tenant by using Azure AD Connect cloud sync. You need to create an account that will be used by Azure AD Connect cloud sync. Which type of account should you create?

- [ ] system-assigned managed identity.
- [x] group managed service account (gMSA).
- [ ] user.
- [ ] InetOrgPerson.

### Your network contains an Active Directory Domain Services (AD DS) domain. The domain contains the domain controllers shown in the following table.You need to ensure that if an attacker compromises the computer account of RODC1, the attacker cannot view the Employee-Number AD DS attribute. Which partition should you modify?

![Question 105](images/question105.png)

- [ ] configuration.
- [ ] global catalog.
- [ ] domain.
- [x] schema.

### ...

### Your on-premises network contains an Active Directory Domain Services (AD DS) domain. You plan to sync the domain with an Azure AD tenant by using Azure AD Connect cloud sync. You need to meet the following requirements: Install the software required to sync the domain and Azure AD. Enable password hash synchronization. What should you install, and what should you use to enable password hash synchronization? Use:

![Question 107](images/question107_108.png)

- [ ] Active Directory Administrative Center.
- [ ] Azure AD Connect.
- [ ] The AD FS Management console.
- [x] The Azure portal.

### Your network contains two Active Directory Domain Services (AD DS) forests as shown in the following exhibit. The forests contain the domain controllers shown in the following table. You perform the following actions on DC1: Create a user named User1. Extend the schema with a new attribute named Attribute1. To which domain controllers are User1 and Attribute1 replicated? User1:

![Question 108 part 1](images/question108_109_1.png)
![Question 108 part 2](images/question108_109_2.png)
![Question 108 part 3](images/question108_109_3.png)

- [ ] DC2 only.
- [ ] DC3 only.
- [ ] DC2 and DC3 only.
- [x] DC3 and DC4 only.
- [ ] DC2, DC3, and DC4.

### Your network contains two Active Directory Domain Services (AD DS) forests as shown in the following exhibit. The forests contain the domain controllers shown in the following table. You perform the following actions on DC1: Create a user named User1. Extend the schema with a new attribute named Attribute1. To which domain controllers are User1 and Attribute1 replicated? Attribute1:

![Question 109 part 1](images/question109_110_1.png)
![Question 109 part 2](images/question109_110_2.png)
![Question 109 part 3](images/question109_110_3.png)

- [ ] DC2 only.
- [x] DC4 only.
- [ ] DC2 and DC3 only.
- [ ] DC2, DC3, and DC4.

### Your network contains an Active Directory Domain Services (AD DS) domain. The domain contains the resources shown in the following table. You plan to replicate a volume from Server1 to Server2 by using Storage Replica. You need to configure Storage Replica. Where should you install Windows Admin Center?

![Question 110](images/question110.png)

- [ ] Server1.
- [x] CLIENT1.
- [ ] DC1.
- [ ] Server2.

### You have an on-premises Active Directory Domain Services (AD DS) domain named contoso.com that syncs with Azure AD by using Azure AD Connect. You enable password protection for contoso.com. You need to prevent users from including the word contoso as part of their password. What should you use?

- [x] the Azure Active Directory admin center.
- [ ] Active Directory Users and Computers.
- [ ] Synchronization Service Manager.
- [ ] Windows Admin Center.

### ...

### Overview Company Information ADatum Corporation is a manufacturing company that has a main office in Seattle and two branch offices in Los Angeles and Montreal.Fabrikam Partnership ADatum recently partnered with 2 company named Fabrikam, Inc. Fabrikam is a manufacturing company that has a main office in Boston and a branch office in Orlando. Both companies intend to collaborate on several joint projects. Existing Environment ADatum AD DS Environment The on-premises network of ADatum contains an Active Directory Domain Services (AD DS) forest named adatum.com. The forest contains two domains named adatum.com and east.adatum.com and the domain controllers shown in the following table. Fabrikam AD DS Environment The on-premises network of Fabrikam contains an AD DS forest named fabrikam.com. The forest contains two domains named fabrikam.com and south.fabrikam.com. The fabrikam.com domain contains an organizational unit (OU) named Marketing. Server Infrastructure The adatum.com domain contains the servers shown in the following table. HyperV1 contains the virtual machines shown in the following table. All the virtual machines on HyperV1 have only the default management tools installed. SSPace1 contains the Storage Spaces virtual disks shown in the following table. Azure Resources ADatum has an Azure subscription that contains an Azure AD tenant. Azure AD Connect is configured to sync the adatum.com forest with Azure AD. The subscription contains the virtual networks shown in the following table. The subscription contains the Azure Private DNS zones shown in the following table. The subscription contains the virtual machines shown in the following table. All the servers are in a workgroup. The subscription contains a storage account named storage1 that has a file share named share1. Requirements Planned Changes ADatum plans to implement the following changes:  Sync Data1 to share1.  Configure an Azure runbook named Task1. Enable Azure AD users to sign in to Server1.  Create an Azure DNS Private Resolver that has the following configurations:  Name: Private1  Region: West US  Virtual network: VNet1  Inbound endpoint: SubnetB  Enable users in the adatum.com domain to access the resources in the south.fabrikam.com domain. Technical Requirements ADatum identifies the following technical requirements: The data on SSPace1 must be available always. DC2 must become the schema master if DC1 fails. VM3 must be configured to enable per-folder quotas.Trusts must allow access to only the required resources.  The users in the Marketing OU must have access to storage1. Azure Automanage must be used on all supported Azure virtual machines. A direct SSH session must be used to manage all the supported virtual machines on HyperV1. DC1 fails. You need to meet the technical requirements for the schema master. You run ntdsutil.exe. Which five commands should you run in sequence?

![Question 113 part 1](images/question113_114_1.png)
![Question 113 part 2](images/question113_114_2.png)
![Question 113 part 3](images/question113_114_3.png)
![Question 113 part 4](images/question113_114_4.png)
![Question 113 part 5](images/question113_114_5.png)
![Question 113 part 6](images/question113_114_6.png)
![Question 113 part 7](images/question113_114_7.png)

- [ ][NO_ANSWER]

### Overview -Company Information - ADatum Corporation is a manufacturing company that has a main office in Seattle and two branch offices in Los Angeles and Montreal. Fabrikam Partnership - ADatum recently partnered with 2 company named Fabrikam, Inc. Fabrikam is a manufacturing company that has a main office in Boston and a branch office in Orlando. Both companies intend to collaborate on several joint projects. Existing Environment - ADatum AD DS Environment - The on-premises network of A. Datum contains an Active Directory Domain Services (AD DS) forest named adatum.com. The forest contains two domains named adatum.com and east.adatum.com and the domain controllers shown in the following table. Fabrikam AD DS Environment - The on-premises network of Fabrikam contains an AD DS forest named fabrikam.com. The forest contains two domains named fabrikam.com and south.fabrikam.com. The fabrikam.com domain contains an organizational unit (OU) named Marketing. Server Infrastructure - The adatum.com domain contains the servers shown in the following table. HyperV1 contains the virtual machines shown in the following table. All the virtual machines on HyperV1 have only the default management tools installed. SSPace1 contains the Storage Spaces virtual disks shown in the following table. Azure Resources - ADatum has an Azure subscription that contains an Azure AD tenant. Azure AD Connect is configured to sync the adatum.com forest with Azure AD. The subscription contains the virtual networks shown in the following table. The subscription contains the Azure Private DNS zones shown in the following table. The subscription contains the virtual machines shown in the following table. All the servers are in a workgroup. The subscription contains a storage account named storage1 that has a file share named share1. Requirements - Planned Changes - ADatum plans to implement the following changes:  Sync Data1 to share1. Configure an Azure runbook named Task1. Enable Azure AD users to sign in to Server1. Create an Azure DNS Private Resolver that has the following configurations: Name: Private1 Region: West US Virtual network: VNet1 Inbound endpoint: SubnetB  Enable users in the adatum.com domain to access the resources in the south.fabrikam.com domain. Technical Requirements - ADatum identifies the following technical requirements: The data on SSPace1 must be available always. DC2 must become the schema master if DC1 fails. VM3 must be configured to enable per-folder quotas. Trusts must allow access to only the required resources. The users in the Marketing OU must have access to storage1. Azure Automanage must be used on all supported Azure virtual machines.  A direct SSH session must be used to manage all the supported virtual machines on HyperV1. You need to ensure that access to storage1 for the Marketing OU users meets the technical requirements. What should you implement?

![Question 114 part 1](images/question113_114_1.png)
![Question 114 part 2](images/question113_114_2.png)
![Question 114 part 3](images/question113_114_3.png)
![Question 114 part 4](images/question113_114_4.png)
![Question 114 part 5](images/question113_114_5.png)
![Question 114 part 6](images/question113_114_6.png)
![Question 114 part 7](images/question113_114_7.png)

- [ ] Active Directory Federation Services (AD FS).
- [ ] Azure AD Connect in staging mode.
- [x] Azure AD Connect cloud sync.
- [ ] Azure AD Connect in active mode.

### You use a Group Policy preference to map \\dc1.contoso.com\install as drive H for all users. If a user already has an existing drive mapping for H, the new drive mapping must take precedence. To complete this task, sign in to the required computer or computers.

![Question 115](images/question115.png)

- [x]  1. Open Group Policy Management. 2. Right-click the domain or the required subfolder to create a new GPO, or select an already existing one. Right-click and select Edit to open the Group Policy Management Editor. 3. Go to User Configuration > Preferences > Windows Settings > Drive Maps. 4. Right-click and select New > Mapped Drive. 5. Under the General tab (see Figure below), do the following. 6. Action: Select Create or Update. 7. Location: Specify the full file path, e.g. \\Anjali-dc1\c. Specify: \\dc1.contoso.com\install 8. Reconnect: Enable this to auto connect the drive. 9. Label as: Pick a suitable name for the shared drive, e.g. SharedDrive. 10. Drive Letter: Select a suitable letter for the drive, e.g. K. Specify H 11. Connect as: Enter a username and password if you want users to connect with certain credentials other than their own Windows login credentials. 12. Hide/Show this drive: Select whether you want to hide the folder or make it visible on the network. 13. Hide/Show all drives: Select whether, by default, all the shared drives/folders are hidden or visible.
dc1.contoso.com

### Your network contains an Active Directory Domain Services (AD DS) domain named contoso.com. The domain contains the users shown in the following table. The domain has the Group Policy Objects (GPOs) shown in the following table. The GPOs are configured as shown in the following table.1. When User1 changes their password, at least eight characters must be used for the new password.

![Question 116 part 1](images/question116_117_118_1.png)
![Question 116 part 2](images/question116_117_118_2.png)
![Question 116 part 3](images/question116_117_118_3.png)
![Question 116 part 4](images/question116_117_118_4.png)

- [ ] Yes.
- [x] No.

### Your network contains an Active Directory Domain Services (AD DS) domain named contoso.com. The domain contains the users shown in the following table. The domain has the Group Policy Objects (GPOs) shown in the following table. The GPOs are configured as shown in the following table.1. When User2 changes their password, at least 12 characters must be used for the new password.

![Question 117 part 1](images/question116_117_118_1.png)
![Question 117 part 2](images/question116_117_118_2.png)
![Question 117 part 3](images/question116_117_118_3.png)
![Question 117 part 4](images/question116_117_118_4.png)

- [x] Yes.
- [ ] No.

### Your network contains an Active Directory Domain Services (AD DS) domain named contoso.com. The domain contains the users shown in the following table. The domain has the Group Policy Objects (GPOs) shown in the following table. The GPOs are configured as shown in the following table.1. When User3 changes their password, at least 10 characters must be used for the new password.

![Question 118 part 1](images/question116_117_118_1.png)
![Question 118 part 2](images/question116_117_118_2.png)
![Question 118 part 3](images/question116_117_118_3.png)
![Question 118 part 4](images/question116_117_118_4.png)

- [x] Yes.
- [ ] No.

### Your network contains an Active Directory Domain Services (AD DS) domain named adatum.com. The domain contains a file server named Server1 and three users named User1, User2, and User3. Server1 contains a shared folder named Share1 that has the following configurations: The share permissions for Share1 are configured as shown in the Share Permissions exhibit. Share1 contains a file named File1.bxt. The advanced security settings for File1.txt are configured as shown in the File Permissions exhibit. When User2 connects to \\Server1.adatum.com\Share1, File1.txtis visible.

![Question 119 part 1](images/question119_120_121_1.jpg)
![Question 119 part 2](images/question119_120_121_2.jpg)
![Question 119 part 3](images/question119_120_121_3.jpg)
![Question 119 part 4](images/question119_120_121_3.jpg)

- [ ] Yes.
- [x] No.

### Your network contains an Active Directory Domain Services (AD DS) domain named adatum.com. The domain contains a file server named Server1 and three users named User1, User2, and User3. Server1 contains a shared folder named Share1 that has the following configurations: The share permissions for Share1 are configured as shown in the Share Permissions exhibit. Share1 contains a file named File1.bxt. The advanced security settings for File1.txt are configured as shown in the File Permissions exhibit. When User3 connects to \\Server1.adatum.com\Share1, File1.txtis visible.

![Question 120 part 1](images/question119_120_121_1.jpg)
![Question 120 part 2](images/question119_120_121_2.jpg)
![Question 120 part 3](images/question119_120_121_3.jpg)
![Question 120 part 4](images/question119_120_121_3.jpg)

- [x] Yes.
- [ ] No.

### ...

### ...

### AD DS Environment The network contains an on-premises Active Directory Domain Services (AD DS) forest named contoso.com. The forest contains two domains named contoso.com and canada.contoso.com. The forest contains the domain controllers shown in the following table. All the domain controllers are global catalog servers. Server Infrastructure The network contains the servers shown in the following table. A server named Server4 runs Windows Server and is in a workgroup. Windows Firewall on Servei4 uses the private profile. Server2 hosts three virtual machines named VM1. VM2, and VM3. VM3 is a file server that stores data in the volumes shown in the following table. Group Policies The contoso.com domain has the Group Policies Objects (GPOs) shown in the following table. Existing Identities The forest contains the users shown in the following table. The forest contains the groups shown in the following table. Current Problems When an administrator signs in to the console of VM2 by using Virtual Machine Connection, and then disconnects from the session without signing out another administrator can connect to the console session as the currently signed-in user. Requirements Contoso identifies the following technical requirements: Change the replication schedule for all site links to 30 minutes. Promote Server1 to a domain controller in canada.contoso.com. Install and authorize Server3 as a DHCP server. Ensure that User! can manage the membership of all the groups in ContosoOU3. Ensure that you can manage Server4 from Server1 by using PowerShell removing. Ensure that you can run virtual machines on VM1. Force users to provide credentials when they connect to VM2. On VM3, ensure that Data Deduplication on all volumes is possible. You need to meet the technical requirements for the site links. Which users can perform the required tasks?

![Question 123part 4](images/question123_4.jpg)
![Question 123part 5](images/question123_5.jpg)
![Question 123part 6](images/question123_6.jpg)

- [ ] Admin1 only.
- [ ] Admin1 and Admin3 only.
- [x] Admin1 and Admin2 only.
- [ ] Admin3 only.
- [ ] Admin1, Adrrun2. and Admin3.

### ...

### Overview Fabrikam, Inc. Is a manufacturing company that has a main office In New York and a branch office in Seattle. On-premises Servers The on-premises network contains servers that run Windows Server as shown in the following table. DC1 hosts all the operation master roles. WEB1 and WEB2 run an Internet Information Services (IIS) web app named Webapp1. On-premises Network The New York and Seattle offices are connected by using redundant WAN links. The client computers in each office get IP addresses from their local DHCP server. DHCP! contains a scope named Scope1 that has addresses for the New York office. DHCP2 contains a scope named Scope2 that has addresses for the Seattle office. Group Policy Object (GPOs) The cwp.fabrikam.com domain contains the organizational units (OUs) and custom Group Policy Objects (GPOs) shown in the following table. Requirements: Fabrikam Identifies the following planned changes: Create a single Azure subscription named Sub1 that will contain a single Azure virtual network named Vnet1. Replace the WAN links between the Seattle and New York offices by using Azure Virtual WAN and ExpressRoute. Both on-premises offices will be connected to Vnet1 by using ExpressRoute. Create three Azure file shares named newyorkfiles, seattfefiles, and companyfiles. Create a domain controller named dc3.corp.fabrikam,com in Vnet1. Deploy an Azure Virtual Desktop host pool lo Vnet1. The Azure Virtual Desktop session hosts will be hybrid Azure AD joined. License all servers for Microsoft Defender for servers. Use Azure Policy to enforce configuration management policies on the servers in Azure and on-premises. Networking Requirements Fabrikam identifies the following security requirements: Apply GP04 to the Azure Virtual Desktop session hosts. Ensure that Azure Virtual Desktop user sessions lock after being idle for 10 minutes. Users must be able to control the lockout lime manually from their client computer. Ensure that server administrators request approval before they can establish a Remote Desktop connection to an Azure virtual machine. If the request is approved, the connection must be established within two hours. Prevent user passwords from containing all or part of words that are based on the company name, such as Fab. fabrikam or fsbr! Ensure that all instances of Webapp1 use the same service account. The password of the service account must change automatically every 30 days. Prevent domain controllers from directly contacting hosts on the internet. File Sharing Requirements You need to configure the synchronization of Azure files to meet the following requirements: Ensure that seattlefiles syncs to FS2. Ensure that newyorkfiles syncs to FS1. Ensure that companyfiles syncs to both FS1 and FS2. You need to configure remote administration to meet the security requirements. What should you use?

![Question 125 part 1](images/question125_1.jpg)
![Question 125 part 2](images/question125_2.jpg)

- [x] just in time (JIT) VM access.
- [ ] Azure AD Privileged Identity Management (PIM).
- [ ] the Remote Desktop extension for Azure Cloud Services.
- [ ] an Azure Bastion host.

### You need to meet the security requirements for passwords. Where should you configure the components for Azure AD Password Protection? The Azure AD Password Protection DC agent: [...].

![Question 126](images/question126_127_128.jpg)

- [ ] Locations.
- [ ] DC1 only.
- [x] All the domain controllers.
- [ ] VM1 and VM2.
- [ ] The Azure AD tenant.
- [ ] Answer Area.

### Overview Fabrikam, Inc. Is a manufacturing company that has a main office In New York and a branch office in Seattle. On-premises Servers The on-premises network contains servers that run Windows Server as shown in the following table. DC1 hosts all the operation master roles. WEB1 and WEB2 run an Internet Information Services (IIS) web app named Webapp1. On-premises NetworkThe New York and Seattle offices are connected by using redundant WAN links. The client computers in each office get IP addresses from their local DHCP server. DHCP! contains a scope named Scope1 that has addresses for the New York office. DHCP2 contains a scope named Scope2 that has addresses for the Seattle office.Group Policy Object (GPOs) The cwp.fabrikam.com domain contains the organizational units (OUs) and custom Group Policy Objects (GPOs) shown in the following table. Requirements: Fabrikam Identifies the following planned changes: Create a single Azure subscription named Sub1 that will contain a single Azure virtual network named Vnet1. Replace the WAN links between the Seattle and New York offices by using Azure Virtual WAN and ExpressRoute. Both on-premises offices will be connected to Vnet1 by using ExpressRoute. Create three Azure file shares named newyorkfiles, seattfefiles, and companyfiles. Create a domain controller named dc3.corp.fabrikam,com in Vnet1. Deploy an Azure Virtual Desktop host pool lo Vnet1. The Azure Virtual Desktop session hosts will be hybrid Azure AD joined. License all servers for Microsoft Defender for servers. Use Azure Policy to enforce configuration management policies on the servers in Azure and on-premises. Networking Requirements Fabrikam identifies the following security requirements: Apply GP04 to the Azure Virtual Desktop session hosts. Ensure that Azure Virtual Desktop user sessions lock after being idle for 10 minutes. Users must be able to control the lockout lime manually from their client computer. Ensure that server administrators request approval before they can establish a Remote Desktop connection to an Azure virtual machine. If the request is approved, the connection must be established within two hours. Prevent user passwords from containing all or part of words that are based on the company name, such as Fab. fabrikam or fsbr! Ensure that all instances of Webapp1 use the same service account. The password of the service account must change automatically every 30 days. Prevent domain controllers from directly contacting hosts on the internet. File Sharing Requirements You need to configure the synchronization of Azure files to meet the following requirements: Ensure that seattlefiles syncs to FS2. Ensure that newyorkfiles syncs to FS1. Ensure that companyfiles syncs to both FS1 and FS2. The Azure AD Password Protection proxy service: The Azure AD tenant [...].

![Question 127 part 1](images/question127_128_1.jpg)
![Question 127 part 2](images/question127_128_2.jpg)
![Question 127 part 3](images/question127_128_3.jpg)

- [ ] DC1 only.
- [ ] All the domain controllers.
- [ ] VM1 and VM2.
- [x] The Azure AD tenant.

### Overview Fabrikam, Inc. Is a manufacturing company that has a main office In New York and a branch office in Seattle. On-premises Servers The on-premises network contains servers that run Windows Server as shown in the following table. DC1 hosts all the operation master roles. WEB1 and WEB2 run an Internet Information Services (IIS) web app named Webapp1. On-premises NetworkThe New York and Seattle offices are connected by using redundant WAN links. The client computers in each office get IP addresses from their local DHCP server. DHCP! contains a scope named Scope1 that has addresses for the New York office. DHCP2 contains a scope named Scope2 that has addresses for the Seattle office.Group Policy Object (GPOs) The cwp.fabrikam.com domain contains the organizational units (OUs) and custom Group Policy Objects (GPOs) shown in the following table. Requirements: Fabrikam Identifies the following planned changes: Create a single Azure subscription named Sub1 that will contain a single Azure virtual network named Vnet1. Replace the WAN links between the Seattle and New York offices by using Azure Virtual WAN and ExpressRoute. Both on-premises offices will be connected to Vnet1 by using ExpressRoute. Create three Azure file shares named newyorkfiles, seattfefiles, and companyfiles. Create a domain controller named dc3.corp.fabrikam,com in Vnet1. Deploy an Azure Virtual Desktop host pool lo Vnet1. The Azure Virtual Desktop session hosts will be hybrid Azure AD joined. License all servers for Microsoft Defender for servers. Use Azure Policy to enforce configuration management policies on the servers in Azure and on-premises. Networking Requirements Fabrikam identifies the following security requirements: Apply GP04 to the Azure Virtual Desktop session hosts. Ensure that Azure Virtual Desktop user sessions lock after being idle for 10 minutes. Users must be able to control the lockout lime manually from their client computer. Ensure that server administrators request approval before they can establish a Remote Desktop connection to an Azure virtual machine. If the request is approved, the connection must be established within two hours. Prevent user passwords from containing all or part of words that are based on the company name, such as Fab. fabrikam or fsbr! Ensure that all instances of Webapp1 use the same service account. The password of the service account must change automatically every 30 days. Prevent domain controllers from directly contacting hosts on the internet. File Sharing Requirements You need to configure the synchronization of Azure files to meet the following requirements: Ensure that seattlefiles syncs to FS2. Ensure that newyorkfiles syncs to FS1. Ensure that companyfiles syncs to both FS1 and FS2. A custom banned password list: [...].

![Question 128 part 1](images/question127_128_1.jpg)
![Question 128 part 2](images/question127_128_2.jpg)
![Question 128 part 3](images/question127_128_3.jpg)

- [ ] DC1 only.
- [ ] All the domain controllers.
- [x] VM1 and VM2.
- [ ] The Azure AD tenant.

### AD DS Environment The network contains an on-premises Active Directory Domain Services (AD DS) forest named contoso.com. The forest contains two domains named contoso.com and canada.contoso.com. The forest contains the domain controllers shown in the following table. All the domain controllers are global catalog servers. Server Infrastructure The network contains the servers shown in the following table. A server named Server4 runs Windows Server and is in a workgroup. Windows Firewall on Servei4 uses the private profile. Server2 hosts three virtual machines named VM1. VM2, and VM3. VM3 is a file server that stores data in the volumes shown in the following table. Group Policies The contoso.com domain has the Group Policies Objects (GPOs) shown in the following table. Existing Identities The forest contains the users shown in the following table. The forest contains the groups shown in the following table. Current Problems When an administrator signs in to the console of VM2 by using Virtual Machine Connection, and then disconnects from the session without signing out another administrator can connect to the console session as the currently signed-in user. Requirements Contoso identifies the following technical requirements: Change the replication schedule for all site links to 30 minutes. Promote Server1 to a domain controller in canada.contoso.com. Install and authorize Server3 as a DHCP server. Ensure that User! can manage the membership of all the groups in ContosoOU3. Ensure that you can manage Server4 from Server1 by using PowerShell removing. Ensure that you can run virtual machines on VM1. Force users to provide credentials when they connect to VM2. On VM3, ensure that Data Deduplication on all volumes is possible. You need to meet the technical requirements for VM3 On which volumes can you enable Data Deduplication? A. Synapse Studio

![Question 129](images/question129_1.jpg)
![Question 129](images/question129_2.jpg)
![Question 129](images/question129_3.jpg)
![Question 129](images/question129_4.jpg)
![Question 129](images/question129_5.jpg)
![Question 129](images/question129_6.jpg)

- [ ] D and E only.
- [ ] C, D, E, and F.
- [ ] D only.
- [x] C and D only.
- [ ] D, E, and F only.

### This question is part of a series of questions that present the same scenario. Each question in the series contains a unique solution that might meet the stated goals. Some question sets might have more than one correct solution, while others might not have a correct solution. After you answer a question in this section, you will NOT be able to return to it. As a result, these questions will not appear in the review screen. Your network contains an Active Directory Domain Services.

- [ ] Yes.
- [x] No.

### ...

### Your network contains an Active Directory Domain Services (AD DS) forest named contoso.com. You create the resources shown in the following table. You create the Group Policy Objects (GPOs) shown in the following table. You configure the Group Policy Preferences shown in the following table. If User1 signs in to Comp1, a shortcut named Link4 will appear on the computer's desktop.

![Question 132 part 1](images/question132_133_134_1.jpg)
![Question 132 part 2](images/question132_133_134_2.jpg)
![Question 132 part 3](images/question132_133_134_3.jpg)

- [ ] Yes.
- [x] No.

### Your network contains an Active Directory Domain Services (AD DS) forest named contoso.com. You create the resources shown in the following table. You create the Group Policy Objects (GPOs) shown in the following table. You configure the Group Policy Preferences shown in the following table. If User2 signs in to Comp1, a shortcut named Link will appear on the computer's desktop.

![Question 133 part 1](images/question132_133_134_1.jpg)
![Question 133 part 2](images/question132_133_134_2.jpg)
![Question 133 part 3](images/question132_133_134_3.jpg)

- [x] Yes.
- [ ] No.

### Your network contains an Active Directory Domain Services (AD DS) forest named contoso.com. You create the resources shown in the following table. You create the Group Policy Objects (GPOs) shown in the following table. You configure the Group Policy Preferences shown in the following table. If User3 signs in to Comp1, a shortcut named Link2 will appear on the computer's desktop.

![Question 134 part 1](images/question132_133_134_1.jpg)
![Question 134 part 2](images/question132_133_134_2.jpg)
![Question 134 part 3](images/question132_133_134_3.jpg)

- [x] Yes.
- [ ] No.

### ...

### ...

### ...

### ...

### You deploy a new Active Directory Domain Services (AD DS) forest named contoso.com. The domain contains three domain controllers named DC1, DC2, andDC3.You rename Default-First-Site-Name as Site1.You plan to ship DC1, DC2, and DC3 to datacenters in different locations.You need to configure replication between DC1, DC2, and DC3 to meet the following requirements:✑ Each domain controller must reside in its own Active Directory site.✑ The replication schedule between each site must be controlled independently.✑ Interruptions to replication must be minimized.Which three actions should you perform in sequence in the Active Directory Sites and Services console?

![Question 139](images/question139.jpg)

- [ ] Box 1: Create an additional site link that contains
Site1 and Site2. Box 2: Create two additional sites named Site2 and
Site3. Move DC2 to Site2 and DC3 to Site. Box 3: Remove Site2 from DEFAULTIPSITELINK.
- [x] Box 1: Create two additional sites named Site2 and
Site3. Move DC2 to Site2 and DC3 to Site. Box 2: Create a connection object between DC1
and DC2. Box 3: Create a connection object between DC
and DC3.
- [ ] Box 1:Create a connection object between DC1
and DC2. Box 2: Create a connection object between DC
and DC3. Box 3: Create two additional sites named Site2 and
Site3. Move DC2 to Site2 and DC3 to Site.
- [ ] Box 1: Remove Site2 from DEFAULTIPSITELINK. Box 2: Create two additional sites named Site2 and
Site3. Move DC2 to Site2 and DC3 to Site. Box 3: Create an additional site link that contains
Site1 and Site2.

### ...

### Your network contains an Active Directory domain named contoso.com. The domain contains the computers shown in the following table. On Server3, you create a Group Policy Object (GPO) named GPO1 and link GPO1 to contoso.com. GPO1 includes a shortcut preference named Shortcut1 that has item-level targeting configured as shown in the following exhibit. To which computer will Shortcut1 be applied?

![Question 141](images/question141_1.png)
![Question 141](images/question141_2.png)

- [x] Server3 only.
- [ ] Computer1 and Server3 only.
- [ ] Server2 and Server3 only.
- [ ] Server1, Server2, and Server3 only.

### Your network contains an Active Directory Domain Services (AD DS) forest named contoso.com. The forest contains a child named east.contoso.com and the servers shown in the following table. You need to create a folder for the Central Store to manage Group Policy template files for the entire forest. What should you name the folder, and on which server should you create the folder?

![Question 142](images/question142_1.png)
![Question 142](images/question142_2.png)

- [ ] Name: CentralDefinitions. Server: Server1 only.
- [ ] Name: TemplateDefinitions. Server: DC1, DC2, and Server1.
- [ ] Name: CentralDefinitions. Server: DC1 and DC2 only.
- [x] Name: PolicyDefinitions. Server: DC2 only.

### Your on-premises network contains an Active Directory Domain Services (AD DS) domain. The domain contains the servers shown in the following table. The domain controllers do NOT have internet connectivity. You plan to implement Azure AD Password Protection for the domain. You need to deploy Azure AD Password Protection agents. The solution must meet the following requirements: All Azure AD Password Protection policies must be enforced. Agent updates must be applied automatically. Administrative effort must be minimized. What should you do? Install the Azure AD Password Protection agent on:

![Question 143](images/question143_144_1.png)

- [ ] DC1 only.
- [x] DC1 and DC2 only.
- [ ] DC1, DC2, and RODC1.
- [ ] DC1.

### HYour on-premises network contains an Active Directory Domain Services (AD DS) domain. The domain contains the servers shown in the following table. The domain controllers do NOT have internet connectivity. You plan to implement Azure AD Password Protection for the domain. You need to deploy Azure AD Password Protection agents. The solution must meet the following requirements: All Azure AD Password Protection policies must be enforced. Agent updates must be applied automatically. Administrative effort must be minimized. What should you do? Install the Azure AD Password Protection Proxy on:

![Question 143](images/question143_144_2.png)

- [ ] DC2.
- [ ] RODC1.
- [ ] Server1.
- [x] Server2.

### Which three actions should you perform in sequence to meet the security requirements for Webapp1?

![Question 145](images/question145.jpg)

- [ ] Box 1: Create a standalone managed service account
(SMSA) in AD DS. Box 2: Confiqure the liS application pool to run as
Network Service. Box 3: Configure the lIS application pool to run as a
specified user account.
- [x] Box 1:Create the Key Distribution Services (KDS) root key in AD DS. Box 2: Create a group managed service account (gMSA)
I in Active Directory. Box 3: Configure the lIS application pool to run as a
specified user account.
- [ ] Box 1: Create a system-assigned managed identity in
Azure AD. Box 2: Create a group managed service account (gMSA)
in Active Directory. Box 3: Confiqure the lIS application pool to run as Network Service.
- [ ] Box 1:Confiqure the lIS application pool to run as
Network Service. Box 2: Configure the lIS application pool to run as a
specified user account. Box 3: Create a user-assigned managed identity in Azure AD.

![Question 145](images/question145.jpg)

### You need to configure network communication between the Seattle and New York offices. The solution must meet the networking requirements. What should you configure?

![Question 146](images/question146.jpg)

- [ ] On a Virtual WAN hub: An ExpressRoute gateway. In the offices: A Site to-Site VPN.
- [x] On a Virtual WAN hub:A virtual network gateway. In the offices: An ExpressRoute circuit connection.
- [ ] On a Virtual WAN hub:An ExpressRoute gateway. In the offices: An Azure application gateway.
- [ ] On a Virtual WAN hub:An ExpressRoute circuit connection. In the offices: An on premises data gateway.

### You have servers that have the DNS Server role installed. The servers are configured as shown in the following table. All the client computers in the New York office use Server2 as the DNS server. You need to configure name resolution in the New York office to meet the following requirements: ✑ Ensure that the client computers in New York can resolve names from contoso.com. ✑ Ensure that Server2 forwards all DNS queries for internet hosts to 131. 107.100.200. The solution must NOT require modifications to Server1. Which two components should you configure on Server2?

![Question 147](images/question147.jpg)

- [x] a forwarder.
- [x] a conditional forwarder.
- [ ] a delegation.
- [ ] a secondary zone.
- [ ] a reverse lookup zone.

### AD DS Environment The network contains an on-premises Active Directory Domain Services (AD DS) forest named contoso.com. The forest contains two domains named contoso.com and canada.contoso.com. The forest contains the domain controllers shown in the following table. All the domain controllers are global catalog servers. Server Infrastructure The network contains the servers shown in the following table. A server named Server4 runs Windows Server and is in a workgroup. Windows Firewall on Servei4 uses the private profile. Server2 hosts three virtual machines named VM1. VM2, and VM3. VM3 is a file server that stores data in the volumes shown in the following table. Group Policies The contoso.com domain has the Group Policies Objects (GPOs) shown in the following table. Existing Identities The forest contains the users shown in the following table. The forest contains the groups shown in the following table. Current Problems When an administrator signs in to the console of VM2 by using Virtual Machine Connection, and then disconnects from the session without signing out another administrator can connect to the console session as the currently signed-in user. Requirements Contoso identifies the following technical requirements: Change the replication schedule for all site links to 30 minutes. Promote Server1 to a domain controller in canada.contoso.com. Install and authorize Server3 as a DHCP server. Ensure that User! can manage the membership of all the groups in ContosoOU3. Ensure that you can manage Server4 from Server1 by using PowerShell removing. Ensure that you can run virtual machines on VM1. Force users to provide credentials when they connect to VM2. On VM3, ensure that Data Deduplication on all volumes is possible. You need to meet the technical requirements for Server1. Which users can currently perform the required tasks?

![Question 148](images/question148_1.jpg)
![Question 148](images/question148_2.jpg)
![Question 148](images/question148_3.jpg)
![Question 148](images/question148_4.jpg)
![Question 148](images/question148_5.jpg)
![Question 148](images/question148_6.jpg)


- [ ] Admin1 only.
- [ ] Admin3 only.
- [x] Admin1 and Admin3 only.
- [ ] Admin1 Admin2. and Admm3.

### You need to meet the technical requirements for VM1. Which cmdlet should you run first?

![Question 149](images/question149.jpg)

- [ ] NO ANSWER!

### Which groups can you add lo Group3 and Groups?

![Question 150](images/question150.jpg)

- [x] Group3: Group1 and Group2 only. Group5: Group6 only.
- [ ] Group3: Group6 only. Group5: Group1 only.
- [ ] Group3: Group 1 and Group4 only. Group5: Group4 only.
- [ ] Group3: Group1. Group2, Group4, Group5, and Group6. Group5: Group4 and Group6 only.

### You need to meet the technical requirements for Server4. Which cmdlets should you run on Server1 and Server4?

![Question 151](images/question151.jpg)

- [ ] Server1: Enable-PSRemoting. Server4: Start-Service.
- [ ]Server1:Enable-ServerManagerStandardUserRemoting. Server4: Set-Item.
- [x] Server1: | Set-Item. Server4: Enable-ServerManagerStandardUserRemoting.
- [ ] Server1: Start-Service. Server4: Enable-PSRemoting.

### You have a Microsoft 365 E5 subscription that contains the groups shown in the following table.Which groups can be members of Group1 and Group4?

![Question 152](images/question152.jpg)

- [x] Group1: None of the groups. Group4: Group5 only.
- [ ] Group1: Group2 only. Group4: None of the groups.
- [ ] Group1: Group2 and Group4 only. Group4: Group1, Group2, Group3, and Group5 only.
- [ ] Group1: Group2, Group3, Group4, Group5, and Group6. Group4: Group3 and Groups only.

### Your network contains an Active Directory Domain Services (AD DS) domain named contoso.com. You need to identify which server is the PDC emulator for the domain. Solution: From Active Directory Domains and Trusts, you right-click Active Directory Domains and Trusts in the console tree, and then select Operations Master. Does this meet the goal?

- [x] Yes
- [ ] No

### ...

### ...

### ...

### ...

### ...

### ...

### ...

### Your network contains a multi-site Active Directory Domain Services (AD DS) forest. Each Active Directory site is connected by using manually configured site links and automatically generated connections. You need to minimize the latency for changes to Active Directory. What should you do?

- [ ] For each site links, modify the site link costs.
- [ ] Create a site link bridge that contains all the site links.
- [x] For each site link, modify the options attribute.
- [ ] For each site link, modify the replication schedule.

### Your network contains two Active Directory Domain Services (AD DS) forests named contoso.com and fabrikam.com. Contoso.com contains three child domains named amer.contoso.com, apac.contoso.com, and emea.contoso.com. Fabrikam.com contains a child domain named apac.fabrikam.com. A bidirectional forest trust exists between contoso.com and fabrikam.com. You need to provide users in the contoso.com forest with access to the resources in the fabrikam.com forest. The solution must meet the following requirements: Users in contoso.com must only be added directly to groups in the contoso.com forest. Permissions to access the resources in fabrikam.com must only be granted directly to groups in the fabrikam.com forest. The number of groups must be minimized. Which type of groups should you use to organize the users and to assign permissions?

![Question 162](images/question162.jpg)

- [x] Organize users: Domain global. Assign permissions: Domain local.
- [ ] Organize users: Domain local. Assign permissions: Universal.
- [ ] Organize users: Universal. Assign permissions: Domain global.

### Your network contains two Active Directory forests and a domain trust as shown in the following exhibit. The domain trust has the following configurations: Name: adatum.com. Type: External. Direction: One-way, outgoing. Outgoing trust authentication level: Domain-wide authentication The forests contain the users shown in the following table. The forests contain the network shares shown in the following table. User can be assigned permissions for Share3.

![Question 163 Part 1](images/question163_164_165_1.jpg)
![Question 163 Part 1](images/question163_164_165_2.jpg)
![Question 163 Part 1](images/question163_164_165_3.jpg)

- [x] Yes.
- [ ] No.

### Your network contains two Active Directory forests and a domain trust as shown in the following exhibit. The domain trust has the following configurations: Name: adatum.com. Type: External. Direction: One-way, outgoing. Outgoing trust authentication level: Domain-wide authentication The forests contain the users shown in the following table. The forests contain the network shares shown in the following table. User2 can be assigned permissions for Share1.

![Question 164 Part 2](images/question163_164_165_1.jpg)
![Question 164 Part 2](images/question163_164_165_2.jpg)
![Question 164 Part 2](images/question163_164_165_3.jpg)

- [ ] Yes.
- [x] No.

### Your network contains two Active Directory forests and a domain trust as shown in the following exhibit. The domain trust has the following configurations: Name: adatum.com. Type: External. Direction: One-way, outgoing. Outgoing trust authentication level: Domain-wide authentication The forests contain the users shown in the following table. The forests contain the network shares shown in the following table. User3 can be assigned permissions for Share1.

![Question 165 Part 3](images/question163_164_165_1.jpg)
![Question 165 Part 3](images/question163_164_165_2.jpg)
![Question 165 Part 3](images/question163_164_165_3.jpg)

- [ ] Yes.
- [x] No.

### Your network contains an Active Directory Domain Services (AD DS) domain. The domain contains the domain controllers shown in the following table. You need to configure DC3 to be the authoritative time server for the domain. Which operations master role should you transfer to DC3, and which console should you use?

![Question 166](images/question166.jpg)

- [ ] Role: Domain naming master. Console: Active Directory Domains and Trusts.
- [ ] Role: Infrastructure master. Console: Active Directory Sites and Services.
- [x] Role: PDC emulator. Console: Active Directory Users and Computers.
- [ ] Role: RID master. Console: Active Directory Administrative Center.

### DRAG DROP-Your network contains an Active Directory domain named contoso.com. The domain contains group managed service accounts (gMSAs). You have a server named Server1 that runs Windows Server and is in a workgroup. Server1 hosts Windows containers. You need to ensure that the Windows containers can authenticate to contoso.com. Which three actions should you perform in sequence?

![Question 167](images/question167.jpg)

- [ ] Box 1: From a domain-joined computer, create
a credential spec file and copy the file to Server1. Box 2: In contoso.com, generate a Key Distribution
Service (KDS) root key. Box 3: From a domain-joined computer, create
a credential spec file and copy the file to Server1.
- [ ] Box 1: In contoso.com, create a gMSA and a standard
user account. Box 2: In contoso.com, create a gMSA and a standard
user account. Box 3: On Server1, run New-CredentialSpec.
- [ ] Box 1: On Server1, run New-CredentialSpec. Box 2: On Server1, install and run ccg. exe. Box 3: In contoso.com, generate a Key Distribution
Service (KDS) root key.
- [x] Box 1: In contoso.com, generate a Key Distribution
Service (KDS) root key. Box 2: On Server1, run New-CredentialSpec. Box 3: On Server 1, install and run ceg. exe.

### ...

### Your network contains an on-premises Active Directory Domain Services (AD DS) domain named contoso.com that syncs with an Azure AD tenant. The tenant contains a group named Group1 and the users shown in the following table. Domain/OU filtering in Azure AD Connect is configured as shown in the Filtering exhibit. (Click the Filtering tab.) You review the Azure AD Connect configurations as shown in the Configure exhibit. (Click the Configure tab.) User1 can use self-service password reset (SSPR) to reset his password.

![Question 168 part 1](images/question168_169_170_1.jpg)
![Question 168 part 1](images/question168_169_170_2.jpg)
![Question 168 part 1](images/question168_169_170_3.jpg)

- [x] Yes.
- [ ] No.

### Your network contains an on-premises Active Directory Domain Services (AD DS) domain named contoso.com that syncs with an Azure AD tenant. The tenant contains a group named Group1 and the users shown in the following table. Domain/OU filtering in Azure AD Connect is configured as shown in the Filtering exhibit. (Click the Filtering tab.) You review the Azure AD Connect configurations as shown in the Configure exhibit. (Click the Configure tab.) If User1 connects to Microsoft Exchange Online, an on-premises domain controller provides authentication.

![Question 169 part 2](images/question168_169_170_1.jpg)
![Question 169 part 2](images/question168_169_170_2.jpg)
![Question 169 part 2](images/question168_169_170_3.jpg)

- [x] Yes.
- [ ] No.

### Your network contains an on-premises Active Directory Domain Services (AD DS) domain named contoso.com that syncs with an Azure AD tenant. The tenant contains a group named Group1 and the users shown in the following table. Domain/OU filtering in Azure AD Connect is configured as shown in the Filtering exhibit. (Click the Filtering tab.) You review the Azure AD Connect configurations as shown in the Configure exhibit. (Click the Configure tab.) You can add User2 to Group1 as a member.

![Question 170 part 3](images/question168_169_170_1.jpg)
![Question 170 part 3](images/question168_169_170_2.jpg)
![Question 170 part 3](images/question168_169_170_3.jpg)

- [x] Yes.
- [ ] No.

### Your on-premises network contains an Active Directory Domain Services (AD DS) domain. You plan to sync the domain with an Azure AD tenant by using Azure AD Connect cloud sync. You need to meet the following requirements: Install the software required to sync the domain and Azure AD. Enable password hash synchronization. What should you install, and what should you use to enable password hash synchronization?

![Question 171](images/question171.jpg)

- [ ] Install: Active Directory Administrative Center. Use: Azure AD Connect.
- [ ] Install: The AD FS Management console. Use: The AD FS Management console.
- [ ] Install: The Azure AD Connect provisioning agent. Use: Active Directory Administrative Center.
- [x] Install: Azure AD Connect. Use: The Azure portal.

### Your network contains two Active Directory Domain Services (AD DS) forests as shown in the following exhibit. The forests contain the domain controllers shown in the following table. You perform the following actions on DC1: Create a user named User1. Extend the schema with a new attribute named Attribute1. To which domain controllers are User1 and Attribute1 replicated?

![Question 172](images/question172_1.jpg)
![Question 172](images/question172_2.jpg)
![Question 172](images/question172_3.jpg)

- [x] User1: DC3 and DC4 only. Attribute1: DC4 only.
- [ ] User1: DC2 and DC3 only. Attribute1: DC2 and DC3 only.
- [ ] User1: DC3 only. Attribute1: DC2, DC3, and DC4.
- [ ] User1: DC2 only. Attribute1: DC2 onlv.

### ...

### You deploy a single-domain Active Directory Domain Services (AD DS) forest named contoso.com. You deploy five servers to the domain. You add the servers to a group named ITFarmHosts. You plan to configure a Network Load Balancing (NLB) cluster named NLBCluster.contoso.com that will contain the five servers. You need to ensure that the NLB service on the nodes of the cluster can use a group managed service account (gMSA) to authenticate. Which three PowerShell cmdlets should you run in sequence?

![Question 174](images/question174.jpg)

- [ ] Box 1: Add-ADComputerServiceAccount. Box 2: Add-KdsRootKey. Box 3: Set-KdsConfiguration.
- [ ] Box 1: Set-KdsConfiguration. Box 2: Install-ADServiceAccount. Box 3:Add-ADComputerServiceAccount.
- [ ] Box 1: Add-ADGroupMember. Box 2: Set-KdsConfiguration. Box 3:New-ADServiceAccount.
- [x] Box 1: Add-KdsRootKey. Box 2: New-ADServiceAccount. Box 3: Install-ADServiceAccount.

### You have an on-premises Active Directory Domain Services (AD DS) domain that syncs with an Azure Active Directory (Azure AD) tenant.You have several Windows 10 devices that are Azure AD hybrid-joined.You need to ensure that when users sign in to the devices, they can use Windows Hello for Business. Which optional feature should you select in Azure AD Connect?

- [x] Device writeback.
- [ ] Group writebeack.
- [ ] Azure AD app and attribute filtering.
- [ ] Password writeback.
- [ ] Directory extension attribute sync.

### Your network contains an Active Directory Domain Services (AD DS) forest named contoso.com. The forest contains a child domain named east.contoso.com. In the contoso.com domain, you create two users named Admin1 and Admin2. You need to ensure that the users can perform the following tasks: ✑ Admin1 can create and manage Active Directory sites. ✑ Admin2 can deploy domain controllers to the east.contoso.com domain. The solution must use the principle of least privilege. To which group should you add each user? Hot Area:

![Question 176](images/question176.jpg)

- [ ] Admin1: Contoso Administrators. Admin2: Contoso Administrators.
- [x] Admin1: ContosolDomain Admins. Admin2: East\Domain Admins.
- [ ] Admin1: Contoso\Enterprise Admins. Admin2: ContosolDomain Admins.
- [ ] Admin1: East Administrators. Admin2: East Administrators.

### Your network contains an Active Directory Domain Services (AD DS) forest. The forest contains three Active Directory sites named Site1, Site2, and Site3. Each site contains two domain controllers. The sites are connected by using DEFAULTIPSITELINK. You open a new branch office that contains only client computers. You need to ensure that the client computers in the new office are primarily authenticated by the domain controllers in Site1. Solution: You create an organization unit (OU) that contains the client computers in the branch office. You configure the Try Next Closest Site Group Policy Object (GPO) setting in a GPO that is linked to the new OU. Does this meet the goal?

- [x] Yes.
- [ ] No.

### Your network contains an Active Directory Domain Services (AD DS) forest. The forest contains three Active Directory sites named Site1, Site2, and Site3. Each site contains two domain controllers. The sites are connected by using DEFAULTIPSITELINK. You open a new branch office that contains only client computers. You need to ensure that the client computers in the new office are primarily authenticated by the domain controllers in Site1. Solution: You create a new site named Site4 and associate Site4 to DEFAULTSITELINK. Does this meet the goal?

- [x] Yes.
- [ ] No.

### Your network contains an Active Directory Domain Services (AD DS) forest. The forest contains three Active Directory sites named Site1, Site2, and Site3. Each site contains two domain controllers. The sites are connected by using DEFAULTIPSITELINK. You open a new branch office that contains only client computers. You need to ensure that the client computers in the new office are primarily authenticated by the domain controllers in Site1. Solution: You configure the Try Next Closest Site Group Policy Object (GPO) setting in a GPO that is linked to Site1. Does this meet the goal?

- [x] Yes.
- [ ] No.

### Your network contains an Active Directory Domain Services (AD DS) domain named contoso.com. You need to identify which server is the PDC emulator for the domain. Solution: From Active Directory Sites and Services, you right-click Default-First-Site-Name in the console tree, and then select Properties. Does this meet the goal?

- [x] Yes.
- [ ] No.

### Your network contains a single-domain Active Directory Domain Services (AD DS) forest named contoso.com. The forest contains the servers shown in the following exhibit table. You plan to install a line-of-business (LOB) application on Server1. The application will install a custom Windows service. A new corporate security policy states that all custom Windows services must run under the context of a group managed service account (gMSA). You deploy a root key. You need to create, configure, and install the gMSA that will be used by the new application. Which two actions should you perform?


![Question 182](images/question182.jpg)

- [ ] On Server1, run the setspn command.
- [x] On DC1, run the New-ADServiceAccount cmdlet.
- [x] On Server1, run the Install-ADServiceAccount cmdlet.
- [ ] On Server1, run the Get-ADServiceAccount cmdlet.
- [ ] On DC1, run the Set-ADComputer cmdlet.
- [ ] On DC1, run the Install-ADServiceAccount cmdlet.

###
