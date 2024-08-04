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

- Internet Information Services
- PHP Manager 
- Rewrite Moduel 
- MySQL

![Prereqs](https://github.com/user-attachments/assets/c433c8b4-b294-42d8-b575-3f6d21915f40)

<h2>Installation Steps</h2>

![Dropping osTicket upload file into wwwroot](https://github.com/user-attachments/assets/c9ef52a2-c9a2-4fb2-9802-ac911b96050f)


![rename osticket](https://github.com/user-attachments/assets/f4f02ea2-9555-4507-94fa-ba22ad812699)

In these two screenshots, I extract and copy osticket's upload folder into the wwwroot folder. This folder is the virtual machine's web server's main folder. Once all the files are copied into the wwwroot folder, I rename the upload folder to "osticket". 
<br />



https://github.com/user-attachments/assets/91bd0711-3240-4c00-b55a-427b493c27f6


<p>
</p>
<p>
In this screenrecording, I open IIS back up to open up osTicket's website. This shows that osticket is now installed and running. </p>
<br />



![Screenshot 2024-07-31 131627](https://github.com/user-attachments/assets/51d2e8f3-2363-4ca8-b48a-f8b01c9041df)





</p>
<p>
This screenshot shows the completion of a database I set up through HeidiSQL. HeidiSQL links the prereq, MySQL's server and allows me to set up the database that osTicket will use. 

![OsTicket Installed](https://github.com/user-attachments/assets/82d3ce3a-e5cd-49ae-b4c4-d81ace365d0b)



