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
- Windows Server - User / Device CAL 
- Remote Desktop Services (RDS) - User / Device CAL
- Active Directory Rights Management Services (ADRMS) - User / Device CAL
- Core CAL Suite - User / Device CAL
- Enterprise CAL Suite - User / Device CAL
- External Connector (for external users / devices)

## Downgrade Rights
- ***Windows Server Datacenter***<br>
May be downgraded to any version of Windows Server Datacenter, Enterprise, Standard or Essentials.
- ***Windows Server Standard***<br>
May be downgraded to any version of Windows Server Enterprise, Standard or Essentials.
- ***Windows Server Essentials***<br>
May be downgraded to any previous version of Windows Server Essentials.

## Step-Ups License
The Software Assurenece provides eligilibility to purchase Step-Up licenses allowing move from Win STD to Win DC.
Set-Up licese costs just price difference between STD+SA and DC+SA. 

## Licensing Virtual Machines (VMs) / Containers
- Windows Server Datacenter
	- The server must be fully licensed with Core licenses (as described inthe Core-based Licensing section)
	- An unlimited number of virtual machines may be run on the server.
- Windows Server Standard
	- The server must be fully licensed with Core licenses (as described inthe Core-based Licensing section)
	- 2 virtual machines may be run on the server.
	- The server must be licensed again to run a further 2 virtual machines. *
	
	For example, a single processor server with 8 cores requires 16 Core
	licenses to run 2 VMs. A further 16 Core licenses must be assigned to
	the server to run another 2 VMs.
- Windows Server Essentials
	- Host virtualization rights and rights to run in a single physical or virtual OSE
	- Restricted to 25 user accounts and 50 devices
- License for Virtual Machine (only with SA)

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
	
