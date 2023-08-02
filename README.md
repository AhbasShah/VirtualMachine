<img width="789" alt="Screenshot 2023-08-01 at 6 55 43 PM" src="https://github.com/AhbasShah/VirtualMachine/assets/141075365/1bd80a56-7022-448e-938b-ddb40d373e0d">

<h1>Creating A Virtual Machine On Azure</h1>
This guide provides instructions on how to set up a virtual machine on Microsoft Azure. It explains the initial configuration including details like VM name, geographical location, size, and operating system selection.

<h2>What Do You Need?</h2>

- Microsoft Azure Cloud: This is where the virtual machine is hosted. The user interacts with this environment through the Azure portal.

- User's Local System: This refers to the user's computer, which is used to access the Azure portal and later connect to the deployed VM.
completely reword this

<h2>Operating Systems That Can Use Virtual Machines </h2>

- macOS
- Windows
- Linux

<h2>Quick Steps</h2>

- Step 1- Access Azure Portal and Begin VM Setup
- Step 2- Basic VM Configuration
- Step 3- Review and Create VM

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Sign in to your Azure account at https://portal.azure.com.
Click on the "Create a resource" button (+), search for "Virtual Machine", select it from the dropdown menu, and click on "Create".
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Fill out the details for the VM including Subscription, Resource Group, VM name, Region, Image (OS), and Size.
Choose your authentication type and create a username and password.
Select appropriate inbound port rules. (For example, RDP (3389) for a Windows VM, or SSH (22) for a Linux VM.)
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After the Basic tab, you can go through the Disks, Networking, and Management tabs for more advanced configurations, or leave them as the default settings.
Click on "Review + Create" to validate your settings. If all settings pass the validation, you can click on "Create" to start the VM deployment.
</p>
<br />
