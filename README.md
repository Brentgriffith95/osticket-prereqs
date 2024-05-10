# osticket-prereqs<p align="center">
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

- Azure Virtual Machine
- Internet Information Services (IIS)
- PHP Manager
- Rewrite Module
- VC Redist
- MySQL
- Heidi SQL
- osTicket v1.15.8
- Link to downloads: https://drive.google.com/drive/u/0/folders/1APMfNyfNzcxZC6EzdaNfdZsUwxWYChf6


<h2>Installation Steps</h2>


![1YKln1Z - Imgur](https://github.com/Brentgriffith95/osticket-prereqs/assets/150200843/2964710d-1deb-4ce6-ad0f-9754de82c133)

To begin this tutorial we will be creating a VM in Azure. Then we will be connecting through a Remote Desktop Connection. In order to do this go to the VM, copy its public IP address and connect to RDC (Remote Desktop Connection).


![o0pcewd - Imgur](https://github.com/Brentgriffith95/osticket-prereqs/assets/150200843/4de11884-9bc5-45eb-ade5-af7a855ae853)
Next copy this link and paste into your VMs web browser.
https://drive.google.com/drive/folders/1DABjdlQAXxIvWIURTiBelD0rw6IzLNru


![odrBI34 - Imgur](https://github.com/Brentgriffith95/osticket-prereqs/assets/150200843/199e319f-4141-4822-8c81-a699d8b457d1)

Now go into the Programs section in control panel and click "Turn Windows features on or off"


![JFtbeJu - Imgur](https://github.com/Brentgriffith95/osticket-prereqs/assets/150200843/abdd9aa2-35b3-46e1-a5fe-b0c38980b710)

Install and enable IIS in Windows with CGI. Make sure to check every box shown in this vsiual and click ok.



![5o8pCQV - Imgur](https://github.com/Brentgriffith95/osticket-prereqs/assets/150200843/6f2b8850-94cd-4016-8c2b-dce88df7adc8)

After IIS is installed, open Microsoft Edge and type "127.0.0.1" in the browser. IIS should open up as shown in the visual. If not go back to control panel and make sure CGI is checked.




![NXQSCeG - Imgur](https://github.com/Brentgriffith95/osticket-prereqs/assets/150200843/039b8079-d518-4f05-a668-6f0dde1e1092)



![3eyeq1c - Imgur](https://github.com/Brentgriffith95/osticket-prereqs/assets/150200843/cccfddbd-4bd1-4114-aca4-7c7cf42465d4)

Now we download and install PHPManagerForIIS_V1.5.0.msi as well as rewrite_amd64_en-US.msi.


![hX3c87m - Imgur](https://github.com/Brentgriffith95/osticket-prereqs/assets/150200843/bc8ce9ab-cdf9-46d6-be4d-54dd5c5e571c)

Then we create a new directory in the C drive called PHP or C:\PHP.


![JOBRQXl - Imgur](https://github.com/Brentgriffith95/osticket-prereqs/assets/150200843/cec9f103-ffb2-4283-8742-99d0a42c5f14)

Download and install  php-7.3.8-nts-Win32-VC15-x86.zip and make sure to extract all content into the C:\PHP directory.


![GgEZmQN - Imgur](https://github.com/Brentgriffith95/osticket-prereqs/assets/150200843/2dd9c70f-2d56-4646-ac9f-21f6180b57eb)

Next download and install VC_redist.x86.exe. Then download and install mysql-5.5.62-win32.msi.
The setup will be  Launch Wizard > Standard Configuration > Next > Set the password to "Password1" > Execute



