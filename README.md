<p align="center">

![image](https://github.com/user-attachments/assets/81966049-c461-4d97-9f96-eee9e507fd96)


</p>

<h1> Creating A Virtual Machine (Azure)</h1>
This tutorial provides a comprehensive, step-by-step guide to creating a Virtual Machine (VM) in Microsoft Azure and accessing it for use.<br />





<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Resource Groups
- RDP (Remote Desk Protocol)
- SSH (Secure Shell)


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

### ②  Navigate to Virtual Machines
1️⃣ In the Azure portal, search for **Virtual Machines** .  
![Screenshot 2024-11-17 095949](https://github.com/user-attachments/assets/3c8511b1-4d33-4b92-9dd8-de75762f5158)

2️⃣ Click on **Virtual Machines** from the results.

   ![Step 3 Image](images/step3_vm_page.png)

---

### ④ Create a New Virtual Machine
1️⃣ Click the **+ Create** button.  
2️⃣ Select **Azure Virtual Machine**.

   ![Step 4 Image](images/step4_create_vm.png)

---

### ⑤ Configure Basic Settings
1️⃣ Fill in the following details:  
   - **Subscription**: Choose your Azure subscription.  
   - **Resource Group**: Select an existing group or create a new one.  
   - **Virtual Machine Name**: Enter a name for your VM (e.g., `MyAzureVM`).  
   - **Region**: Select the region closest to you.  
2️⃣ Click **Next** to proceed.

   ![Step 5 Image](images/step5_basic_settings.png)

---

### ⑥ Choose an Image and Size
1️⃣ Under the **Image** section, select the operating system (e.g., Windows Server or Ubuntu).  
2️⃣ Select the VM size based on your needs (e.g., Standard B1s for small workloads).

   ![Step 6 Image](images/step6_image_size.png)

---

### ⑦ Configure Administrative Account
1️⃣ Provide a username and password for accessing the VM.  
2️⃣ Ensure the inbound port rules allow **RDP (for Windows)** or **SSH (for Linux)**.

   ![Step 7 Image](images/step7_admin_account.png)

---

### ⑧ Review and Create
1️⃣ Click on the **Review + Create** button.  
2️⃣ Review your configuration details.  
3️⃣ Click **Create** to deploy the virtual machine.

   ![Step 8 Image](images/step8_review_create.png)
