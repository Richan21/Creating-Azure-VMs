
<h1>Creating-Azure-VMs</h1>
The guide outlines setting up a Security Operations Center (SOC) and Honeynet on Azure, emphasizing effective monitoring, incident response, and honeypot deployment to bolster your organization's resilience against cyber threats <br />


## Prerequisites
1. Create an Azure Subscription to access the Azure Platform. This comes with an initial $200 credit for new accounts.

<h2>Environments and Technologies Used</h2>
(NOTE: I was able to set up the entire project on both my IPAD Pro 2020 and desktop running Windows 10)

- Microsoft Azure (Virtual Machines/Compute)

<h2>Operating Systems used</h2>

- windows 10(21h2)
- IpadOS Version 16

## Resource Group Creation
1. Sign in to the Azure Portal.
2. Navigate to “Resource groups.”
3. Click “+ Add” to create a new resource group.
4. Fill in the basics:
   - Subscription: Choose Azure subscription.
   - Resource group: Enter a unique name.
   - Region: Choose the deployment region.
5. Review and create the resource group.

![image](https://github.com/Richan21/How-to-Implement-a-SOC-in-AZURE/assets/153684298/793d928e-f636-43bc-8f46-b61191a2fe94)
![image](https://github.com/Richan21/How-to-Implement-a-SOC-in-AZURE/assets/153684298/8208fb19-952d-4345-bc71-26c79d74b0b7)
![image](https://github.com/Richan21/How-to-Implement-a-SOC-in-AZURE/assets/153684298/0fd5d018-52c9-45fa-91b1-4dd2d4c805d7)

## Virtual Machines (VM)
1. Navigate to “Virtual Machines”
2. Click “+ Add” to create a new Virtual Machines.
3. Fill in the basics:
   - Subscription: Choose Azure subscription.
   - Resource group: Create or select.
   - Virtual Machine name: Enter a unique name.
   - Region: Choose the deployment region.
4. Proceed to Create/Review.
6. Create the Virtual Machine.

![image](https://github.com/Richan21/How-to-Implement-a-SOC-in-AZURE/assets/153684298/3a2baf83-9253-4cda-810c-638bb234791c)
![image](https://github.com/Richan21/How-to-Implement-a-SOC-in-AZURE/assets/153684298/6f0ceddc-a6a9-4575-b856-4761ed5a5ea0)
![image](https://github.com/Richan21/How-to-Implement-a-SOC-in-AZURE/assets/153684298/86d47af9-28ed-4f5e-8a35-af6967915736)
![image](https://github.com/Richan21/How-to-Implement-a-SOC-in-AZURE/assets/153684298/d023c5c1-b66f-4317-ba99-851b2891776f)
![image](https://github.com/Richan21/How-to-Implement-a-SOC-in-AZURE/assets/153684298/726c6b5a-c4dc-4e49-ab78-d130428e5d8c)
