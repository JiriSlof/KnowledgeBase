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

## License Model
- **Core-based + CAL**
	> A Core license must be assigned to each physical core in the server.
- **Single Server license**
	> A single server license must be assigned to the physical server.
- **Service Provider License Agreement (SPLA)**
	> Program for service providers.

#### *License model reference*:
| **_Windows Server Edition_** | **Server license** | **Core-Based + CAL** |
|:----------------------------:|:------------------:|:--------------------:|
| Essentials                   |         ✓          |                      |
| Standard                     |                    |           ✓          |
| Datacenter                   |                    |           ✓          |
  

## License Rules
#### Core-based license + CAL
- A Core license must be assigned to each physical core in the server.
- Windows Server Client Access Licenses are required for either users or devices.
- Core licenses are purchased in 2-packs or 16-packs from resellers.
- Minimum of 8 Core licenses per processor.
- Minimum of 16 Core licenses per server.

> [!NOTE]  
> *For example, a single processor server with 4 cores requires 16 Core licenses, and a 4-processor server with 8 cores on each processor requires 32 Core licenses.*

![obrazek](https://github.com/JiriSlof/KnowledgeBase/assets/168433423/bec3bbaa-20d1-44e5-bbd9-bd026a8e31d7)

#### Single server license
- A single server license must be assigned to each physical.
- Windows Server Client Access Licenses are NOT required.

![obrazek](https://github.com/JiriSlof/KnowledgeBase/assets/168433423/e41a4fde-0016-4676-a31c-8043256fd46a)


## License Mobility
1. License Mobility is not available for Windows Server.
2. Licenses can be reassigned to servers no more frequently than once every 90 days.
3. License Mobility IS available for the External Connector licenses.

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

#### *Access licenses:*
- Windows Server - User / Device CAL 
- Remote Desktop Services (RDS) - User / Device CAL
- Active Directory Rights Management Services (ADRMS) - User / Device CAL
- Core CAL Suite - User / Device CAL
- Enterprise CAL Suite - User / Device CAL
- External Connector (for external users / devices)

![obrazek](https://github.com/JiriSlof/KnowledgeBase/assets/168433423/42a8dfed-4e74-4229-bba2-58fcaf15225c)


## Downgrade Rights
Customers can choose to deploy an earlier version and, sometimes, an alternative edition.

#### *Downgrade rights reference*:
|    **Licensed Product**   	|                               **Target Edition**                               	| **Target Version** 	|
|:-------------------------:	|:-----------------------------------------------------------------------------------:	|:------------------:	|
| Windows Server Datacenter 	| Windows Server Datacenter <br>Windows Server Standard <br>Windows Server Essentials 	|   same or earlier  	|
|  Windows Server Standard  	|                Windows Server Standard <br>Windows Server Essentials                	|   same or earlier  	|
| Windows Server Essentials 	| Windows Server Essentials                                                           	|                    	|

## Step-Ups License
- Customers who have existing Windows Server Standard Core licenses with Software Assurance may purchase Step-Up licenses to move to Windows Server Datacenter Core licenses.
- The Step-Up license is priced at the difference in price of the two licenses and SA.

## Licensing Virtual Machines (VMs) / Containers
- Windows Server Datacenter
	- The server must be fully licensed with Core licenses (as described inthe Core-based Licensing section).
	- An unlimited number of virtual machines may be run on the server.
![obrazek](https://github.com/JiriSlof/KnowledgeBase/assets/168433423/1774d347-a044-4bdc-83ab-0e62b6525f0a)

- Windows Server Standard
	- The server must be fully licensed with Core licenses (as described inthe Core-based Licensing section)
	- 2 virtual machines may be run on the server.
	- The server must be licensed again to run a further 2 virtual machines (license stacking).
	
> [!TIP]  
> *For example, a single processor server with 8 cores requires 16 Core licenses to run 2 VMs. A further 16 Core licenses must be assigned to the server to run another 2 VMs.*

![obrazek](https://github.com/JiriSlof/KnowledgeBase/assets/168433423/7c941e8a-08bd-4da8-b475-37d6e4d0974e)

- Windows Server Essentials
	- Host virtualization rights and rights to run in a single physical or virtual OSE.
	- Restricted to 25 user accounts and 50 devices.
   
- License for Virtual Machine (only with SA)

## Failover Scenarios

### License across Server Farm
- As the Mobility is not available for Windows Server proper licenses must be assigned to all servers in Server Farm.
- Windows Server Datacenter is the ussulay only reliable option due to possibility to run unlimited number of VMs.
![obrazek](https://github.com/JiriSlof/KnowledgeBase/assets/168433423/72520a3e-9ca3-414e-a039-cd0f3745543b)

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
