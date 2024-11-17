<p align="center">

![image](https://github.com/user-attachments/assets/81966049-c461-4d97-9f96-eee9e507fd96)


</p>

<h1> Creating A Virtual Machine (Azure)</h1>
This tutorial provides a comprehensive, step-by-step guide to creating a Virtual Machine (VM) in Microsoft Azure and accessing it for use.<br />





<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Resource Groups
- RDP (3389)


<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)



<h2>Installation Steps</h2>

 ① Create a Microsoft Azure Subscription


1️⃣ Go to the [Azure Free Trial](https://azure.microsoft.com/en-us/free/) or [Azure Pricing](https://azure.microsoft.com/en-us/pricing/) page.  
![Screenshot 2024-11-17 091248](https://github.com/user-attachments/assets/9cce42a5-dd75-405f-b3af-6c8a68093f72)
-Azure is a paid subscription but you can use the free trial in order to gain experience with using thier system

-They also have a pay as you go subscription which allows you to use thier resources whithout any long term contracts

2️⃣ Sign in with your Microsoft account.  
![Screenshot 2024-11-17 095105](https://github.com/user-attachments/assets/ae57230b-c090-4223-8849-2da128823e84)

-Once you have created your account Sighn into Azure with your new credentials

---

### ③ Create a Resource Group
A **resource group** is a logical container for your Azure resources. To create one:  
1️⃣ In the Azure Portal, search for **Resource Groups** in the top search bar.  
![Screenshot 2024-11-17 101339](https://github.com/user-attachments/assets/0e0da973-765a-478b-baf5-80f265d43ee2)

2️⃣ Click **+ Create** to create a new resource group.  
![Screenshot 2024-11-17 101439](https://github.com/user-attachments/assets/db8ffbaf-9af5-451c-b266-61875a047084)

3️⃣ Fill in the following details:
   - **Subscription**: Select your Azure subscription.
   - **Resource Group Name**: Enter a unique name for your resource group (e.g., `MyResourceGroup`).
   - **Region**: Choose a region where you want the resources to be located.
     ![Screenshot 2024-11-17 101916](https://github.com/user-attachments/assets/0629b9bd-3e5f-40dc-acd5-9dd471ba258e)

4️⃣ Click **Review + Create** and then **Create**.
![Screenshot 2024-11-17 102019](https://github.com/user-attachments/assets/6375c47f-d72d-4fd9-a86e-bae21271e13b)


---

### ②  Navigate to Virtual Machines
1️⃣ In the Azure portal, search for **Virtual Machines** .  
![Screenshot 2024-11-17 102535](https://github.com/user-attachments/assets/bfa52cda-b1bb-4a7e-b707-5eb945d86ec8)



---

### ④ Create a New Virtual Machine
1️⃣ Click the **+ Create** button.  
![Screenshot 2024-11-17 103013](https://github.com/user-attachments/assets/223ba81e-2aaf-47e0-a185-df8967b6edc9)

2️⃣ Select **Azure Virtual Machine**.

 ![Screenshot 2024-11-17 103123](https://github.com/user-attachments/assets/093433a5-5138-469f-af37-c6aef0c389a3)


---

### ⑤ Configure Basic Settings
1️⃣ Fill in the following details:  
   - **Subscription**: Choose your Azure subscription.  
   - **Resource Group**: Select an existing group or create a new one.
     
     ![Screenshot 2024-11-17 103909](https://github.com/user-attachments/assets/f1574ff2-b475-461c-b1fa-87959405e584)

   - **Virtual Machine Name**: Enter a name for your VM (e.g., `MyAzureVM`).  
   - **Region**: Select the region closest to you.  
2️⃣ Click **Next** to proceed.

  ![Screenshot 2024-11-17 104444](https://github.com/user-attachments/assets/1d739a9c-854a-4fd7-aaf8-5c6a576b1971)


---

### ⑥ Choose an Image and Size
1️⃣ Under the **Image** section, select the operating system (e.g., Windows Server or Ubuntu).  
![Screenshot 2024-11-17 104734](https://github.com/user-attachments/assets/0d142ad5-8e37-4403-ba05-a419cc1e9c0f)

-For this example we are going to be using Windows 10 Pro


2️⃣ Select the VM size based on your needs (e.g., Standard B1s for small workloads).
![Screenshot 2024-11-17 104844](https://github.com/user-attachments/assets/12cf94ea-5d21-44c9-85c3-0ecdf6ba610a)

-If you recieve the error message (This size is currently unavailable in eastus for this subscription: NotAvailableForSubscription) you may need to switch your region in order for the Size to be emplamented correctly.

  ![Screenshot 2024-11-17 105822](https://github.com/user-attachments/assets/9bbd547c-f5b7-46df-b908-106dc8ca3059)
![Screenshot 2024-11-17 105906](https://github.com/user-attachments/assets/26972379-4a3c-4c03-b846-d5a38611f534)

-In this example I swithced my my region to (Central US) and as you can see the error message went away


---

### ⑦ Configure Administrative Account
1️⃣ Provide a username and password for accessing the VM.  
![Screenshot 2024-11-17 110535](https://github.com/user-attachments/assets/6f837432-6201-4374-840a-82c73a927a16)

-The Administrator Account credentials are what youre gonna use to log into the (VM) using Remote Desktop

2️⃣ Ensure the inbound port rules allow **RDP (for Windows)** or **SSH (for Linux)**.

   ![Screenshot 2024-11-17 111030](https://github.com/user-attachments/assets/67663114-3db7-487b-be22-c34b646e5185)

  -The Virtual Machine we will be accessing is configured with Windows 10 Pro and utilizes Remote Desktop Protocol (RDP) on port 3389 for remote connectivity.


---

### ⑧ Review and Create
1️⃣ Click on the **Review + Create** button. 

![Screenshot 2024-11-17 111739](https://github.com/user-attachments/assets/6ae847b7-e919-4461-a3ee-f2f57a352069)

-Dont forget to check the licensing agreenment 

 
3️⃣ Click **Create** to deploy the virtual machine.

![Screenshot 2024-11-17 112236](https://github.com/user-attachments/assets/3b35de31-300c-4442-9a0b-9aec9994c05a)


   # Project Completed! 🎉

We've successfully created and deployed the virtual machine. Great job!
