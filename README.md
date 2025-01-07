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

- Operating System: Windows 10 (21H2)
- Web Server: IIS with CGI feature enabled.
- PHP Version: 7.3.8.
- Database: MySQL 5.5.
- Tools:
PHP Manager for IIS.
URL Rewrite Module.
HeidiSQL for database management.

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Enable IIS Features:

Enable "Internet Information Services" and "CGI" in Windows Features.
Install Dependencies:

Install PHP Manager and URL Rewrite Module.
Download and configure PHP 7.3.8 in C:\PHP.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Set Up MySQL:

Install MySQL 5.5, set the root password, and create a database named osTicket.
Install osTicket:

Download osTicket and extract the "upload" folder to C:\inetpub\wwwroot\osTicket.
Rename ost-sampleconfig.php to ost-config.php and set appropriate permissions.
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure PHP Extensions:

Enable php_imap.dll, php_intl.dll, and php_opcache.dll in PHP Manager.
Finalize Installation:

Access http://localhost/osTicket in your browser and follow the setup wizard.
After installation, delete the setup folder and set ost-config.php to read-only.
</p>
<br />
