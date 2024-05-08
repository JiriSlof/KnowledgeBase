# Microsoft Exchange Server
Microsoft Exchange Server is a mail server and calendaring server and server managing your contacts developed by Microsoft. It runs exclusively on Windows Server operating system.

## Editions
- Microsoft Exchange Server Standard
- Microsoft Exchange Server Enterprise

## Versions
- Microsoft Exchange Server 2016
- Microsoft Exchange Server 2019

## License model
#### **Server License + CAL**
> Purchase a Server license for each server, and then purchase Client Access Licenses (CALs) for either users or devices.
- **Server License**
  - Exchange Server Standard License
  - Exchange Server Enterprise License
- **Client Acess License (CAL)**
  - Exchange Server Standard CALs - User / Device
  - Exchange Server Enterprise CALs - User / Device
 
![image](https://github.com/JiriSlof/KnowledgeBase/assets/168433423/1b522288-91e8-4322-bc14-ca8b3c19b3f1)

## License Rules
- **Server License**
    - A single server license must be assigned to the physical server.
    - Choose Exchange Server Standard for small to midsize organizations with limited scalability requirements with fewer users.
    - Choose Exchange Server Enterprise for larger organizations with high scalability requirements with a large number of users, or for high availability within clustered environments.
- **Client Acess License (CAL)**
    - A Client Access Licenses (CALs) must be purchased for either users or devices.
    - Exchange Server Standard CALs for users to access fundamental email and calendar information.
    - Exchange Server Enterprise CAL for Unified Messaging, integrated archiving functionality, and information protection capabilities.
    - Exchange Server Enterprise CAL with Services with active SA includes the rights to Data Loss Prevention and Exchange Online Protection.                       	|                     #                  	|      	|

> [!IMPORTANT]  
> - *Exchange Server Enterprise CAL can be assigned only for users or devices *
> - *Choose the Server license based on the required scalability and the CALs based on the required functionality.*

> [!WARNING]  
> *Exchange Server Enterprise CAL can be added only to user / device with assigned Exchange Server Standard CALs.*

| Features                                                                                                                                     	|          Standard CAL          	|        Standard + Enterprise CAL       	|      	|
|----------------------------------------------------------------------------------------------------------------------------------------------	|:------------------------------:	|:--------------------------------------:	|:----:	|
| Email, calendar, contacts, and tasks                                                                                                         	|                ✓               	|                    s                   	|      	|
| Outlook on the web (Internet Explorer, Firefox, Chrome, Safari, and Edge support)                                                            	|                 #              	|                     #                  	|      	|
| Apps for Outlook and Outlook on the web                                                                                                      	|                 #              	|                     #                  	|      	|
| Site mailboxes2                                                                                                                              	|                 #              	|                     #                  	|      	|
| Role-based access control (RBAC) capabilities                                                                                                	|                 #              	|                     #                  	|      	|
| Journaling                                                                                                                                   	|            Per database        	|         Per user/distribution list     	|      	|
| Journal decryption                                                                                                                           	|                                	|                     #                  	|      	|
| Retention policies                                                                                                                           	|         Default and custom     	|             Default and custom         	|      	|
| In-Place Archive2                                                                                                                            	|                                	|                     #                  	|      	|
| Multi-mailbox search                                                                                                                         	|                                	|                     #                  	|      	|
| In-Place Hold2                                                                                                                               	|                                	|                     #                  	|      	|
| Information protection and control (IPC): transport protection rules,  Outlook protection rules, Information Rights Management (IRM) search  	|                                	|                     #                  	|      	|


## License Mobility
TBD

## License Suites
TBD

## Software assurance
TBD

## Licensing external users
- External users are users who are not the licensee’s or its affiliates’ employees or on-site agents or contractors.
- External users are licensed by the Exchange Server 2019 license and there are no requirements for CALs or other licenses for these users.

## Downgrading versions and editions
TBD

## Licensing virtual machines (VMs)/containers
TBD

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
