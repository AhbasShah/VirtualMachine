<img width="789" alt="Screenshot 2023-08-01 at 6 55 43 PM" src="https://github.com/AhbasShah/VirtualMachine/assets/141075365/1bd80a56-7022-448e-938b-ddb40d373e0d">

<h1>Creating A Virtual Machine On Azure</h1>
This guide provides instructions on how to set up a virtual machine on Microsoft Azure. It explains the initial configuration including details like VM name, geographical location, size, and operating system selection.

<h2>What Do You Need?</h2>

- Microsoft Azure Cloud: This is where the virtual machine is hosted. The user interacts with this environment through the Azure portal.

- User's Local System: This refers to the user's computer, which is used to access the Azure portal and later connect to the deployed VM.
completely reword this

<h2>Things To Note</h2>

Don't Ignore Security: Even though VMs are isolated environments, they are not immune to security threats. Always follow the principle of least privilege, keep your VMs updated, and use security tools provided by Azure, like Azure Security Center.

Don't Forget Cost Management: Azure (like any cloud provider) charges based on the resources you use. Remember to stop or deallocate VMs when they're not in use to avoid unnecessary costs. Also, select the VM size that best fits your needs, larger VMs are more expensive.

Don't Neglect Backups: Even though your VMs are in the cloud, you should still back them up. Azure offers a backup service that can be used for this purpose.

Don't Ignore Performance Monitoring: Azure provides a variety of monitoring tools that you should make use of to ensure your VMs are running smoothly. This can help you spot and fix performance issues before they become critical.

Don't Skip Planning: Before setting up a VM, have a clear understanding of what you need it for. This includes the specifications it should have (CPU, memory, storage), the networking setup, who needs access to it, and more.

Don't Overlook Compliance: If your application needs to comply with certain standards (like GDPR, HIPAA, etc.), ensure that your use of Azure VMs adheres to these requirements.

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
<img width="1250" alt="Screenshot 2023-08-01 at 8 29 00 PM" src="https://github.com/AhbasShah/VirtualMachine/assets/141075365/7a663d27-2245-4770-888d-905a2e5d8087">
</p>
<p>
Sign in to your Azure account at https://portal.azure.com.
Click on the "Create a resource" button (+), search for "Virtual Machine", select it from the dropdown menu, and click on "Create".
</p>
<br />

<p>
<img width="615" alt="Screenshot 2023-08-01 at 8 32 59 PM" src="https://github.com/AhbasShah/VirtualMachine/assets/141075365/40715c57-77ce-4655-bb4e-3dcf2f0358a9">
</p>
<p>
Fill out the details for the VM including Subscription, Resource Group, VM name, Region, Image (OS), and Size.
Choose your authentication type and create a username and password.
Select appropriate inbound port rules. (For example, RDP (3389) for a Windows VM, or SSH (22) for a Linux VM.)
</p>
<br />

<p>
<img width="615" alt="Screenshot 2023-08-01 at 8 36 41 PM" src="https://github.com/AhbasShah/VirtualMachine/assets/141075365/d81302b9-3548-4eb6-9c1b-4669dab5f47a">
</p>
<p>
After the Basic tab, you can go through the Disks, Networking, and Management tabs for more advanced configurations, or leave them as the default settings.
Click on "Review + Create" to validate your settings. If all settings pass the validation, you can click on "Create" to start the VM deployment.
</p>
<br />
