# virtual-machine
<p align="center">
<img src="https://i.imgur.com/4wqxHID.png" height="40%" width="60%" alt="Microsoft Azure Logo"/>
</p>

<h1>Microsoft Azure</h1>
This guide will demonstrate how to create a virtual machine using Azure. Microsoft Azure is a cloud platform that will let you rent space in order to store or process your own data.

Create an Azure account [here](https://azure.microsoft.com/en-us/free/) and you will receive a 30-day $200 credit.

<h2>Requirements</h2>

- Computer with Internet Connection
- Free Microsoft Azure Account (requires credit card for $200 credit)

<h2>Configuration Steps</h2>


<h3>Step 1: Create Resource Group</h3>
A Resource Group acts as a folder holding the resources you create such as Virtual Machines, Storage Accounts, and Databases

- Go to [portal.azure.com](https://www.portal.azure.com)
- Use the search bar, type "resource groups" and hit enter
- Select create resource group
- Give the resource group a name and select the region 
- Select review + create
    - In this demonstration, we will be using "RG-Lab-1" for the name and "(US) East US" for the region (recommended to keep region that was defaulted to you)

<p align="center">
<img src="https://imgur.com/IitZKlP.png" height="70%" width="70%" alt="Azure Free Account"/> <img src="https://imgur.com/t97KCtA.png" height="70%" width="70%" alt="Azure Free Services"/>
</p>

<h3>Step 2: Create Virtual Machine</h3>
     
- Go to search bar and search "virtual machine"
- Select create, then select Azure virtual machine
- You will need to select the resource group, the region, and create a name for the virtual machine
    - For the example we will name the virtual machine virtualmachine
    - Use same resource group and region as step 2/3

<h3>Step 3: Create Virtual Machine</h3>

* You will then need to select image and size
    - For image we will use Windows 10 Pro
    - For size, select see all sizes and select Standard D2as_v4
* You will then need to make a username and password
    - For username, we will use labuser
    - Create your own password
* Click the box under licensing and finally click Review + Create

<h3>Step 4: Create Virtual Machine</h3>

- First you will need to find the Public IP address of your virtual machine
   - Select the virtual machhine we created in step and the IP address will be on the right hand side 
   - Copy the IP address

<p align="center">
<img src="https://imgur.com/OnwCcc6.png" height="70%" width="70%" alt="Azure Free Account"/> <img src="https://i.imgur.com/PCJ3QAr.png" height="70%" width="70%" alt="Azure Free Services"/>
</p>
 

<p align="center">
<img src="https://i.imgur.com/p9UJXND.png" height="70%" width="70%" alt="Azure Free Account"/> <img src="https://i.imgur.com/GHBDae0.png" height="70%" width="70%" alt="Azure Free Services"/>
</p>
 
<p align="center">
<img src="https://i.imgur.com/T4Oc2RX.png" height="80%" width="80%" alt="Azure Free Account"/>

* Mac Users 
   - Download Microsoft Remote Desktop
   - Open application and click add PC
   - Paste IP address and select Add
   - Double click on the virtual machine and enter username and password from step 4
   - Select continue
   
* Windows Users
     - Open and use Remote Desktop
     - Paste IP Address and select Connect
     - Enter username and password from step 4
     - Select OK
  
     
     
 <p align="center">
<img src="https://i.imgur.com/14pPOdv.png" height="70%" width="70%" alt="Azure Free Account"/> <img src="https://i.imgur.com/Og3LKyd.png" height="70%" width="70%" alt="Azure Free Services"/>
</p>


🎉Congratulations! You have created your first virtual machine within Azure!🎉

<p align="center">
<img src="https://i.imgur.com/rEBpL8Y.png" height="80%" width="80%" alt="Azure Free Account"/>

<h3>Tip</h3>

-  If you want to save your free $200 credits, make sure you delete ALL resource groups after finishing!    
  
