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
2️⃣ Sign in with your Microsoft account.  
3️⃣ Provide the necessary details, including your payment method and contact information.  
4️⃣ Complete the setup to activate your subscription.

   ![Step 1 Image](images/step1_subscription.png)

---

### ② Log in to Azure Portal
1️⃣ Navigate to the [Azure Portal](https://portal.azure.com).  
2️⃣ Log in using your Microsoft account credentials.

   ![Step 2 Image](images/step2_portal.png)

---

### ③ Navigate to Virtual Machines
1️⃣ In the Azure portal, search for **Virtual Machines** in the top search bar.  
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
