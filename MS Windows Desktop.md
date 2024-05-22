# Microsoft Windows Desktop
Microsoft Windows is a product line of proprietary graphical operating systems developed and marketed by Microsoft.

## Editions
- Windows Home
- Windows Pro
- Windows Pro for Workstations
- Windows Pro Education
- Windows Education
- Windows Enterprise
- Windows SE

## Versions
- Windows 7 *(obsolete)*
- Windows 8 *(obsolete)*
- Windows 8.1 *(obsolete)*
- Windows 10
- Windows 11

## License Model
Device and User licenses are available for Windows Desktop.
- Licese by Device
  > Device licenses are assigned to an individual device and any user may use Windows on that device.
- Licese by User
  > User licenses are assigned to a user who may then use Windows on up to 5 devices.
  - Windows VDA per User
  - Windows Enterprise per User
  - Windows Enterprise per User Add-on

![obrazek](https://github.com/JiriSlof/KnowledgeBase/assets/168433423/04260281-2d00-4aca-b6b0-ec23e6d9d84e)

## License Types
Microsoft offers various licensing types to accommodate the diverse needs of users and organizations.

### Retail Licenses
A full Packaged Product (FPP) is the retail version of a Microsoft licensed product.
Ideal for small businesses or individual users requiring a one-time purchase of Microsoft Office products.
A "Retail" license refers to the one you acquire when purchasing a copy of Windows from your local store or an online retailer. The Windows Retail license and product key can be transfered to another computer as long as you deactivate the old device.

![obrazek](https://github.com/JiriSlof/KnowledgeBase/assets/168433423/2eaad441-916b-4983-96a7-bcad5b93a216)

#### Retail License Availability
- Windows 11 Home / Pro
- Windows 10 Home / Pro

### OEM Licenses
Come pre-installed on new hardware, offering a cost-effective solution for those purchasing new devices.

![obrazek](https://github.com/JiriSlof/KnowledgeBase/assets/168433423/cc56b16f-1510-4d8b-aec3-0814f36bd233)

#### OEM License Availability
- Windows 11 Home / Pro
- Windows 10 Home / Pro


### Volume Licenses
Tailored for organizations that need to purchase licenses in bulk, providing flexibility and potential cost savings.

A "Volume" license is designed for large businesses, education, and government entities. Usually, a volume license allows organizations to use one master product key to activate any installation of Windows. 

![MS_Volume](https://github.com/JiriSlof/KnowledgeBase/assets/168433423/e588db81-8ec7-4b4e-b1e7-085feaff8eea)


> [!IMPORTANT]  
> - *Licenses that are purchased through the volume licensing agreements are upgrade licenses only.*
> - *There needs to be a quialifying operating system already on device, before volume license can be assigned to it.*
> - *The only exception is that customers can acquire the Windows VDA license to remotely access Windows 11 running in a virtual environment regardless of whether the user’s device has a Qualifying Operating System or not.*

#### Windows 11 availability in Volume Licensing
| _Windows 11 Offering_        	| CSP 	| Open Value and <br>Subscription 	| Select Plus and <br>MPSA 	| Enterprise Agreement <br>and Subscription 	|
|------------------------------	|:---:	|:-------------------------------:	|:------------------------:	|:-----------------------------------------:	|
| Windows 11 Pro               	|  ✓  	|                                 	|             ✓            	|                                           	|
| Windows Enterprise LTSC 2021 	|  ✓  	|                                 	|             ✓            	|                                           	|
| Windows 11 Enterprise        	|     	|                ✓                	|             ✓            	|                     ✓                     	|
| Windows VDA                  	|     	|                ✓                	|             ✓            	|                     ✓                     	|

#### Qualifying OS
- Winddows 11 Enterprise / Pro
- Winddows 10 Enterprise / Pro
- Winddows 8/8.1 Enterprise / Pro
- Winddows 7 Enterprise / Proffesional / Ultimate

### Subscription Licenses
Such as Microsoft 365, offer ongoing access to Microsoft products, ensuring users always have the latest versions.

### Educational, Non-Profit, and Government Licenses

## License Mobility
TBD

## License Suites
TBD

## Software Assurance
Windows 11 Enterprise includes Software Assurance which gives the following rights:
- Virtual Desktop Access
  > Rights to access virtual machines hosted in a Virtual Desktop Infrastructure.
- Local virtualization
  > Rights to access up to four virtual OSEs on a licensed device.
- MDOP
  > Microsoft Desktop Optimization Pack tools.
- Flexible Virtualization Benefit
  > Rights to install software on Authorized Outsourcers’ servers.
- Ongoing access to new Long-Term Servicing Channel builds.

> [!NOTE]  
> *Windows 11 Pro and Windows Enterprise LTSC 2021 licenses do not include Software Assurance.*

## Downgrade Rights

| Can be donwgraded to:     	| OEM<br>Pro 	| Volume<br>Pro 	| Volume<br>Enterprise 	|
|---------------------------	|:----------:	|:-------------:	|:--------------------:	|
| Windows 10 Enterprise     	|            	|               	|           ✓          	|
| Windows 10 Pro            	|      ✓     	|       ✓       	|           ✓          	|
| Windows 8/8.1 Enterprise  	|            	|               	|           ✓          	|
| Windows 8/8.1 Pro         	|            	|       ✓       	|           ✓          	|
| Windows 7 Enterprise      	|            	|               	|           ✓          	|
| Window 7 Professional     	|            	|       ✓       	|           ✓          	|
| Windows Vista Enterprise  	|            	|               	|           ✓          	|
| Windows Vista Business    	|            	|       ✓       	|           ✓          	|
| Windows XP Professional   	|            	|       ✓       	|           ✓          	|
| Windows 2000 Professional 	|            	|       ✓       	|           ✓          	|
| Windows 95 / 98 / NT      	|            	|       ✓       	|           ✓          	|

## Licensing Virtual Machines (VMs) / Containers
TBD


## Windows Activation
Every copy of Windows 11 must be activated with a valid product key.

### OEM  / Retail Activation
-  Via the Internet
-  Via the Telephone

### Volume Activation
- Key Management Services (KMS)
  > Activation is done against a service hosted within an organization, enabling organizations to activate systems within their network, eliminating the need for individual computers to connect to Microsoft.
- Multiple Activation Key (MAK)
  > Volume license key that is used for one-time activation with activation services that are hosted by Microsoft. This method is useful for smaller organizations, and for computers which are infrequently connected to the organization’s network.
- Active Directory-based activation
  > Is a role service that allows organizations to use Active Directory Domain Services (ADDS) to simplify the task of maintaining volume activation services for a network.


## Servicing Channels
Servicing Channels allow customers to designate how frequently their individual devices are updated for new features.

- General Availability Channel
  - New functionality is provided with annual feature update releases.
  - As long as a device isn't set to defer feature updates, any device in this channel will install a feature update as soon as it's released.
  - Applies to both Windows Pro and Enterprise editions.
- Long-Therm Servicing Channel (LTSC)
	- Feature updates every 2-3 years.
	- Regular cadense for security and quality fixes to stay up to date.
	- Each LTS has 5years mainstream + 5years extended support.
  - A Windows Enterprise LTSC edition is available through some Volume Licensing agreements and CSP.
  - Used for specialized systems—such as PCs that control medical equipment, point-of-sale systems, and ATMs—often.
  - Windows Enterprise customers may choose to deploy this edition.



## External Links

Windows 10 Qualifying OS Requirements - [Link](https://download.microsoft.com/download/3/D/4/3D42BDC2-6725-4B29-B75A-A5B04179958B/Licensing_brief_PLT_Windows_10_qualifying_operating_%20system_requirements.pdf)

Windows 11 Qualifying OS Requirements - [Link](https://download.microsoft.com/download/3/D/4/3D42BDC2-6725-4B29-B75A-A5B04179958B/Licensing_brief_PLT_Windows_qualifying_operating_%20system_requirements.pdf)

Commercial Licensing Guide - [Link](https://wwlpdocumentsearch.blob.core.windows.net/prodv2/Windows_11_Commercial_Licensing_Guide.pdf) 
