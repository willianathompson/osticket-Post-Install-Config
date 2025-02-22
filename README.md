<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Delete the setup Folder
- Configure Email Settings for Ticketing
- Set Up Ticketing Categories and Departments
- Create Agent and Admin User Accounts
- Set Up Security Measures (Backup and Updates)

<h2>Configuration Steps</h2>

![image](https://github.com/user-attachments/assets/8f9f8edd-e81e-4897-abb9-efeb4693e3f1)


![image](https://github.com/user-attachments/assets/769ee3b1-dc3b-42b1-95bd-83731632d75f)



![image](https://github.com/user-attachments/assets/5769fec7-ff70-48ee-a7a0-0d1199b5c7b1)



![image](https://github.com/user-attachments/assets/1808d4bd-65b4-4816-b832-5f7d4db6a95e)




![image](https://github.com/user-attachments/assets/67597874-da34-4bed-98c2-cfa32118273a)




![image](https://github.com/user-attachments/assets/31e99527-527c-4ec6-8a93-b21a7780d545)




![image](https://github.com/user-attachments/assets/b7971c03-dbdf-490e-8b77-b325309e452c)











![image](https://github.com/user-attachments/assets/2a9e8ea0-5432-4243-be53-2778221f8d5f)

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The setup folder was deleted from the osTicket installation directory (C:\inetpub\wwwroot\osticket) to prevent unauthorized access to the installation scripts and enhance system security.

</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The email settings for ticketing were successfully configured to enable osTicket to send and receive email notifications. SMTP was set up under Admin Panel > Settings > Email for outgoing emails, and email addresses were configured in Admin Panel > Settings > Mailboxes to receive incoming tickets. Auto-response settings were also configured to ensure customers receive acknowledgment emails upon ticket creation, facilitating seamless communication between the support team and customers.

</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Ticketing categories and departments were successfully set up to streamline ticket management. New departments (e.g., Sales, IT Support, Billing) were created under Admin Panel > Manage > Departments, and ticket categories with custom fields were configured in Manage > Ticket Forms to ensure proper routing. Each department was assigned a mailbox for ticket creation, and permissions were set to control access to specific departments, enhancing the efficiency and structure of the helpdesk operations.

</p>
<br />


</p>
<p>
Agent and admin user accounts were successfully created to manage the system efficiently. New agent accounts were set up under Admin Panel > Manage > Staff, with appropriate permissions assigned for accessing specific departments, managing tickets, and viewing reports. Roles (Admin, Agent, etc.) were assigned to ensure each user had the correct level of access, enabling agents to provide support and admins to configure and manage the system.

</p>
<br />

</p>
<p>
Security measures were successfully implemented to ensure data integrity and system reliability. A routine for database and file backups was set up using backup scripts and manual exports to protect ticket data. osTicket was configured to receive automatic updates for security patches, and the system was checked for new versions under Admin Panel > Settings > Version. File and folder permissions were reviewed and configured properly, particularly for the attachments, include, and upload directories, to prevent unauthorized access and data loss, ensuring long-term safety of the osTicket system.

</p>
<br />


</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />


