<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

- <h2>List of Prerequisites</h2>

- Enabled internet info services (IIS)
- Install PHP Manager
- Rewrite Module
- Install MySQL & set up username and password
- Configure permissions
- Register PHP from within IIS
- Enable Extensions
- Assign Permissions
- Install Heidi SQL & set up username and password


<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/BQv3Pqu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
install / Enable IIS in windows WITH CGI World Wide Web Services -> Application Development Features -> [X] CGI</p>
<br />
<p>
<img src="https://i.imgur.com/k8bQKmy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Open IIS as an admin & register PHP from within IIS
</p>
<br />

<p>
<img src="https://i.imgur.com/er25CHj.png" alt="Disk Sanitization Steps"/>
</p>
<p>
Enable php extension by going to IIS, sites -> Default -> osTicket
</p>
<br />

<p>
<img src="https://i.imgur.com/VkPI674.png" alt="Disk Sanitization Steps"/>
</p>
<p>
Assign Permissions:
  
Disable inheritance -> Remove All
  
New Permissions -> Everyone -> All
</p>
<br />

<p>
<img src="https://i.imgur.com/BLMrHu8.png" alt="Disk Sanitization Steps"/>
</p>
<p>
Continue Setting up osticket in the browser (install heidei sql is something that helps you to connects to the database to interact with it.)
</p>
<br />

<p>
<img src="https://i.imgur.com/d35Sbjq.png" alt="Disk Sanitization Steps"/>
</p>
<p>
Create a database within heidi called “osTicket”
</p>
<br />

<p>
<img src="https://i.imgur.com/FSJ6MCQ.png" alt="Disk Sanitization Steps"/>
</p>
<p>
Installation Complete ✅
</p>
<br />
