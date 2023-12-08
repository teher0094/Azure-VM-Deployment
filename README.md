# Azure-VM-Deployment
Setting up Virtual Machines in Microsoft Azure

## Overview
This guide provides step-by-step instructions on how to deploy Virtual Machines (VMs) in Microsoft Azure. It is intended for beginners and aims to simplify the process of VM creation and setup in the Azure cloud environment.

## Prerequisites
- Active Azure account
- Basic knowledge of cloud computing concepts

## Step-by-Step Deployment

### Step 1: Create a Resource Group
- After logging into your Azure account, search for **Resource Group** using Azure's search bar.
- This will bring you to a page which will allow you to create a Resource Group.
- Resource Groups will allow you to manage a variety of Azure services within a single container.
- Select the **+ Create** or **Create Resource Group**.
- Within the creation page, create a name and choose a region for your resource group.
  
![image](https://github.com/teher0094/Azure-VM-Deployment/assets/153027290/6b56e8dc-80b5-45e9-85dc-451d016e31af)

- Note that depending on the region you choose, certain Azure services may not be available. I find that regions in the US will have the most available resources.
- Next, you can add tags to the resource then select **Review + Create** and **Create** to create the Resource Group.


### Step 2: Create a New Virtual Machine and Configuration
- Now that there is a Resource Group to contain the services, use the Azure search bar to search "Virtual Machines".
- Note: There will be a variety of VM options but let's pick the one called "Virutal Machine" to keep it simple.
- Click **+Create** and it'll take you to a configuration page. 
  
![image](https://github.com/teher0094/Azure-VM-Deployment/assets/153027290/53df64ba-7c1a-41f2-b6cc-ca3870d3cc9e)

![image](https://github.com/teher0094/Azure-VM-Deployment/assets/153027290/29b89e5d-e7fa-4e13-a0fe-ad54ab3da150)

- Note: For simplicity, we'll be keeping most of the configuration options at 'default', so options that are not mentioned should be left unchanged.
- Select your desired **Subscription** and **Resource Group**.
- Name your virtual machine and choose it's region.
- Note: You can experiment with different types of OS by looking through the options of VM images available. The different VM sizes will affect how capable your VM will be but the more powerful the VM, the more costly it will be to manage.
- For this project, choose the "Windows 10 Pro version 22H2-64x Gen2" for the image.
- The size can be "Standard_E2s_v3 - 2 vcpus, 16 GiB memory". 

### Step 3: Set Up Authentication
- Enter required credentials based on the authentication method.
  
  ![image](https://github.com/teher0094/Azure-VM-Deployment/assets/153027290/87bc676c-2b81-414a-abc5-d72027678b5e)

- Because we've chosen Windows 10, we'll have to create an Admin account, which will be needed to login into the VM.
- Create a username and password.
- For Licensing, make sure to check the box.

  ![image](https://github.com/teher0094/Azure-VM-Deployment/assets/153027290/d7c2ffc9-9025-4c77-99c6-555c4fb04d63)


### Step 5: Review and Create
- Review your configurations.
- Click **Create** to deploy the VM.

## Post-Deployment Configuration
- Once the VM is deployed, you can connect to it via SSH or RDP.
- Customize the VM based on your project requirements.

## Useful Tips
- Monitor your VM's performance and cost in the **Azure Dashboard**.
- Regularly update and patch your VM for security.

## Conclusion
Deploying VMs in Azure can significantly enhance your IT infrastructure. With this guide, you can start exploring the vast possibilities in cloud computing.

---

Feel free to add or modify sections based on the specifics of your project or to include any additional insights you gained during your VM deployment experience.
