# Microsoft Skype for Bussiness

## Editions
- Skype for Business (single edition)

## Versions
- Skype for Businesses 2016
- Skype for Businesses 2019
- Skype for Business LTSC 2021
- Skype for Business for Microsoft 365

## Requirements
- Microsoft Windows Server
  - Skype for Businesses Server solution has an infrastructure requirement for Windows Server.
  - Users therefore need to be covered with the relevant licenses for this product.
- Microsoft SQL Server
  - Skype for Businesses Server solution has an infrastructure requirement for Microsoft SQL Server.
  - Users must be licensed in the underlying infrastructure with the relevant licenses.

## License Model
#### **Server License + CAL**
> Purchase a Server license for each server, and then purchase Client Access Licenses (CALs) for either users or devices.
- **Server License**
  - Skype for Business Server License
- **Client Acess License (CAL)**
  - Skype for Business Standard CAL - User / Device CAL 
  - Skype for Business Enterprise CAL - User / Device CAL (Conference)
  - Skype for Business Plus CAL - User / Device CAL (Enterprise Voice + Telefony)

> [!NOTE]
> - *Skype for Business has only single type of server license.*
> - *Everyone acessing Skype For Bussiness Server need to have a Standard CAL assigned.*

![image](https://github.com/JiriSlof/KnowledgeBase/assets/168433423/03768e17-3170-47f3-bbf1-5e80045dec4b)


## License Rules
### **Server License**
- **Skype for Business Server License**
  - A single server license must be assigned to the physical server.
    
### **Client Acess License (CAL)**
A Client Access Licenses (CALs) must be purchased for either users or devices.
- **Skype for Business Standard CAL**
  - The instant messaging and presence integration functionality.
  - This CAL must be assigned for either users or devices acessing Skype for Business server.
- **Skype for Business Enterprise CAL**
  - For audio, video and web conferencing in addition to the Standard CAL.
- **Skype for Business Plus CAL**
  - For enterprise voice and telephony in addition to the Standard CAL.

> [!NOTE]  
> - *Choose additional CALs based on user / device required functionality.*
> - *Skype for Business Enterprise CAL and Business Plus CAL are only the additive CALs.*
> - *Both Enterprise CAL and Business Plus CAL can added only in addition to the Standard CAL.*

## License Mobility
- License Mobility is not available for Exchange Server.
- Licenses can be reassigned to servers no more frequently than once every 90 days.

## Software Assurance
- Skype for Business Server licenses purchased with Software Assurance have License Mobility across Server Farms rights which allows the reassignment of Server licenses to other physical servers in a server farm as often as required.
- Software Assurence provides rights for Server Disaster Recovery (“Permitted Use of Backup Instances”).

## Licensing External Users
- Licensed with Server.
- External users who attend a Skype for Business Meeting, for example, are licensed by the Skype for Business Server license and there are no requirements for CALs, or other licenses, for these users.
- External users are users who are not the licensee’s or its affiliates’ employees or on-site agents or contractors.

## Downgrade Rights
None.

## Licensing Virtual Machines (VMs) / Containers
A Server license must be assigned to a single physical server which licenses Skype for Business Server to be run in either the physical operating system environment or a single virtual machine on that server.

## Skype for Business Clients
Users have a choice of clients to access their Skype for Business Server service:
- Microsoft Skype for Business
    > The complete Skype for Business client, which is typically installed with Microsoft 365.
- Microsoft Skype for Business Basic
    >  A free of charge, less feature-rich Skype for Business client.
- Microsoft Skype for Business on Mac
    > The Skype for Business client for Mac OS X desktop and laptop computers.
- Microsoft Skype for Business for mobile devices
    > Available for Android and iOS devices from the relevant stores.
- Microsoft Skype for Business Web App
    > Available for individuals invited to Skype for Business Meetings who do not have a Skype for Business client installed. It enables a rich meeting experience via the browser.


> [!IMPORTANT]  
> *Note that internal users using any of these clients must be licensed with the relevant CALs.*

## External Links
- Overview - [Link](https://getlicensingready.com/HandoutStore/Skype%20for%20Business%20Server%202019%20v22.40.pdf)
- Video EDU - [Link](https://youtu.be/z9oeP8VHap4?si=x8LdhZZSD_OqXwKQ)
