# Microsoft Exchange Server
Microsoft Exchange Server is a mail server and calendaring server and server managing your contacts developed by Microsoft. It runs exclusively on Windows Server operating system.

## Editions
- Microsoft Exchange Server Standard
- Microsoft Exchange Server Enterprise

## Versions
- Microsoft Exchange Server 2016
- Microsoft Exchange Server 2019

## Requirements
- Microsoft Windows Server
> An Exchange Server solution has an infrastructure requirement for Windows Server. Users therefore need to be covered with the relevant licenses for this product.

## License model
#### **Server License + CAL**
> Purchase a Server license for each server, and then purchase Client Access Licenses (CALs) for either users or devices.
- **Server License**
  - Exchange Server Standard License
  - Exchange Server Enterprise License
- **Client Acess License (CAL)**
  - Exchange Server Standard CALs - User / Device
  - Exchange Server Enterprise CALs - User / Device

![obrazek](https://github.com/JiriSlof/KnowledgeBase/assets/168433423/246e540a-7b45-4d7f-8665-87d1b38a063c)

## License Rules
- **Server License**
    - A single server license must be assigned to the physical server.
    - Exchange Server Standard for small to midsize organizations with limited scalability requirements with fewer users (limited to 1-5 database/s per server).
    - Exchange Server Enterprise for larger organizations with high scalability requirements with a large number of users, or for high availability within clustered environments (limited to 1-100 database/s per server).
- **Client Acess License (CAL)**
    - A Client Access Licenses (CALs) must be purchased for either users or devices.
    - Exchange Server Standard CALs - access fundamental email and calendar information.
    - Exchange Server Enterprise CAL - Unified Messaging, integrated archiving functionality, and information protection capabilities.
    - Exchange Server Enterprise CAL with Services with active SA - includes the rights to Data Loss Prevention and Exchange Online Protection.

> [!IMPORTANT]  
> - *Standard or Enterprise CALs can be used with either Standard or Enterprise Server editions.*
> - *Choose the Server license based on the required scalability and the CALs based on the required functionality.*

> [!WARNING]
> - *Exchange Server Enterprise CAL is only the additive CAL.*
> - *Exchange Server Enterprise CAL can be added only to user / device with assigned Exchange Server Standard CALs.*


#### *Client Acess License (CAL) feature reference*:
| Features                                                                                                                                     	|          Standard CAL          	|        Standard + Enterprise CAL       	|
|----------------------------------------------------------------------------------------------------------------------------------------------	|:------------------------------:	|:--------------------------------------:	|
| Email, calendar, contacts, and tasks                                                                                                         	|                 ✓                	|                     ✓	                   	|
| Outlook on the web (Internet Explorer, Firefox, Chrome, Safari, and Edge support)                                                            	|                 ✓               	|                     ✓	                   	|
| Apps for Outlook and Outlook on the web                                                                                                      	|                 ✓               	|                     ✓	                 	|
| Site mailboxes2                                                                                                                              	|                 ✓               	|                     ✓	                  	|
| Role-based access control (RBAC) capabilities                                                                                                	|                 ✓               	|                     ✓	                  	|
| Journaling                                                                                                                                   	|            Per database        	|         Per user/distribution list     	|
| Journal decryption                                                                                                                           	|                                	|                     ✓	                  	|
| Retention policies                                                                                                                           	|         Default and custom     	|             Default and custom         	|
| In-Place Archive2                                                                                                                            	|                                	|                     ✓	                  	|
| Multi-mailbox search                                                                                                                         	|                                	|                     ✓	                  	|
| In-Place Hold2                                                                                                                               	|                                	|                     ✓	                  	|
| Information protection and control (IPC): transport protection rules,  Outlook protection rules, Information Rights Management (IRM) search  	|                                	|                     ✓	                  	|

## License Mobility
- License Mobility is not available for Exchange Server.
- Licenses can be reassigned to servers no more frequently than once every 90 days.
- License Mobility across Server Farms IS benefit of Software Assurance.

## License Suites
TBD

## Software assurance
- Exchange Server licenses purchased with Software Assurance have License Mobility across Server Farms rights which allows the reassignment of Server licenses to other physical servers in a server farm as often as required.
- An Exchange Server Enterprise CAL with Services with active Software Assurance includes the rights to Data Loss Prevention and Exchange Online Protection.

## Licensing external users
- External users are users who are not the licensee’s or its affiliates’ employees or on-site agents or contractors.
- External users are licensed by the Exchange Server license and there are no requirements for CALs or other licenses for these users.

## Downgrading versions and editions
TBD

## Licensing Virtual Machines (VMs) / Containers
A Server license must be assigned to a single physical server which licenses Exchange Server to be run in either the physical operating  system environment or a single virtual machine on that server.

## Failover Scenarios
####  Server license without SA
- Assign Server license to a physical server to recieve rights to run the application in eather a physical or virtual operating system environment.
- The Server license must be assigned to each server in Server Farms for single Exchage Server in automatic failover scenario.
![obrazek](https://github.com/JiriSlof/KnowledgeBase/assets/168433423/ef2c0e21-dead-463f-917a-b4c9775c0dac)

####  Server license with SA
![obrazek](https://github.com/JiriSlof/KnowledgeBase/assets/168433423/b546f4d4-b7c9-4b95-a73d-229a0df8a4fc)
- Assign Server license to a physical server to recieve rights to run the application in eather a physical or virtual operating system environment.
- Adding the Software Assurence (SA) to the license provides rights for License Mobility across Server Farms. So the Server license can be moved to another physical server as often as required.

## Clients
Users have a choice of clients to access their Exchange mailbox:
- Microsoft Outlook
    > Is the corporate Exchange client, which is part of Office Standard or Professional Plus and can also be purchased standalone
- Outlook on the web
    > Enables users to access their Exchange mailbox from almost any web browser.
- Android / iOS Apps
    > Mail/Calendar/Outlook Apps for Android and iOS devices are available from the relevant stores.

> [!IMPORTANT]  
> *Note that users accessing their Exchange mailbox in any of these ways must be licensed with the relevant Exchange Server CALs, dependent on the functionality they will be using.*

## External Links
- Overview - [Link](https://www.getlicensingready.com/HandoutStore/Exchange%20Server%202019%20v22.40.pdf)
- Video EDU - [Link](https://youtu.be/z9oeP8VHap4?feature=shared)
- Exchange Server Cal - [Link](https://www.microsoft.com/cs-cz/microsoft-365/exchange/microsoft-exchange-server-licensing-licensing-overview)
- Exchnage Server FAQ - [Link](https://www.microsoft.com/cs-cz/microsoft-365/exchange/microsoft-exchange-licensing-faq-email-for-business)
