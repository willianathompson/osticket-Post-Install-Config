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
1. Delete the setup Folder
Security Reason: After completing the installation, you should immediately delete the setup folder from the osTicket installation directory to prevent unauthorized access to the installation scripts.
How to Do It:
Navigate to the osTicket installation folder (e.g., C:\inetpub\wwwroot\osticket).
Delete the setup folder.
This is a critical step to secure your system.

</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
2. Configure Email Settings for Ticketing
Purpose: Ensure osTicket can send and receive email notifications for new tickets, responses, and updates.
Steps:
Go to Admin Panel: Log in to the osTicket Admin Dashboard.
Configure Email Settings:
Under Admin Panel > Settings > Email, set up the SMTP server to send outgoing emails (e.g., Gmail SMTP, Mailgun, etc.).
In Admin Panel > Settings > Mailboxes, set up email addresses (e.g., support@yourdomain.com) to receive incoming emails for ticket creation.
Configure Auto-Response settings to ensure customers receive acknowledgment emails upon ticket creation.
This ensures seamless email communication between your support team and customers.

</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
3. Set Up Ticketing Categories and Departments
Purpose: Organize your tickets by category and department to streamline ticket management.
Steps:
In the Admin Panel, go to Manage > Departments to create new departments (e.g., Sales, IT Support, Billing).
Go to Manage > Ticket Forms to configure ticket categories and custom fields, ensuring tickets are routed appropriately.
Assign each department a mailbox for ticket creation, if required, and set permissions for who can access certain departments.
Proper categorization helps improve the efficiency and structure of your helpdesk operations.

</p>
<br />


</p>
<p>
4. Create Agent and Admin User Accounts
Purpose: Set up roles for your support team and admin staff to manage the system efficiently.
Steps:
In the Admin Panel, go to Manage > Staff to create agent accounts.
Assign appropriate permissions, such as the ability to view specific departments, manage tickets, or view reports.
Assign roles (Admin, Agent, etc.) to ensure each user has the correct level of access.
This ensures that agents can access the features they need to provide support, while admins can configure and manage the system.

</p>
<br />

</p>
<p>
5. Set Up Security Measures (Backup and Updates)
Purpose: Implement security protocols and ensure data integrity through regular backups.
Steps:
Backups: Set up a routine for database and file backups to protect ticket data. Use database backup scripts or manual exports to secure data.
Update Configuration: Ensure osTicket is set to receive automatic updates for security patches. You can check for new versions under the Admin Panel > Settings > Version.
Permissions: Double-check that file and folder permissions are properly configured, especially for the attachments, include, and upload directories, to prevent unauthorized access or data loss.
Implementing these security practices ensures the long-term reliability and safety of your osTicket system.

</p>
<br />


</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />


