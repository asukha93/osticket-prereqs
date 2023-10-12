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

- Install / Enable IIS in Windows
- Install Web Platform Installer
- Install osTicket v1.15.8
- Download and Install HeidiSQL

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/uhlNvHS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The installation of the IIS Web Server was carried out with the purpose of serving ASP.NET web applications and static websites. Additionally, it has the capability to function as an FTP server, support WCF services, and can be expanded to accommodate web applications developed on different platforms like PHP, as seen in its application for osTicketing. To activate IIS on a Windows Server, you have the option of using either PowerShell or Server Manager. In this specific setup, PowerShell was employed for the installation process.
</p>
<br />

<p>
<img src="https://i.imgur.com/lBKIlLm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The Web Platform Installer was obtained in order to stay current with the most recent components of the Microsoft Web Platform, encompassing Internet Information Services (IIS) and SQL Server Express. This user-friendly tool serves the purpose of ensuring the seamless operation of various web applications.
</p>
<br />

<p>
<img src="https://i.imgur.com/ZYNODkB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
osTicket, a support ticket system, was implemented to enhance the quality of customer service and overall experience. It boasts compatibility with a wide range of operating systems and offers a plethora of features and solutions for efficient help desk management. The osTicket software is developed using PHP as its programming language and relies on a MySQL database for storing information.
</p>
<br />

<p>
<img src="https://i.imgur.com/k5Kv5C7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
HeidiSQL was installed and downloaded to enable tasks such as data browsing, editing, table and view creation, as well as the editing of procedures, triggers, and scheduled events, along with managing database structures. This versatile software supports various database systems, including MariaDB and MySQL, running on the computer.
</p>
<br />
