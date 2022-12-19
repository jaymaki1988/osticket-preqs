<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Azure Tenant
- Subsricption
- Google Drive Instalation Files
- Item 4
- Item 5

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
We will first start by creating a rescource group in Microsoft Azure. Click on rescource group or search rescource in the search bar. Choose a name and a region. After that has been done, we will next create a Virtual Machine in the rescource group. Type in the search bar for "Virtual Machine" and click on it. Make sure to select the rescource group we just made. Give the machine a name, choose the same location as the recource group. Under the image section choose Windows 10 Pro. Next step is to choose what size or components the virtual machine will run off. I recomend at least the 2 cpu 16 memory. Click next for disk and network. It will automatically create a virtual network and subnet. Click review and create. 
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next we are going to launch windows in the virtual desktop. Click on the virtual machine we just made and cop the Public IP address. There is a copy icon to the right of the IP address. Go to the search bar near the start window and search for remote desktop. Paste the IP address in the Computer section of Remote Desktop. Type in user name and password you just made. Once it starts up, say no to all the settings it pops up with. Next we are going to setup ISS in windows. 
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click on Microsoft Edge and paste the Google Drive Installation in an open tab. Go to the Search near start button and type Control Panel and click on it. Click on Uninstall a program. CLick on the Turn Windows features on or off. Search for Internet Information Services and selct the box and click ok. It should have Created a folder path from the image above with the wwwroot. Install the WebPlatforminstaller from the Google Drive Instalation Files. Once it is installed, go to the search and search for Web Platformer and open it. Once it is opened go to the search bar on the top right and type MySQL. Click on Add from MySQL WIndows. Next we will add PHP files. Type in the search for PHP and on Name to view search results by name. Add all PHP x86 files starting with the 5.6.31 to 7.3.25(x86). Click on Install.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
A popup window will ask you to create an admin accout password. The admin name will be root and you just create a password. Click on I accept and it will attempt to download files. For any of the files that fail, refer to the Google Drive files for any that failed. Next you will download the osTicket file from the Google Drive files. It will end up in your Downloads Folder. Right click it and Extract All in the downloads folder. Once that is complete, click on the osTicket folder and copy the "upload" folder in there to the folder we navigated to earlier c:\inetpub\wwwroot. Rename the "upload" folder to "osTicket".
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
We will now be reloading IIS. Go to the search next to start and search IIS. On the right side click on the restart button.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
