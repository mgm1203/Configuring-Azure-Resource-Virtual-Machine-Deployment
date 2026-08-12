<h1 align="center">
  <img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/0188b8bf-9d10-4234-9fc5-739606a86f3c" />

# Creating-Azure-Account-Configuring-Resources
Hands-on Microsoft Azure project demonstrating the process of creating a Microsoft Azure account and deploying and configuring several Azure cloud resources. The project covers Azure Resource Groups, Azure Storage, Virtual Machines, Azure Virtual Networks and Remote Desktop Protocol (RDP).

# Goal: 
*  The goal of this project is to gain hands-on experience with Microsoft's Azure cloud platform and understand how different cloud resources work together within an Azure environment.

## Environments and Technologies Used
* Microsoft Azure
* Azure Portal
* Azure Resource Groups
* Azure Storage
* Azure Virtual Machines
* Azure Virtual Network
* Remote Desktop Protocol (RDP)

## Operating Systems Used
* Windows 11-Local computer used to access Azure resources
* Windows Server- Operating system used for the Azure Virtual Machine

 ## High-Level Deployment and Configuration Steps
1. Create a Microsoft Azure account.
2. Sign into the Azure Portal.
3. Create a Resource Group to organize Azure resources.
5. Create a Storage Account within the Resource Group.
6. Deploy a Virtual Machine within the Resource Group.
7. Deploy a Virtual Network. 
8. Connect to the Virtual Machine using Remote Desktop Protocol (RDP).
9. Verify that the deployed resources are working correctly.
10. Manage, stop, or delete resources when they are no longer needed.

## Deployment and Configuration Steps
<p align="center">
<img width="1800" height="1008" alt="image" src="https://github.com/user-attachments/assets/d1bd6d7b-d63e-4d3f-bec7-88b2c21be475" />
  <p align="center">
  <img width="1800" height="1008" alt="image" src="https://github.com/user-attachments/assets/c655b93d-4b73-46f1-a844-efc8125764b4" />
  
The first step is to visit https://azure.microsoft.com/en-us/free/, you will click "Try Azure for free." Following this step you will then continue to sign in to an already existing account and or create a new one providing access to Microsoft's cloud computing platform. 

<h1 align="center">
  <img width="1920" height="1008" alt="image" src="https://github.com/user-attachments/assets/53ed4c59-fea8-49b1-b62b-e7cb8a42bc46" />
</h1>

Next, you will go to [https://portal.azure.com](https://portal.azure.com), which is known as the Azure Portal. The Azure Portal provides a graphical interface for creating, configuring, and managing Azure resources.

<p align="center">
  <img width="1920" height="1008" alt="image" src="https://github.com/user-attachments/assets/cb76e751-f1ce-4eb7-95a1-f5996b318e24" />
</p>

<p align="center">
<img width="1920" height="1008" alt="image" src="https://github.com/user-attachments/assets/184afc72-2f3d-4495-a082-8d19007edca0" />
</p>

Next, you will type, "Resource Group," in the text box and click on the service. This brings to to the service where u can then create a new resource group. (Yours will be empty, i already have some created on screen.) The Resource Group acts as a container for related Azure resources, such as Virtual Machines, Storage Accounts, and Virtual Networks.

<p align="center">
<img width="1920" height="1008" alt="image" src="https://github.com/user-attachments/assets/df28b862-150c-4354-8ba1-94d54a003fa7" />
</p>

<p align="center">
<img width="1920" height="1008" alt="image" src="https://github.com/user-attachments/assets/a9d236b8-7c7b-45e0-8d73-29c4ea6ee30b" />
</p>

Furthermore, to use the service and create a resource group, you will click "Create," and name the group anything you want. Once created, you will now see your new resource group populate.

<p align="center">
<img width="1920" height="1008" alt="image" src="https://github.com/user-attachments/assets/cc03c220-31c9-496e-bd2c-ff4d15fdfa32" />
</p>

Next, like the Resource Group, you will type in the search bar "Storage Account," and click "Create." An Azure Storage Account provides cloud storage for different types of data. In this project, we will create the Storage account within the Resource Group which demonstrates cloud storage ability.

<p align="center">
<img width="1920" height="1008" alt="image" src="https://github.com/user-attachments/assets/ae91b6e1-5d88-4555-be29-041c59c1719e" />
</p>

<p align="center">
<img width="1920" height="1008" alt="image" src="https://github.com/user-attachments/assets/69e3da23-465b-4b9a-9f46-4f94f13a366f" />
</p>

Furthermore, after clicking "Create," you will now fill in the project details for any reason you have created the Storage Account. To create the Storage Account within the Resource Group, be sure to click on down arrow shown next to "Resource Group," and choose accordingly. You can then choose a Unique name for the account, followed by the region and performance/redundancy which provide different options and explanations for whichever you prefer. Finally, you can click review and create, you will now see your new Storage Account in your Storage Center or inside of the Resource Group you created earlier.

<p align="center">
<img width="1920" height="1008" alt="image" src="https://github.com/user-attachments/assets/4ad3027e-25ac-46c1-ad02-9c415a29f88e" />
</p>

Next, applying your knowledge in previous segments, you will search and click on "Virtual Machine," and create a new machine within the Resource Group. An Azure Virtual Machine provides a virtualized computer running in Microsoft's cloud. An Azure Virtual Network (VNet) provides a private networking environment for Azure resources.

##### Note: When creating the new Virtual Machine, it will give us the option to also continue the following step of creating a Virtual Network. This will allow us to then deploy them both under the same Resource Group for organization efforts. The Virtual Network allows resources such as Virtual Machines to communicate with each other and provides control over IP addressing and network connectivity.

<p align="center">
<img width="1920" height="1008" alt="image" src="https://github.com/user-attachments/assets/0a4c4deb-a061-4c2d-8c04-17120b805578" />
</p>

Here you will select the appropriate Resource Group which allows us to create the new Virtual Machine within the Resource Group. Followed by this, put the name and region of your Virtual Machine. 

<p align="center">
<img width="1920" height="1008" alt="image" src="https://github.com/user-attachments/assets/93e1a846-6950-4896-81c8-b859c55d4201" />
</p>

Selecting the appropriate image when creating an Azure Virtual Machine is important because the image determines what operating system and preconfigured software your VM starts with. The size determines the virtual hardware allocated to your VM. You want enough resources to run what you're planning to do without paying for resources you don't need.

#### Note: Windows Server 2022: Gives you a VM running Windows Server 2022, Windows 11: Gives you a Windows 11 environment, Ubuntu: Gives you a Linux based VM.

<p align="center">
<img width="1920" height="1008" alt="image" src="https://github.com/user-attachments/assets/68628202-f932-47f6-a68e-0ccb9364bdc9" />
</p>

Properly saving your Username and Passwords to almost any account is vital for organization and safety.  

<p align="center">
<img width="1920" height="1008" alt="image" src="https://github.com/user-attachments/assets/63dad204-81a2-4fe0-a2d1-0918f26770f3" />
</p>

Finally, you will confirm the licensing, without confirming you can not create your Virtual Machine.

