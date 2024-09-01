
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Azure Virtual Machine
- IIS Internet Information Services
- PHP Manager for IIS
- Rewrite Module
- Visual C++ Redistributable (VC redist)
- MySQL Server (storage database)
  

<h2>prerequisite: PHP Installation Steps</h2>

<p>
<img src="https://i.imgur.com/chyaFyl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Open IIS as an Administrator in your Windows 10. This is done by searching IIS the search bar, right click, select run as administrator. This is where you'll begin the PHP registration, from within the IIS. 
  
</p>
<br />

<p>
<img src="https://i.imgur.com/chyaFyl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Hover and click on the PHP Manager Icon in the IIS database to proceed with registration, then Reload IIS by selecting Stop then Start in the server settings.  
</p>
<br />


<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

<h2>osTicket Installation Steps</h2>
  
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download osTicket from the File Folder. Extract and copy "upload" folder to the inetpub root folder. Rename the upload folder to osTicket. Reload IIS. Upon relaunch go to sites-default-osTicket click "Browse *80". Notice that some extensions are not enabled. This can be fixed in the PHP Manager. Continue setting up OSTicket in the browser, using the HeidiSQL connect to the osTicket session, create your username and password for installation. Once installed, browse to the help desk login page. 
</p>
<br /> 

<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
