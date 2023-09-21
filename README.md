<h1>Control Andoid Device With Metasploit Framwork</h1>

 ### [YouTube Demonstration](https://www.youtube.com/watch?v=8ZFNiQce4Ds)

<h2>Description</h2>
Project consists of a simple PowerShell script that walks the user through "zeroing out" (wiping) any drives that are connected to the system. The utility allows you to select the target disk and choose the number of passes that are performed. The PowerShell script will configure a diskpart script file based on the user's selections and then launch Diskpart to perform the disk sanitization.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Linux or Windows with metasploit framwork</b> 
- <b>Shared Drive / medium of data transfer</b>

<h2>Environments Used </h2>

- <b>Kali Linux</b> 

<h2>Program walk-through:</h2>

<p align="center">
Run the following command to create a RAT Application: <br/>
<img src="https://i.imgur.com/7JgmO0B.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Share the RAT app to victim mobile:  <br/>
<img src="https://i.imgur.com/GJtP2ua.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Install the App: <br/>
<img src="https://i.imgur.com/l2Ry84A.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
I am using MSFconsole as a listner:  <br/>
<img src="https://i.imgur.com/hrJBBBV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Configure the listner:  <br/>
<img src="https://i.imgur.com/lPBvTTb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Checking all the requirements are fullfied :  <br/>
<img src="https://i.imgur.com/e8h4cJc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Give all the permission to RAT app:  <br/>
<img src="https://i.imgur.com/iJViMX8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <br />
<br />
Run the exploit:  <br/>
<img src="https://i.imgur.com/jvT0Xb8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
We capture the information in MSFconsole:  <br/>
<img src="https://i.imgur.com/QUuX5bi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
