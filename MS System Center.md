# Microsoft System Center
The System Center licensing models requires licenses only for the endpoints that are being managed. Rights to SQL Server and the Management Server software are included.

## Editions
- Microsoft System Center Standard
- Microsoft System Center Datacenter

## Versions
- Microsoft System Center 2016
- Microsoft System Center 2019
- Microsoft System Center 2022

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


## License Restrictions / Benefits
- Server Managed Core License (SML)
    - Include right to use Management Server software.
    - Include all the System center products.
    - Give rights to use MS SQL Server.
    - Only available with Software Essurence (SA).      
    - Minimum 8 Core licenses per processor.
    - Minimum 16 Core licenses per server.
      
A Server ML Core license must be assigned to each physical core in the server, with a minimum of 8 Core licenses per processor, and a minimum of 16 Core licenses per server.
For example, a single processor server with 4 cores requires 16 Server ML Core licenses, and a 4-processor server with 8 cores on each processor requires 32 Server ML Core licenses.

- Client Managed License (CML)
    - Software Assurance is included with all Client MLs.
    - Client MLs include the right to run the Management Server
software and MS SQL Server.

## License Mobility
- Licenses can be reassigned to servers no more frequently than once every 90 days.
- License Mobility is benefit of SA.
- License Mobility across Server Farms is NOT available as an SA benefit.

## License Suites
- Core CAL Suite
    - Microsoft Endpoint Configuration Manager
    - System Center Endpoint Protections
- Enterprise CAL Suite
    - Microsoft Endpoint Configuration Manager
    - System Center Endpoint Protections

## Software Assurance
The following SA benefits are also available for System Center Server Management Licenses:
- 24x7 Problem Resolution Support
- Disaster Recovery Rights
- License Mobility through Software Assurance
- Self-Hosting Use Rights
Note that License Mobility across Server Farms is NOT available as an SA benefit.

## Licensing External Users
- SharePoint Standard CAL - User / Device CAL
- SharePoint Standard + Enterprise CAL - User / Device CAL

## Downgrading Versions and Editions
TBD

## Step-Ups
Customers who have System Center 2022 Standard Server ML Core licenses with active Software ssurance may purchase. Step-Up licenses to move to System Center 2022 Datacenter Server ML ore licenses.
The Step-Up license is priced at the difference in price of the two licenses and SA.

## Licensing Virtual Machines (VMs) / Containers
- Microsoft System Center Standard license  
    - The server must be fully licensed with  licenses (same as Core-based licensing for Windows Server).
    - An unlimited number of virtual machines may be run and can be managed on the server.
  
- Microsoft System Center Datacenter license
    - The server must be fully licensed with  licenses (same as Core-based licensing for Windows Server).
    - Only 2 virtual machines may be run on the server.
    - The server must be licensed again to run a further 2 virtual machines. Stacking license.

For example, a single processor server with 8 cores requires 16 Core licenses to run 2 VMs. A further 16 Core licenses must be assigned to the server to run another 2 VMs.

## External Links
Descrription - https://www.microsoft.com/en-us/licensing/product-licensing/system-center
Licensing Overview - https://getlicensingready.com/HandoutStore/System%20Center%202022%20v23.10.pdf
