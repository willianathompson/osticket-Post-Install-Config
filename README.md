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

<p>
</p>

![image](https://github.com/user-attachments/assets/5bcc841a-6a2b-4e08-9ca2-37e884751962)

<p>
</p>
<p>
The setup folder was deleted from the osTicket installation directory (C:\inetpub\wwwroot\osticket) to prevent unauthorized access to the installation scripts and enhance system security.

</p>
<br />

<p>
  
![image](https://github.com/user-attachments/assets/80b01596-eabc-47be-98ae-2e88c25e7a7c)
</p>
<p>
The email settings for ticketing were successfully configured to enable osTicket to send and receive email notifications. SMTP was set up under Admin Panel > Settings > Email for outgoing emails, and email addresses were configured in Admin Panel > Settings > Mailboxes to receive incoming tickets. Auto-response settings were also configured to ensure customers receive acknowledgment emails upon ticket creation, facilitating seamless communication between the support team and customers.

</p>
<br />

<p>
  
![image](https://github.com/user-attachments/assets/8121394a-917b-4cbf-8a99-5f79ca49d6d5)

</p>
<p>
Ticketing categories and departments were successfully set up to streamline ticket management. New departments (e.g., Sales, IT Support, Billing) were created under Admin Panel > Manage > Departments, and ticket categories with custom fields were configured in Manage > Help Topics to ensure proper routing. New SLA's were arranged in Manage > SLA  for each ticket category. Each department was assigned a mailbox for ticket creation, and permissions were set to control access to specific departments, enhancing the efficiency and structure of the helpdesk operations.

</p>
<br />

![image](https://github.com/user-attachments/assets/b2e2894f-d1bf-4b69-be99-a93e593fd981)


</p>
<p>
Agent and admin user accounts were successfully created to manage the system efficiently. New agent accounts were set up under Admin Panel > Manage > Staff, with appropriate permissions assigned for accessing specific departments, managing tickets, and viewing reports. Roles (Admin, Agent, etc.) were assigned to ensure each user had the correct level of access, enabling agents to provide support and admins to configure and manage the system.

</p>
<br />

![image](https://github.com/user-attachments/assets/4f359c74-dd9c-4ee4-b9be-fd299b646db7)
![image](https://github.com/user-attachments/assets/cb2db211-49e6-4ca7-a609-9bd8748dfda4)

</p>
<p>
Security measures were successfully implemented to ensure data integrity and system reliability. A routine for database and file backups was set up using backup scripts and manual exports to protect ticket data. osTicket was configured to receive automatic updates for security patches, and the system was checked for new versions under Admin Panel > Settings > Version. File and folder permissions were reviewed and configured properly, particularly for the attachments, include, and upload directories, to prevent unauthorized access and data loss, ensuring long-term safety of the osTicket system.

</p>
<br />



