<h1>Active Directory Lab</h1>

<h2>Description</h2>
In this project I built an Active Directory homelab using virtualization through Oracle VM VirtualBox. This project aided me in gaining real world experience and practice troubleshooting with Active Directory.
Using scripts in Windows PowerShell, I was able to generate the following for my database:<br />
Computers  = 2 <br />
Workstations = 1<br />
Servers    = 1<br />
Users      = 2970<br />
Groups     = 68<br />
                                                          
<br />


<h2>Utilities Used</h2>

- <b>Oracle VM VirtualBox</b>
- <b>Windows Active Directory</b>
- <b>Windows PowerShell</b>
- <b>Remote Desktop</b>


<h2>Environments Used </h2>

- <b>Windows 10</b>
- <b>Windows Server 2019</b>


<h2>Skills Learned </h2>

- Built and managed an Active Directory database
- Added new user accounts to Active Directory
- Assigned static IP addresses
- Basic PowerShell scripts



<h2>I have included images of the project below:</h2>

<p align="center">
Here is a list of users that were added to Active Directory with the PowerShell script.  <br/>
<img src="https://imgur.com/Zq4eSom.png" height="80%" width="80%" alt="Active Directory"/>
<br />
<br />
I created a user account "PC1", from there I was able to successfully ping my Active Directory server at 192.168.20.10 which verified they were connected on the same network<br/>
<img src="https://imgur.com/pufsLxn.png" height="80%" width="80%" alt="Active Directory"/>
<br />
<br />
Assigning a static IP address for my user account "PC1" <br/>
<img src="https://imgur.com/V7gtZYq.png" height="80%" width="80%" alt="Active Directory"/>
<br />
<br />
 <br/> 
 Accessing user "PC1" via remote desktop<br/>
<img src="https://imgur.com/HBIjkah.png" height="80%" width="80%" alt="Active Directory"/>
<br />
<br />
Here I used a PowerShell script which gathered information on the amount of computers, workstations, servers, users and groups<br/>
 <img src="https://imgur.com/my3YCdm.png" height="80%" width="80%" alt="Active Directory"/>
<br />
<br />


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
