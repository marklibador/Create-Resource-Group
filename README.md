<p align="center">
  
![image](https://github.com/CarlosAlvarado0718/Virtual-Machine/assets/140138198/dc2b5537-ab14-4558-8051-beed0437806f)


  
</p>

<h1>Let's Create Resource Groups and Deploy a Virtual Machine Together!</h1>
<br />

This tutorial outlines the founding steps of using Microsoft Azure, Creating Resource Groups, Creating Virtual Machines, and using Remote Desktop Connection(RDP)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Having a Free 30 Day Scription to MicroSoft Azure


<h2>Tutorial Steps</h2>

>**Note***
>_This is a Tutorial to build both a Resources Group and a Virutal Machine to begin the tutorial on osTicket. Creating this groundwork will provide us a stable foundation to work on._

<h3>&#9312Creating a Resource Group</h3>

>**Note***
>_A resource group is a container that holds related resources for an Azure solution._

- After logging into your free scription on MicroSoft Azure, You'll see the main interface
- Type into the search bar **Resource Group**
- Click `Resource groups` underneath `Services`

  ![image](https://github.com/CarlosAlvarado0718/Virtual-Machine/assets/140138198/350467d4-21ba-40e5-a28d-7dc1ac55b67b)

- Click `Create` or `Create resource group`

  ![image](https://github.com/CarlosAlvarado0718/Virtual-Machine/assets/140138198/9f781b6a-2b12-4164-bf9a-fcaee5afc75d)

- Set `Subscription` as **Azure Subscription 1**
- Set `Resource group` as **RG-osTicket**
- Set `Region` as **(US) WEST US 3**
- Click `Review + create` once Validation is finished -> Click `Create`

 ![image](https://github.com/CarlosAlvarado0718/Virtual-Machine/assets/140138198/abc7f1ad-7067-47ad-9b5b-7e38768a7117)

- Now you have a Resource Group!

![image](https://github.com/CarlosAlvarado0718/Virtual-Machine/assets/140138198/8c327181-c4e0-48d4-a8c7-81e745ea61c5)

<h3>&#9313Creating a Virtual Machine</h3>

>**Note***
>_Virtual machines are generally used to host applications when the customer requires more control over the computing environment than what is offered by other compute resources._

- Click back to Azure's Main Interface
- Type into the search bar **Virtual Machine**
- Click `Virtual Machines` underneath `Services`

![image](https://github.com/CarlosAlvarado0718/Virtual-Machine/assets/140138198/4a2b3294-7fa4-48fa-a4aa-79f638241071)

- Click `Create`
- Click `Azure virtual machine`

  ![image](https://github.com/CarlosAlvarado0718/Virtual-Machine/assets/140138198/92a4054f-e89b-413e-8c3a-4d0321656db6)

- Set `Resource group` to **RG-osTicket**
- Set `Virtual machine name` to **vm-osticket**
- Set `Region` to **(US) WEST 3**
- Set `Image` to **Windows 10 Pro, version 22H2**

![image](https://github.com/CarlosAlvarado0718/Virtual-Machine/assets/140138198/760bf4c8-190b-4b4e-87a7-79aef87f8bd0)

- Set `Size` to **Standard_D4s_v3-4vcpus, 16 GiB memory($140.16/month)**
- Set `Username` to **labuser**
- Set `Password` to **osticketPassword1**
- Confirm eligible license with multi-tenant hosting rights.
- Click `Next` until you reach `Networking` then click `Review + create`

  ![image](https://github.com/CarlosAlvarado0718/Virtual-Machine/assets/140138198/7d38a101-effe-4a46-897e-42b0290c482c)

- Click `Create`

 ![image](https://github.com/CarlosAlvarado0718/Virtual-Machine/assets/140138198/e04d25d7-d706-486a-8e89-394748e8b150)

 <h3>&#9314 Log into the Virtual Machine</h3>

- Click on the MicroSoft Azure logo on the Top Left Corner
- Click into `vm-osticket` Virtual Machine
- Copy the `Public I.P Address`

 ![image](https://github.com/CarlosAlvarado0718/Virtual-Machine/assets/140138198/4c8ea98b-0144-44cf-88b9-1ea6475673e4)

 - Open up the start menu on your computer
 - Type in Remote Desktop Connection (RDP)
 - Paste the I.P Address
 - Click Connect

![image](https://github.com/CarlosAlvarado0718/Virtual-Machine/assets/140138198/a68dca3d-ba02-403b-a68b-e4c9c20754b6)

- Once a pop up box appears, click `more choices`
- Input log-in details from before

![image](https://github.com/CarlosAlvarado0718/Virtual-Machine/assets/140138198/8540b237-c9aa-4ea9-bdb8-b3ff34b31de2)

- Click `Yes` to bypass the prompt

![image](https://github.com/CarlosAlvarado0718/Virtual-Machine/assets/140138198/b6b0a09c-3110-4096-85f2-edbd375caec2)

<h2>Congrats! You've made your first Virtual Machine with MicroSoft Azure</h2>

![image](https://github.com/CarlosAlvarado0718/Virtual-Machine/assets/140138198/0488a5d6-3007-4e10-befe-0b402554c8b1)
