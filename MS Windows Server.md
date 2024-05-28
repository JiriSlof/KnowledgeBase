# Microsoft Windows Server 
Windows Server is a group of server operating systems that has been developed by Microsoft since 1993.

## Editions
- Windows Server Datacenter
- Windows Server Standard
- Windows Server Essentials
- Windows Server Enterprise (obsolte)

## Versions
- Windows Server 2016
- Windows Server 2019
- Windows Server 2022
- Windows Server 2025

## License Model

#### **Core-based + CAL**
- Core-Based License
	- Windows Server Standard 2/16 Core License
	- Windows Server Datacenter 2/16 Core License
- Client Access License (CAL)
	- Windows Server CAL - User / Device
	- Remote Desktop Services (RDS) CAL - User / Device
	- Active Directory Rights Management Services (ADRMS) CAL - User / Device 
	- Core CAL Suite - User / Device
	- Enterprise CAL Suite - User / Device
	- External Connector (for external users / devices)

![obrazek](https://github.com/JiriSlof/KnowledgeBase/assets/168433423/bec3bbaa-20d1-44e5-bbd9-bd026a8e31d7)

#### **Single Server License**
> A single server license must be assigned to the physical server.

![obrazek](https://github.com/JiriSlof/KnowledgeBase/assets/168433423/e41a4fde-0016-4676-a31c-8043256fd46a)

#### *License model reference*:
| **_Windows Server Edition_** | **Server license** | **Core-Based + CAL** |
|:----------------------------:|:------------------:|:--------------------:|
| Essentials                   |         ✓          |                      |
| Standard                     |                    |           ✓          |
| Datacenter                   |                    |           ✓          |
  

## License Rules

### Core-based License + CAL
- **Core-based License**
	- A Core license must be assigned to each physical core in the server.
	- Core licenses are purchased in 2-packs or 16-packs from resellers.
	- Minimum of 8 Core licenses per processor.
	- Minimum of 16 Core licenses per server.
- **Client Access License (CAL)**
	- Windows Server Client Access Licenses are required for either users or devices.
> [!NOTE]  
> *For example, a single processor server with 4 cores requires 16 Core licenses, and a 4-processor server with 6 cores on each processor requires 32 Core licenses.*

### Single Server License
- A single server license must be assigned to each physical.
- Windows Server Client Access Licenses are NOT required.
- Single Server License model is available only for Windows Server Essentials.

> [!IMPORTANT]  
> - *Windows Server Essentials is restricted to 25 users and 50 devices.*
> - *There is no specific installation media - instead an Essentials product key is used to activate the Standard edition of Windows Server and you get all the same features.*
> - *Windows Server Essentials is available to be purchased through OEMs only.*


# License Mobility & Reassignement
- License Mobility is not available for Windows Server.
- Licenses can be reassigned to servers no more frequently than once every 90 days.
- License Mobility IS available for the External Connector licenses.

## License Suites
- Core Infrastructure Server (CIS) Suite Standard
- Core Infrastructure Server (CIS) Suite Datacenter

## Software Assurance
1. 24x7 Problem Resolution Support
2. Disaster Recovery Rights (SA required for both Serverlicenses and CALs)
3. E-Learning
4. Planning Services
5. Self-Hosting Use Rights
6. Eligibility for Step-Up license
7. Possibility to license per Virtual Machine (VM)

## Licensing External Users
External users can be licensed with either individual User or Device CALs or with a Windows Server External Connector license.
- A physical server must be licensed appropriately with Windows Server Standard or Datacenter licenses and then a single External Connector license is assigned to the server. There is just one edition of the External Connector license used regardless of whether the  underlying server is licensed with Windows Server Standard or Datacenter edition.
- The External Connector license allows unlimited external users to connect to and use the services of the physical server and any virtual machines running on the server.
- If an organization has more than approximately 70 external users, it is likely to be most cost effective to use an External Connector license to license those users.

![obrazek](https://github.com/JiriSlof/KnowledgeBase/assets/168433423/42a8dfed-4e74-4229-bba2-58fcaf15225c)

## Downgrade Rights
Customers can choose to deploy an earlier version and, sometimes, an alternative edition.

#### *Downgrade rights reference*:
|    **Licensed Product**   	|                               **Target Edition**                               	| **Target Version** 	|
|:-------------------------:	|:-----------------------------------------------------------------------------------:	|:------------------:	|
| Windows Server Datacenter 	| Windows Server Datacenter <br>Windows Server Standard <br>Windows Server Essentials 	|   same or earlier  	|
|  Windows Server Standard  	|                Windows Server Standard <br>Windows Server Essentials                	|   same or earlier  	|
| Windows Server Essentials 	| Windows Server Essentials                                                           	|   same or earlier  	|

## Step-Ups License
- Customers who have existing Windows Server Standard Core licenses with Software Assurance may purchase Step-Up licenses to move to Windows Server Datacenter Core licenses.
- The Step-Up license is priced at the difference in price of the two licenses and SA.

## Licensing Virtual Machines (VMs) / Containers
####  Windows Server Datacenter
- The server must be fully licensed with Core licenses (as described inthe Core-based Licensing section).
- An unlimited number of virtual machines may be run on the server.
![obrazek](https://github.com/JiriSlof/KnowledgeBase/assets/168433423/1774d347-a044-4bdc-83ab-0e62b6525f0a)

####  Windows Server Standard
- The server must be fully licensed with Core licenses (as described inthe Core-based Licensing section)
- Only 2 virtual machines may be run on the server.
- The server must be licensed again to run a further 2 virtual machines (license stacking).
	
> [!TIP]  
> *For example, a single processor server with 8 cores requires 16 Core licenses to run 2 VMs. A further 16 Core licenses must be assigned to the server to run another 2 VMs.*

![Bez názvu](https://github.com/JiriSlof/KnowledgeBase/assets/168433423/73a810dc-d27b-441a-a8b5-a41d6152c64f)

####  Windows Server Essentials
- Host virtualization rights and rights to run in a single physical or virtual OSE.
- Restricted to 25 user accounts and 50 devices.
   
####  License for Virtual Machine (only with SA)
- Introduced in October 2022 for customers with Software Assurence or Subscription licenses.
- All virtual cores in a virtual machine must be licensed.
- Minimum of 8 Core licenses assigned to a virtual machine.
- Windows Server Client Access Licenses (CALs) are required for either users or devices.
  	  
> [!NOTE]  
> - *CALs must also have active SA or be subscription licenses. Note that this includes licenses such as Microsoft 365 E3 which is a subscription license including CAL Equivalent rights for Windows Server.*
> - *Customers choosing this licensing model do not have rights to run Windows Server in the physical Operating System Environment (OSE).*

![obrazek](https://github.com/JiriSlof/KnowledgeBase/assets/168433423/28eb8cc6-4672-463d-a071-35e3d2a185e3)

1. Scenario: **Silgle Server**
![obrazek](https://github.com/JiriSlof/KnowledgeBase/assets/168433423/aa03f606-3680-47f9-8599-6bd789c76699)
2. Scenario: **Two Servers**
![obrazek](https://github.com/JiriSlof/KnowledgeBase/assets/168433423/061e1fef-8a8a-464c-a2fc-fe490070e916)

## Failover Scenarios
### License across Server Farm
- As the Mobility is not available for Windows Server proper licenses must be assigned to all servers in Server Farm.
- Windows Server Datacenter is the ussulay only reliable option due to possibility to run unlimited number of VMs.
![obrazek](https://github.com/JiriSlof/KnowledgeBase/assets/168433423/72520a3e-9ca3-414e-a039-cd0f3745543b)

### License across Server Farm for Virtual Machine
- Elibility to use license model for VM is restricted to custmers using Core licenses and CALs with Software Assurance or Software Subscriptions licenses.
![obrazek](https://github.com/JiriSlof/KnowledgeBase/assets/168433423/e32dbfe5-d5a6-4ac1-9b4e-b00bf5629e16)


## Volume Activation
- Key Management Services (KMS)	
- Multiple Activation Key (MAK)
- Active Directory-based activation

## Servicing Channels
- Long-Therm Servicing Channel (LTSC)
	- Feature updates every 2-3 years
	- Regular cadense for security and quality fixes
	- Each LTS has 5years mainstream + 5years extended support
- Semi-Annual Channel (obsolete)
	
## External Links
- Overview - [link](https://getlicensingready.com/HandoutStore/Licensing%20Windows%20Server%202022%20on-premises%20v24.10.pdf)
- OnPrem Video Edu - [link](https://youtu.be/Lv_Qm6cZhOY?si=pJDviDzLxkjib3nu)
- License by VM - [link](https://getlicensingready.com/HandoutStore/Licensing%20Windows%20Server%20by%20virtual%20machine%20v23.30.pdf)
- License by VM Video Edu - [link](https://www.youtube.com/watch?v=MmFRzdbJIxs&t=5s)
- Licensing Winser with Virt. Technologies -  [link](https://www.licensingschool.co.uk/wp-content/uploads/2022/10/Licensing_Windows_Server_for_use_with_virtualization_technologies-Oct-2022.pdf)
- Windows Server 2022 Licensing Guide - [link](https://bit.ly/3M8KrTq)
