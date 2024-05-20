# Microsoft SharePoint Server

## Editions
- SharePoint Server
- SharePoint Server Subscription Edition (Online)

## Versions
- SharePoint Enterprise 2016
- SharePoint Enterprise 2019

## Requirements
- Microsoft Windows Server
  - SharePoint Server solution has an infrastructure requirement for Windows Server.
  - Users therefore need to be covered with the relevant licenses for this product.
- Microsoft SQL Server
  - SharePoint Server solution has an infrastructure requirement for Microsoft SQL Server.
  - Users must be licensed in the underlying infrastructure with the relevant licenses.


## License model
#### **Server License + CAL**
> Purchase a Server license for each server, and then purchase Client Access Licenses (CALs) for users or devices.
- **Server License**
  - SharePoint Server License
- **Client Acess License (CAL)**
  - SharePoint Standard CAL - User / Device CAL
  - SharePoint Enterprise CAL - User / Device CAL
 
> [!WARNING]
> - *SharePoint Enterprise CAL is only the additive CAL.*
> - *SharePoint Enterprise CAL can be added only to user / device with assigned SharePoint Standard CAL.*

## License Rules
### **Server License** (per Instance)
- Microsoft SharePoint Server license must be assigned to each server to run SharePoint Server services.
- For Products under the Server/CAL License Model, customer may use one Running Instance of server software in either a Physical OSE or Virtual OSE on a Licensed Server for each License it acquires.

### **Client Acess License (CAL)**
Microsoft SharePoint Server offers different levels of functionality, and there are CALs which correspond to this.
- **SharePoint Standard CAL**
  > Delivers only the core capabilities of SharePoint.
  - *Sites* - a single infrastructure for all your business websites.
  - *Communities* - an integrated collaboration platform.
  - *Content* - enterprise content management (ECM) for the masses.
  - *Search* - people and expertise search, visual previews, visual best bets.
- **SharePoint Enterprise  CAL**
  >  Delivers the full capabilities of SharePoint.
  - *Sites* - a single infrastructure for all your business websites.
  - *Communities* - an integrated collaboration platform.
  - *Content* - ECM for the masses.
  - *Search* - standard search features plus entity extraction, video search, item recommendations.
  - *Business solutions* - includes Access Services and InfoPath Services.
  - *Business Intelligence* - for everyone (includes Power View, PerformancePoint Services, Excel Services, and Visio Services).

![obrazek](https://github.com/JiriSlof/KnowledgeBase/assets/168433423/2a66945f-305b-4dc1-9134-f41afe46c6c9)

#### *Deployment Model Reference*:
Requirement of Client Access Licenses (CALs) for internal users is based on content type.
SharePoint Server can be implemented in 3 different deployment scenarios "Intranet", "Extranet" and "Internet".
![obrazek](https://github.com/JiriSlof/KnowledgeBase/assets/168433423/a727843b-776b-4d62-8cff-21b1c04abb95)

1. Scenario: **Intranet**
  > Information that is accessible inside the firewall to internal users only.
  - SharePoint Server license required for Server.
  - Client Access Licenses (CALs) for either users or devices.
  - External users does not have access.
![obrazek](https://github.com/JiriSlof/KnowledgeBase/assets/168433423/02763c26-88f5-4ea9-acd6-7aad7bca5077)

2. Scenario: **Extranet**
  > Information that is accessible inside the firewall to internal users and named external users only.
  - SharePoint Server license required for Server.
  - Client Access Licenses (CALs) for either users or devices.
  - No CALs required for external users.
![obrazek](https://github.com/JiriSlof/KnowledgeBase/assets/168433423/533730f2-eec9-4a24-9a91-32c10fd60e65)

3. Scenario: **Internet**
  > Information that is publicly accessible to all internal and external users.
  - SharePoint Server license required for Server.
  - No CALs required for either users or devices.
  - No CALs required for external users.
![obrazek](https://github.com/JiriSlof/KnowledgeBase/assets/168433423/b36ece15-3ac4-46ee-9a6c-6ced4098cae8)


## License Mobility
- License Mobility is not available for SharePoint Server.
- Licenses can be reassigned to servers no more frequently than once every 90 days.
- License Mobility across Server Farm is benefit of Software Assurence.

## License Suites
- Microsoft Core CAL Suite
  > Contains SharePoint Server Standard CAL.
- Microsoft Enterprise CAL Suite
  > Contains SharePoint Server Enterprise CAL.

## Software Assurence
- SharePoint Server licenses purchased with Software Assurance have License Mobility across Server Farms rights which allows the reassignment of Server licenses to other physical servers in a server farm as often as required.
- Customers with active Software Assurance may alternatively deploy SharePoint Server Subscription Edition.

## Licensing External Users
No CALs are required for external users.

## Downgrading Rights
None.

## Licensing Virtual Machines (VMs) / Containers
A Server license must be assigned to a single physical server which licenses SharePoint Server to be run in either the physical operating system environment or a single virtual machine on that server.

## Failover Scenarios
####  Server License without SA
- Assign Server license to a physical server to recieve rights to run the application instance in eather a physical or virtual operating system environment.
- The Server license must be assigned to each server in Server Farms for single Exchage Server in automatic failover scenario.
![obrazek](https://github.com/JiriSlof/KnowledgeBase/assets/168433423/ef2c0e21-dead-463f-917a-b4c9775c0dac)

####  Server License with SA
- Assign Server license to a physical server to recieve rights to run the application instance in eather a physical or virtual operating system environment.
- Adding the Software Assurence (SA) to the license provides rights for License Mobility across Server Farms. So the Server license can be moved to another physical server as often as required.
![obrazek](https://github.com/JiriSlof/KnowledgeBase/assets/168433423/b546f4d4-b7c9-4b95-a73d-229a0df8a4fc)


## External Links
- Overview - [Link](https://getlicensingready.com/HandoutStore/SharePoint%20Server%202019%20v22.40.pdf)
- Video EDU - [Link](https://youtu.be/z9oeP8VHap4?si=JeLuv1IGVpeerItv)
- MS Sharepoint Server Licensing- [Link](https://download.microsoft.com/download/3/D/4/3D42BDC2-6725-4B29-B75A-A5B04179958B/Licensing_Microsoft_SharePoint_Server.pdf)
