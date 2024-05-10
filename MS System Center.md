# Microsoft System Center Suite
Microsoft System Center is a suite of software products designed to simplify the deployment, configuration and management of IT infrastructure and virtualized Software-Defined Data Centers (SDDCs).

## Editions
- Microsoft System Center Standard
- Microsoft System Center Datacenter

## Versions
- Microsoft System Center 2016
- Microsoft System Center 2019
- Microsoft System Center 2022

## Suited Products
- System Center Operations Manager (SCOM)
  > *Monitor health, capacity, and usage across applications, workloads, and infrastructure.*
- System Center Orchestrator
  > *Automate your datacenter tasks; efficiently create and execute runbooks using native PowerShell scripts.*
- System Center Virtual Machine Manager (VMM)
  > *Deploy and manage your virtualized, software-defined datacenter with a comprehensive solution for networking, storage, compute, and security.*
- System Center Service Manager
  > *Automated service delivery tool for incident resolution, change control, and asset lifecycle management.*
- System Center Data Protection Manager (DPM)
  > *Protect your data with backup, storage, and recovery for private cloud deployments, physical machines, clients, and server applications.*
- System Center Configuration Manager (SCCM)
  > *Is an endpoint management solution for Microsoft devices, applications, and servers.*

![obrazek](https://github.com/JiriSlof/KnowledgeBase/assets/168433423/6914f5df-104c-40e8-a3c6-af8bf17768cb)


## License Model
- Server Managed License (SML)
    - System Center Standard SML - Core-based
    - System Center Datacenter SML - Core-based

- Client Managed License (CML)
    - Microsoft Endpoint Configuration Manager CML - OSE / User
    - System Center Endpoint Protection SL - Device / User
    - System Center Data Protection Manager CML - OSE / User
    - System Center Orchestrator CML - OSE / User
    - System Center Operations Manager CML - OSE / User
    - System Center Service Manager CML - OSE / User

![obrazek](https://github.com/JiriSlof/KnowledgeBase/assets/168433423/ef15f8be-c150-48cc-8b47-7a528cade992)

> [!NOTE]  
> *The System Center licensing models requires licenses only for the endpoints that are being managed. Rights to use MS SQL Server and the Management Server software are included.*


## License Rules
- Server Managed Core License (SML)
    - Include right to use Management Server software.
    - Include all the System center products.
    - Give rights to use MS SQL Server.
    - Only available with Software Essurence (SA).      
    - Minimum 8 Core licenses per processor.
    - Minimum 16 Core licenses per server.
 
|    Feature/Right                                                                                                                                                                                                         |                                          Datacenter edition                                                |                                           Standard edition                                                 |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:----------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------:|
|                                                    Number of managed OSEs/Hyper-V isolation                                                                                                                              |                                                    Unlimited                                               |                                                        2*                                                  |
|                                                    Number of managed Windows Server containers                                                                                                                           |                                                    Unlimited                                               |                                                    Unlimited                                               |
|                                                    Configuration Manager                                                                                                                                                 |                                                        ✓                                                   |                                                        ✓                                                   |
|                                                    Data Protection Manager                                                                                                                                               |                                                        ✓                                                   |                                                        ✓                                                   |
|                                                    Endpoint Manager                                                                                                                                                      |                                                        ✓                                                   |                                                        ✓                                                   |
|                                                    Operations Manager                                                                                                                                                    |                                                        ✓                                                   |                                                        ✓                                                   |
|                                                    Service Manager                                                                                                                                                       |                                                        ✓                                                   |                                                        ✓                                                   |
|                                                    Virtual Machine Manager                                                                                                                                               |                                                        ✓                                                   |                                                        ✓                                                   |
|                                                    SQL Technology: right to run management server software and supporting SQL Server Runtime (SQL Server Standard edition)                                               |                                                        ✓                                                   |                                                        ✓                                                   |
|                                                    Manage any type of supported workload                                                                                                                                 |                                                        ✓                                                   |                                                        ✓                                                   |

- Client Managed License (CML)
    - Software Assurance is included with all Client MLs.
    - Client MLs include the right to run the Management Server
software and MS SQL Server.
> [!TIP]  
> *A Server ML Core license must be assigned to each physical core in the server, with a minimum of 8 Core licenses per processor, and a minimum of 16 Core licenses per server.
> For example, a single processor server with 4 cores requires 16 Server ML Core licenses, and a 4-processor server with 8 cores on each processor requires 32 Server ML Core licenses.*


## License Mobility
- License Mobility is benefit of SA.
- License Mobility across Server Farms is NOT available as an SA benefit.

## Related License Suites
- Core Client Access License (CAL) Suite
    - Microsoft Endpoint Configuration Manager
    - System Center Endpoint Protections
- Enterprise Client Access License (CAL) Suite
    - Microsoft Endpoint Configuration Manager
    - System Center Endpoint Protections

## Software Assurance
The following SA benefits are also available for System Center Server Management Licenses:
- 24x7 Problem Resolution Support
- Disaster Recovery Rights
- License Mobility through Software Assurance
- Self-Hosting Use Rights
> [!CAUTION]
> *License Mobility across Server Farms is NOT available as an SA benefit.*


## Downgrading Versions and Editions
*TO BE DEFINED*

## Step-Up License
- Customers who have System Center Standard Server ML Core licenses with active Software ssurance may purchase Step-Up licenses to move to System Center Datacenter Server ML Core licenses.
- The Step-Up license is priced at the difference in price of the two licenses and SA.

## Licensing Virtual Machines (VMs) / Containers
- Microsoft System Center Standard license  
    - The server must be fully licensed with  licenses (same as Core-based licensing for Windows Server).
    - An unlimited number of virtual machines may be run and can be managed on the server.
  
- Microsoft System Center Datacenter license
    - The server must be fully licensed with  licenses (same as Core-based licensing for Windows Server).
    - Only 2 virtual machines may be run on the server.
    - The server must be licensed again to run a further 2 virtual machines. Stacking license.
> [!TIP]  
> *For example, a single processor server with 8 cores requires 16 Core licenses to run 2 VMs.
> A further 16 Core licenses must be assigned to the server to run another 2 VMs.*

## External Links
- Descrription - [link](https://getlicensingready.com/HandoutStore/System%20Center%202022%20v23.10.pdf)
- Licensing Overview - [link](https://getlicensingready.com/HandoutStore/System%20Center%202022%20v23.10.pdf) 
