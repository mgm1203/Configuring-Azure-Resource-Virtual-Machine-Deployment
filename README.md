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
7. Deploy a Virtual Network within the Resource Group.
8. Connect to the Virtual Machine using Remote Desktop Protocol (RDP).
9. Verify that the deployed resources are working correctly.
10. Manage, stop, or delete resources when they are no longer needed.

## Deployment and Configuration Steps
<p align="center">
<img width="1800" height="1100" alt="image" src="https://github.com/user-attachments/assets/d1bd6d7b-d63e-4d3f-bec7-88b2c21be475" />
  <p align="center">
  <img width="1800" height="1100" alt="image" src="https://github.com/user-attachments/assets/c655b93d-4b73-46f1-a844-efc8125764b4" />
  
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

<p align="center">
<img width="1920" height="1008" alt="image" src="https://github.com/user-attachments/assets/8deb9d9d-0a9f-4b2a-966b-8776f342371a" />
</p>

<p align="center">
<img width="1920" height="1008" alt="image" src="https://github.com/user-attachments/assets/7f7c58d2-136d-4bc6-81a2-b10c0dcf3e08" />
</p>

Next, after you confirm licensing, you will click "Networking," this is where we will create our Virtual Network. After clicking this subsection, you will notice "Edit Virtual Network," this enables you to change the name of the new Virtual Network which will be created within our Resource Group.

<p align="center"> 
<img width="1920" height="1008" alt="image" src="https://github.com/user-attachments/assets/d12f9e95-b5e7-4faa-829a-b1d76aa772c3" />
</p>

<p align="center"> 
<img width="1920" height="1008" alt="image" src="https://github.com/user-attachments/assets/802ab1f8-b9ea-4bbb-bfa9-a1b9e31fa05c" />
</p>

Finally, after renaming our new Virtual Network, after clicking "Review and Create," we can now view both the Virtual Machine and Virtual Network under either section or we can view them both within our Resource Group.

<p align="center">
<img width="608" height="325" alt="image" src="https://github.com/user-attachments/assets/3f058f44-523d-449c-b697-c5352746e545" />
</p>

The next and final resource we will be using involves the implementation of the Virtual Machine we created in order to connect virtually to a Remote Desktop. This specific image refers to Remote Desktop Protocol (RDP) using Windows. 

<p align="center">
<img width="1920" height="1008" alt="image" src="https://github.com/user-attachments/assets/8600db39-af28-4b7f-afe5-21a1006e7cfd" />
</p>

After deployment, obtain and copy the Virtual Machine's Public IP Address. This is found by searching either your Resource Group or Virtual Machine you created and clicking on it's name. Under Networking, you will see a visible Public IP Address. 

<p align="center">
<img width="826" height="520" alt="image" src="https://github.com/user-attachments/assets/01fc32c3-8788-495e-816f-10962c8311bc" />
</p>

Next, on the Windows search bar, you will search for "Remote Desktop Connection," prompting the needed resource to open.

<p align="center">
<img width="608" height="325" alt="image" src="https://github.com/user-attachments/assets/9f61c8d1-536e-4910-872c-5c88ae511e52" />
</p>

Finally, you will enter the copied Public IP Address of the Virtual Machine and administrator credentials created during the Virtual Machine deployment to establish the remote connection.

<p align="center">
<img width="1920" height="1008" alt="Compute infrastructure - Microsoft Azure - Google Chrome 8_12_2026 5_11_06 AM" src="https://github.com/user-attachments/assets/4bf0aea4-6e52-49d0-ac12-cc9daa25becd" />
</p>

The final steps include verifying that all Azure Resources are successfully created and are functioning correctly. Individually searching for each created resource works and when specifically searching for your Virtual Machine, it visibly shows you whether a program is running or stopped.

<p align="center">
<img width="1920" height="1008" alt="Compute infrastructure - Microsoft Azure - Google Chrome 8_12_2026 5_18_52 AM" src="https://github.com/user-attachments/assets/0cd22876-ca52-4749-a6a8-bcd859fa104e" />
</p>

<p align="center">
<img width="1920" height="1008" alt="Compute infrastructure - Microsoft Azure - Google Chrome 8_12_2026 5_19_23 AM" src="https://github.com/user-attachments/assets/a5e5f0ed-016e-4806-b97f-8e67b3a0ebd0" />
</p>

Lastly, the final step in this project of configuring resources is managing them. If you no longer need any of the resources you created, you can simply delete "Resource Group," because we created all of our resources within our Resource Group, they will all delete at once. However, if you simply want to stop, restart, or delete individual resources, you will click the drop down dots as shown and click the appropriate status.

# Overall Learning Outcome
This project provided practical experience with deploying and managing cloud resources in Microsoft Azure. It helped develop an understanding of how cloud computing, virtualization, networking, storage, and remote administration work together in a real-world Azure environment.

