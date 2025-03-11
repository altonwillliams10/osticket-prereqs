<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

☁️ Cloud Platform:


- Microsoft Azure (Virtual Machines/Compute)

🌐 Remote Access & Web Services:


- Remote Desktop Protocol (RDP) (to connect to the VM)

- Internet Information Services (IIS) (Web Server for osTicket)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Setup a Virtual Machine in Azure
- Install the osTicket requirements
- Install osTicket itself
- IIS (Internet Information Services) – Used as a web server
- PHP – Required for osTicket to function
- MySQL - (MySQL Server) – Database for storing tickets
- osTicket Download Package

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/kJ7Z3FO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the screenshot above you will see me navigating to the top left of the screenshot to create a new virtual machine. By using a Microsoft Azure VM I will be utilizing a dedicated environment to install and configure osTicket without affecting my personal computer.
</p>
<br />

<p>
<img src="https://i.imgur.com/lQag8Fm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the screenshot above you'll see I Installed IIS because without IIS, there’s no way to access the ticketing system via a web browser.
After enabling IIS, you can open http://localhost/osticket/setup/ and start the installation!
</p>
<br />

<p>
<img src="https://i.imgur.com/ltoPUC6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The screenshot above clearly shows that the process I implemented, was successful on installing OsTicket.
</p>
<br />
