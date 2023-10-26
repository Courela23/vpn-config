# vpn-config
<h1>Analyzing the Impact of a VPN on IP Address Behavior</h1>

![Screen Shot 2023-10-26 at 10 25 58 AM](https://github.com/Courela23/vpn-config/assets/136120929/92abb410-7d7b-4c51-b7a7-ee531e5e9d33)

A VPN, or Virtual Private Network, is a technology that encrypts and secures your internet connection, providing privacy and protection from potential threats. It also allows you to access the internet as if you were in a different location, bypassing geo-restrictions and enhancing online anonymity.



![Screen Shot 2023-10-26 at 10 13 33 AM](https://github.com/Courela23/vpn-config/assets/136120929/83aad9a0-3865-4744-ae36-2679a968802f)

![Screen Shot 2023-10-26 at 10 14 04 AM](https://github.com/Courela23/vpn-config/assets/136120929/d07447f7-f5a9-48df-a905-b4c3f7348e36)
![Screen Shot 2023-10-26 at 10 14 30 AM](https://github.com/Courela23/vpn-config/assets/136120929/56330199-751e-4320-8ade-43a93420cd2e)

![Screen Shot 2023-10-26 at 10 15 04 AM](https://github.com/Courela23/vpn-config/assets/136120929/be51b002-a6ca-4fbd-931f-8513d0fd31ca)
![Screen Shot 2023-10-26 at 10 15 24 AM](https://github.com/Courela23/vpn-config/assets/136120929/bfd44264-cf0c-4452-ae94-e9b40b2b0532)
![Screen Shot 2023-10-26 at 9 47 36 AM](https://github.com/Courela23/vpn-config/assets/136120929/da173a28-0d2a-43ca-a81b-e5b1333b2c17)
![Screen Shot 2023-10-26 at 9 48 09 AM](https://github.com/Courela23/vpn-config/assets/136120929/9b13e855-e36a-4ee5-9aa7-1b85abf01857)
![Screen Shot 2023-10-26 at 9 48 27 AM](https://github.com/Courela23/vpn-config/assets/136120929/77493193-b86e-449d-a2dc-586f1677c192)
![Screen Shot 2023-10-26 at 9 50 29 AM](https://github.com/Courela23/vpn-config/assets/136120929/3a55c907-5872-431a-bd28-994c77ee585d)
![Screen Shot 2023-10-26 at 9 50 59 AM](https://github.com/Courela23/vpn-config/assets/136120929/a02036b0-6e94-4ad7-9d40-ceeb0f5bc821)
![Screen Shot 2023-10-26 at 9 52 37 AM](https://github.com/Courela23/vpn-config/assets/136120929/3303eff0-46e7-4467-a2a5-d896abb27056)

</p>

<h1>Observing the Effect of a VPN on IP Addressing</h1>
In this project, the impact of a virtual private network (VPN) on IP address will be observed. <br />

![Screen Shot 2023-10-26 at 10 52 42 AM](https://github.com/Courela23/vpn-config/assets/136120929/e4f54715-d145-47c9-b30c-4b6ba8c3df7c)


<h2>Environments and Technologies Used</h2>

- Microsoft Azure Account & VM
- ProtonVPN (free free subcription)
-	Remote Desktop for Windows or Mac


<h2>Operating System Used </h2>

- Windows 10 (21H2)

<h2>High-Level Steps</h2>

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
<img src="https://i.imgur.com/8KmJIqO.png" height="70%" width="70%"/> 
</p>
<p>
On your pc type in "free azure account". Click on the link which should say "Create Your Azure Free Account Today". In the webpage, click on the "start free" box. 
 
<p>
<img src="https://i.imgur.com/t9x6DOE.jpg" height="70%" width="70%"/> 
</p>
<p>
You will be prompted to sign into an existing Microsoft account or to create one (Note: creating an azure account does require the use of a credit card, but will not charge the card unless the free $200 of credit that is applied to the account is exceeded so be sure to have that ready to input.)
</p>
<br />

<p>
<img src="https://i.imgur.com/HlPj27w.jpg" height="70%" width="70%"/>
</p>
<p>
After creating your account, go to the Azure portal by typing in portal.azure.com in the search bar. Verify the creation of your new subscription by typing in "subscription" in the Microsoft azure search bar interface. 

<p>
<img src="https://i.imgur.com/VB0la1r.jpg" height="70%" width="70%"/>
</p>
<p>  
Open another web browser and type in the search bar "whatismyipaddress.com". Take a note of the IP address displayed. (Note: it's important not to share or  disclose your public IP address with just anyone because it can give away your private location and worst give a malicious actor a target to use malicious techniques against your network).
</p>
<br />

<p>
<img src="https://i.imgur.com/HlPj27w.jpeg" height="70%" width="70%"/>
</p>
<p>
Go back to the Microsoft Azure interface. Type in "virtual machine" in the Microsoft azure search bar and select the virtual machine icon. This step will require basically just inputting different names or titles and selecting different types of resources. 
</p>
<br />

 - Subscription: (choose subscription you created)
 - Resource Group: (leave unmarked, or create in advance)
 - Virtual machine: (provide a name)
 - Region: select any available region and take note of it (in this demonstration, (Europe) France Central is used)
 - Image: select "Windows 10 pro, version 21H2 - Gen2 (free services eligible)" 
 - Size: (choose an option of your choice for the best performance)
 - Administrator Account: (create a username and password)
 - Establish a Windows 10 virtual machine on Azure.
Initiate a remote desktop connection to access the virtual machine.
Retrieve the IP address and location of the VM using whatismyipaddress.com.
Download the free edition of ProtonVPN, and create an account if necessary.
Connect to a ProtonVPN server located in a different country.
Recheck the VM's IP address and location using whatismyipaddress.com.
Visit a webpage to detect any modifications in URL or language.
Conclude by removing Resource Groups from Azure.

<p>
Check the licensing agreement box then click "Review + Create". Once the process is finished validating all the resources, click "Create" to initialize the virtual machine.
</p>
<br />

<p>
<img src="https://i.imgur.com/eJby71b.jpeg" height="70%" width="70%"/>
</p>
<p>
After the virtual machine is created, click on the virtual machine and copy the public IP address of the virtual machine in order to connect to it remotely. Depending on the operating system, open up either "Remote Desktop Connection" (Windows) or in this case, "Microsoft Remote Desktop" (MacOS), and click on "Add PC".
</p>
<br />

<p>
<img src="https://i.imgur.com/UA1EG9D.jpeg" height="70%" width="70%"/>
</p>
<p>
Input the public IP address of the virtual machine in for the "PC Name" then click "add".
</p>
<br />

<p>
<img src="https://i.imgur.com/4lP0uQi.jpeg" height="70%" width="70%"/>  
</p>
<p>
Click on the interface of the virtual machine and input the username and password that you used when creating the virtual machine.
</p>
<br />

<p>
<img src="https://i.imgur.com/buyTxfz.jpeg" height="70%" width="70%"/>
</p>
<p>
After the connection to the virtual machine is completed, open up the web browser and type in whatismyipaddress.com and take note of the ip that is displayed. 
</p>
<br />

<p>
<img src="https://i.imgur.com/RqkwUO1.jpg" height="70%" width="70%"/>
</p>
<p>
Open up another tab, and type in protonvpn.com in the browser. Click on create free account and fill out the informatoin to create your account. 
</p>
<br />

<p>
 
![Screen Shot 2023-10-26 at 10 12 21 AM](https://github.com/Courela23/vpn-config/assets/136120929/6213e6e5-b5fa-43fd-98b5-252e2f0e0c56)
 
</p>
<p>
Once you've registered for a Proton VPN account, obtain the Proton VPN client tailored for your operating system by downloading it.
</p>
<br />

<p>
<img src="https://i.imgur.com/D8xY7wX.jpg" height="70%" width="70%"/>
</p>
<p>
Once the download is completed, open up the VPN client installer and select all the default options for the proton VPN setup wizard. 
</p>
<br />

<p>
<img src="https://i.imgur.com/beXSGzh.jpg" height="70%" width="70%"/>
</p>
<p>
Once the installation is completed open up the proton VPN application and login with the same credentials used to create the account. 
</p>
<br />

<p>
<img src="https://i.imgur.com/oMr3V1Y.jpg" height="70%" width="70%"/>
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
 
![Screen Shot 2023-10-26 at 10 14 30 AM](https://github.com/Courela23/vpn-config/assets/136120929/56330199-751e-4320-8ade-43a93420cd2e)
 
</p>
<p>
Once the connection is completed, refresh the dashboard interface to confirm an established connection, open up a web browser and go to "whatismyipaddress.com" and you'll see that the public ip address of the VM now displays region in which the VPN server is located in. 
</p>
  
In Conclusion: Simply creating a virtual machine similarly acts like a VPN by displaying an IP address where the VM's server is located when choosing the region. The main difference is that a VPN will provide content in the region's language and relevant information exclusive to the region. To verify this simply open up any popular website in a browser and review the display of the language and information on the webpage and compare it to the language and content when viewing that same webpage on your actual PC. 
. 
</p>
<br />
