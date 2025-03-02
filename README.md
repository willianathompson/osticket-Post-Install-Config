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
<h4>Delete the setup Folder</h4>

![image](https://github.com/user-attachments/assets/5bcc841a-6a2b-4e08-9ca2-37e884751962)

<p>
</p>
<p>
  
The setup folder is deleted from the osTicket installation directory (C:\inetpub\wwwroot\osticket) to prevent unauthorized access to the installation files and improve system security.
</p>
<p>


</p>
<br />
<h4>Configure Email Settings for Ticketing</h4>
  
![image](https://github.com/user-attachments/assets/80b01596-eabc-47be-98ae-2e88c25e7a7c)

</p>
<p>
The email settings for ticketing are set up to allow osTicket to send and receive email notifications. All help desk tickets come through a shared inbox, where tickets can be claimed or assigned to another member of the support team or system administrator. SMTP (Simple Mail Transfer Protocol) is configured under Admin Panel > Settings > Email for outgoing emails, and auto-response settings are enabled so that customers receive confirmation emails when a ticket is created, ensuring smooth communication between the support team and customers.
</p>
<p>


</p>
<br />
<h4>Set Up Ticketing Categories and Departments</h4>
  
![image](https://github.com/user-attachments/assets/8121394a-917b-4cbf-8a99-5f79ca49d6d5)

</p>
<p>
New departments like Sales, IT Support, and Billing can be created under Admin Panel > Manage > Departments. This helps the helpdesk system organize and send tickets to the right teams. A main inbox is set up for the support team to see all incoming tickets. Also, permissions are set so that only the right team members can see or manage tickets for their department. This setup makes communication easier and improves the support process.
</p>
<p>
  
![image](https://github.com/user-attachments/assets/cd7f3612-02bf-48cd-98a7-560466cd6352)

</p>
<p>
Ticket categories with custom fields are added under Admin Panel > Manage > Help Topics. These categories help classify tickets based on their nature (e.g., technical support, billing inquiry, etc.), ensuring they are routed to the appropriate team. Custom fields are configured to collect specific information from customers when they create a ticket, providing the support team with more context and enabling faster issue resolution. This system ensures that all tickets are properly sorted and efficiently handled.
</p>
<p>

![image](https://github.com/user-attachments/assets/1fa61ce9-5eef-45d1-8597-52e9e03dc70d)

</p>
<p>
New SLAs (Service Level Agreements) are set up in Admin Panel > Manage > SLA for each ticket category. These SLAs define the response and resolution times for different types of tickets, helping the support team meet expectations and maintain service quality. SLAs are aligned with business priorities, so critical issues are addressed promptly, while less urgent tickets are given the appropriate attention. By setting up SLAs, you can track performance and ensure that the support team meets agreed-upon standards, maintaining a high level of customer satisfaction.
</p>
<p>


</p>
<br />
<h4>Create Agent and Admin User Accounts</h4>

![image](https://github.com/user-attachments/assets/12a7394a-ffe1-4214-be76-c40cadf29be0)
![image](https://github.com/user-attachments/assets/b2e2894f-d1bf-4b69-be99-a93e593fd981)

</p>
<p>
Agent and admin user accounts are created to help manage the system. New agent accounts are set up under Admin Panel > Manage > Staff, with the appropriate permissions assigned to access specific departments, manage tickets, and view reports. 
</p>
<p>

![image](https://github.com/user-attachments/assets/aeb91b7d-3154-4dae-9ec8-51991112c3ff)

</p>
<p>
Different roles, such as Admin and Agent, are assigned to ensure each user has the right level of access, allowing agents to provide support and admins to configure and manage the system.
</p>
<p>


</p>
<br />
<h4>Set Up Security Measures (Backup and Updates)</h4>

![image](https://github.com/user-attachments/assets/4f359c74-dd9c-4ee4-b9be-fd299b646db7)

</p>
<p>
It’s important to periodically check for updates. osTicket automatically receives security updates, and the system is checked for new versions under Admin Panel > Settings > Version.
</p>
<p>

![image](https://github.com/user-attachments/assets/cb2db211-49e6-4ca7-a609-9bd8748dfda4)

</p>
<p>
File and folder permissions are set to prevent unauthorized access and data loss, particularly for critical folders like attachments, include, and upload. These settings ensure only authorized users can access sensitive files, keeping the osTicket system secure.
</p>
<p>

</p>
<br />



[osTicket: Ticket Lifecycle Examples](https://github.com/willianathompson/osticket-lifecycle)
