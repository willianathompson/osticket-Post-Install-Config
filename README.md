<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />



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
  
The setup folder was deleted from the osTicket installation directory (C:\inetpub\wwwroot\osticket) to stop unauthorized access to the installation files and improve system security.

</p>
<br />

<p>
  
![image](https://github.com/user-attachments/assets/80b01596-eabc-47be-98ae-2e88c25e7a7c)
</p>
<p>
  
The email settings for ticketing were successfully set up to allow osTicket to send and receive email notifications. SMTP (Simple Mail Transfer Protocol) was configured under Admin Panel > Settings > Email for outgoing emails, and email addresses were added under Admin Panel > Settings > Mailboxes to receive incoming tickets. Auto-response settings were also enabled so that customers receive confirmation emails when a ticket is created, making communication between the support team and customers smooth.

</p>
<br />

<p>
  
![image](https://github.com/user-attachments/assets/8121394a-917b-4cbf-8a99-5f79ca49d6d5)

</p>
<p>
  
Ticket categories and departments were successfully set up to make managing tickets easier. New departments, like Sales, IT Support, and Billing, were created under Admin Panel > Manage > Departments, and ticket categories with custom fields were added under Manage > Help Topics to make sure tickets are routed correctly. New SLA's (Service Level Agreements) were set up in Manage > SLA for each ticket category. Each department was given a mailbox for ticket creation, and permissions were set to control access to specific departments, making the helpdesk operations more organized and efficient.

</p>
<br />

![image](https://github.com/user-attachments/assets/b2e2894f-d1bf-4b69-be99-a93e593fd981)


</p>
<p>
  
Agent and admin user accounts were successfully created to help manage the system. New agent accounts were set up under Admin Panel > Manage > Staff, with the right permissions given to access specific departments, manage tickets, and view reports. Different roles, like Admin and Agent, were assigned to make sure each user had the right level of access, allowing agents to provide support and admins to configure and manage the system.

</p>
<br />

![image](https://github.com/user-attachments/assets/4f359c74-dd9c-4ee4-b9be-fd299b646db7)
![image](https://github.com/user-attachments/assets/cb2db211-49e6-4ca7-a609-9bd8748dfda4)

</p>
<p>

Security measures were successfully put in place to protect data and ensure the system runs smoothly. A backup routine for the database and files was set up using backup scripts and manual exports to keep ticket data safe. osTicket was configured to automatically receive updates for security patches, and the system was checked for new versions under Admin Panel > Settings > Version. File and folder permissions were reviewed and set up correctly, especially for the attachments, include, and upload folders, to prevent unauthorized access and data loss, ensuring the long-term safety of the osTicket system.

</p>
<br />



