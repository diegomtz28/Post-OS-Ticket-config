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

- Ensure the OS-Ticket environment is secured by implementing HTTPS, access control, and firewall settings. 
- Tailor OS-Ticket's settings, workflows, and user roles to fit your organization's specific needs. 
- Ensure optimal database performance and implement regular backup procedures to protect data.
- Confirm the functionality and reliability of the Os-Ticket system through comprehensive testing and log review. 


<h2>Configuration Steps</h2>

__Step 1:Secure the OS-Ticket Environment__
- Install SSL Certificate: Set up the HTTPS to ensure secure data transmission.
- Configure IIS Security Settings: Limit access to sensitive directories and enable required security protocols.
- Implement FIrewall Rules: Restrict incoming traffic to only necessary ports. 
**Screenshot of IIS manager where you configure the ssl certificates for HTTPS or the bindings page in IIS showing the HTTPS setup.**

<img src="(https://github.com/diegomtz28/Post-OS-Ticket-config/blob/main/SSL%20Certificate.png)"/>


__Step 2: Customize OS-Ticket Configuration__
- Configure Email Notifications: Set up SMTP to enable email alerts for ticket updates and system notifications.
- Adjust ticketing workflows and Fields: Customize the ticketing system to reflect the business, including priorities, SLAs, and custom fields.
- Define User Roles and Permissions: create roles for staff and define access levels to ensure proper functionality and security.

**Take a screenshot of the Os-Ticket admin dashboard where you configured email notifications, custom ticket fields, or user roles.**
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


__Step 3: Optimize Database and Set Up Backup Precudures__
- Schedule Automated Database Backups: Set up regular backups to safeguard against data loss. 
- Optimize Database Performance: Run optimization queries to maintain fast performance.
- Monitor Database Logs: Regularly check for slow queries or potential issues that could impact performance.

**Include a Screenshot of the MYSQL Workbench or OS-Ticket database settings page showing backup configurations or database optimization options.**


<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

__Step 4: Test and Validate the OS-Ticket System__
- Test Ticket Lifecycle: Create and resolve test tickets to verify the system works as expected.
- Verify Email Notifications: Ensure ticket-related emails are sent and received correctly.
- Review System Logs for Errors: Check IIS and OS-Ticket logs to identify and address potential issues. 

**Provide a screenshot of the OS-Ticket creation poage and a test ticket confirmation, or a log page showing system health**
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
