# vpn-config
<h1>Analyzing the Impact of a VPN on IP Address Behavior</h1>

![Screen Shot 2023-10-26 at 10 25 58 AM](https://github.com/Courela23/vpn-config/assets/136120929/92abb410-7d7b-4c51-b7a7-ee531e5e9d33)

A VPN, or Virtual Private Network, is a technology that encrypts and secures your internet connection, providing privacy and protection from potential threats. It also allows you to access the internet as if you were in a different location, bypassing geo-restrictions and enhancing online anonymity.

</p>

<h1>Project Overview</h1>

![Screen Shot 2023-10-26 at 10 52 42 AM](https://github.com/Courela23/vpn-config/assets/136120929/e4f54715-d145-47c9-b30c-4b6ba8c3df7c)


<h2>Environments/Technologies Needed</h2>

- Microsoft Azure Account & VM
- ProtonVPN (free free subcription)
-	Remote Desktop for Windows or Mac

<h2>Operating System Used </h2>

- Macbook

<h2>Objective</h2>

- Create a resource group on Azure.
-	Establish a Windows 10 virtual machine in Azure
-	Initiate a remote desktop connection to access the virtual machine.
-	Retrieve the IP address and location of the VM using whatismyipaddress.com.
-	Download the free edition of ProtonVPN, and create an account if necessary.
-	Connect to a ProtonVPN server
-	Use whatismyipaddress.com to find the new IP address and location for the VM
-	Visit a Netflix to detect any modifications in URL or language.
-	Conclude by removing Resource Groups from Azure.

<h2>Summary</h2>

<p>

![Screen Shot 2023-10-26 at 9 52 37 AM](https://github.com/Courela23/vpn-config/assets/136120929/3303eff0-46e7-4467-a2a5-d896abb27056)
</p>
<p>
In this Azure project tutorial, we'll walk you through the process of setting up your Azure free subscription and creating a resource group. To get started, head to the Azure portal and either sign in with your existing Microsoft account or create one if you don't have it. Once you're in, go to the "Subscriptions" tab and click on "Add" to create your free Azure subscription. Follow the on-screen instructions to complete the subscription setup.

After that, under the "Resource groups" section, click on "Create" to establish a new resource group. Give it a meaningful name and choose your preferred region. This resource group will serve as an organized container for managing your Azure resources effectively. With these initial steps, you'll be ready to start building and managing your Azure project. 
 
<p>

![Screen Shot 2023-10-26 at 9 47 36 AM](https://github.com/Courela23/vpn-config/assets/136120929/da173a28-0d2a-43ca-a81b-e5b1333b2c17)

![Screen Shot 2023-10-26 at 10 15 24 AM](https://github.com/Courela23/vpn-config/assets/136120929/bfd44264-cf0c-4452-ae94-e9b40b2b0532)
</p>
<p>

- Navigate to Virtual Machines: In the Azure portal, click on "Virtual machines" in the left-hand menu.
-	Add a New Virtual Machine: Click on the "+ Add" button to create a new virtual machine.
-	Configure Basics: Provide details like the name, region, operating system, and resource group for your virtual machine. You can also choose the authentication method (password or SSH key).
-	Choose Size: Select the virtual machine size based on your needs, considering factors like CPU, memory, and disk space.
-	Configure Settings: Set options for networking, monitoring, and management. You can create or use an existing virtual network, configure monitoring settings, and enable features like Boot Diagnostics if needed.
-	Review + Create: Review your settings to ensure they are correct, and then click "Create" to start the virtual machine deployment.
-	Deployment: Azure will deploy your virtual machine based on your chosen configuration. You can monitor the deployment progress in the Azure portal.

<br />

<p>
 
 ![Screen Shot 2023-10-26 at 11 13 19 AM](https://github.com/Courela23/vpn-config/assets/136120929/9ef433ab-ca15-4b63-85f5-045179f5228d)

 ![Screen Shot 2023-10-26 at 9 48 27 AM](https://github.com/Courela23/vpn-config/assets/136120929/77493193-b86e-449d-a2dc-586f1677c192)

-	Access Your Virtual Machine: Once the deployment is complete, you can access your virtual machine via Remote Desktop (for Windows) or SSH (for Linux) using the credentials you provided during setup.
-	Get the Public IP Address: In the virtual machine overview, you'll find the public IP address. This is the address you'll use to connect.
-	Connect to the VM: In the Remote Desktop application, enter the public IP address of your virtual machine in the "Computer" field. Click "Connect."
-	Enter Credentials: You will be prompted to enter the username and password or credentials you provided during the virtual machine setup.
-	Connect: After entering the credentials, click "OK" or "Connect." The Remote Desktop session will establish, and you will have access to your virtual machine.

</p>
<p> 

<p>
 
![Screen Shot 2023-10-26 at 12 11 14 PM](https://github.com/Courela23/vpn-config/assets/136120929/fc180e09-d07e-4795-8434-d6da3f9d0a95)
</p>
<p>  
On the Virtual Machine, launch a web browser, then enter "whatismyipaddress.com" into the search bar. Make a record of the IP address shown. Please be cautious not to share or reveal your public IP address to unauthorized individuals, as it could potentially expose your private location and make you vulnerable to malicious actions aimed at your network.
</p>
<br />

<p>

</p>
<p>

</p>
<br />

<p>

</p>
<br />

<p>

</p>
<p>
After the virtual machine is created, click on the virtual machine and copy the public IP address of the virtual machine in order to connect to it remotely. Depending on the operating system, open up either "Remote Desktop Connection" (Windows) or in this case, "Microsoft Remote Desktop" (MacOS), and click on "Add PC".
</p>
<br />

<p>

</p>
<p>
Input the public IP address of the virtual machine in for the "PC Name" then click "add".
</p>
<br />

<p>
 
</p>
<p>
Click on the interface of the virtual machine and input the username and password that you used when creating the virtual machine.
</p>
<br />

<p>
 
![Screen Shot 2023-10-26 at 10 14 04 AM](https://github.com/Courela23/vpn-config/assets/136120929/d07447f7-f5a9-48df-a905-b4c3f7348e36)
</p>
<p>
After the connection to the virtual machine is completed, open up the web browser and type in whatismyipaddress.com and take note of the ip that is displayed. 
</p>
<br />

<p>

</p>
<p>
Open up another tab, and type in protonvpn.com in the browser. Click on create free account and fill out the informatoin to create your account. 
</p>
<br />

<p>
 
![Screen Shot 2023-10-26 at 9 50 59 AM](https://github.com/Courela23/vpn-config/assets/136120929/a02036b0-6e94-4ad7-9d40-ceeb0f5bc821)
 
![Screen Shot 2023-10-26 at 10 12 21 AM](https://github.com/Courela23/vpn-config/assets/136120929/6213e6e5-b5fa-43fd-98b5-252e2f0e0c56)
 
</p>
<p>
Once you've registered for a Proton VPN account, obtain the Proton VPN client tailored for your operating system by downloading it.
</p>
<br />

<p>


</p>
<p>
Once the download is completed, open up the VPN client installer and select all the default options for the proton VPN setup wizard. 
</p>
<br />

<p>

</p>
<p>
Once the installation is completed open up the proton VPN application and login with the same credentials used to create the account. 
</p>
<br />

<p>

</p>
<p>
When you get logged in there will likely only be a few options for VPN servers due to the limited selection of the free account.
</p>

<p>
 
![Screen Shot 2023-10-26 at 10 12 53 AM](https://github.com/Courela23/vpn-config/assets/136120929/1eb84e7f-8d99-425f-8651-fab1263b4f8c)
</p>
<p>  
Pick one of the available VPN servers for connection and allow the connection to establish. For this example, Japan has been chosen.
</p>  

<p>
 
![Screen Shot 2023-10-26 at 10 14 04 AM](https://github.com/Courela23/vpn-config/assets/136120929/d07447f7-f5a9-48df-a905-b4c3f7348e36)
 
![Screen Shot 2023-10-26 at 10 14 30 AM](https://github.com/Courela23/vpn-config/assets/136120929/56330199-751e-4320-8ade-43a93420cd2e)

</p>
<p>
Once the connection is completed, refresh the dashboard interface to confirm an established connection, open up a web browser and go to "whatismyipaddress.com" and you'll see that the public ip address of the VM now displays region in which the VPN server is located in. 
</p>
  
In Conclusion: Simply creating a virtual machine similarly acts like a VPN by displaying an IP address where the VM's server is located when choosing the region. The main difference is that a VPN will provide content in the region's language and relevant information exclusive to the region. To verify this simply open up any popular website in a browser and review the display of the language and information on the webpage and compare it to the language and content when viewing that same webpage on your actual PC. 
. 
</p>
<br />
