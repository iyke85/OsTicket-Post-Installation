<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
Following the successful installation and configuration of osTicket on a Windows Server, the next phase involved post-installation setup. This step was crucial in tailoring osTicket to meet organizational needs by configuring roles, departments, teams, user settings, agents, users, service level agreements (SLAs), and help topics. Below are the detailed steps of the post-installation configuration process.

<br />
<h2>Environments and Technologies Used</h2>
- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Define Access Levels:
Establish distinct roles with specific permissions to manage and control agent access.
- Organize Support Structure:
Create departments and teams to streamline ticket assignment and resolution processes.
- User Accessibility:
Configure settings to allow users to create tickets and interact with the support system efficiently.
- Agent and User Management:
Add and configure agents and users to ensure proper operation and interaction within the system.
- Service Level Agreements (SLAs):
Define response and resolution timeframes to maintain service standards and meet user expectations.
- Categorize Support Requests:
Create help topics to categorize common issues, making it easier for users to submit tickets and for agents to manage them.

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  1. Configure Roles:
Objective: Define different levels of access and permissions for agents.

  Process:
Navigated to Admin Panel -> Agents -> Roles.
Created a new role named Supreme Admin.

  2. Configure Departments:
Objective: Organize agents into departments for better management.

Process:
Navigated to Admin Panel -> Agents -> Departments.
Created a department named System Administrators.

3. Configure Teams:
Objective: Group agents into teams to handle different support levels.

Process:
Navigated to Admin Panel -> Agents -> Teams.
Created two teams:
Level I Support
Level II Support

4. Allow Anyone to Create Tickets:
Objective: Set ticket creation permissions for users.

Process:
Navigated to Admin Panel -> Settings -> User Settings.
Set Registration Required to "Require registration and login to create tickets."
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

5. Configure Agents (Workers):
Objective: Add agents who will manage and respond to tickets.

Process:
Navigated to Admin Panel -> Agents -> Add New.
Added two agents:
Jane
John

6. Configure Users (Customers):
Objective: Add users who will be submitting tickets.

Process:
Navigated to Agent Panel -> Users -> Add New.
Added two users:
Karen
Ken

7. Configure SLAs (Service Level Agreements):
Objective: Define response and resolution times for different types of tickets.

Process:
Navigated to Admin Panel -> Manage -> SLA.
Created three SLA plans:
Sev-A: 1 hour, 24/7
Sev-B: 4 hours, 24/7
Sev-C: 8 hours, business hours

8. Configure Help Topics:
Objective: Categorize common issues to streamline ticket submission.

Process:
Navigated to Admin Panel -> Manage -> Help Topics.
Created four help topics:
Business Critical Outage
Personal Computer Issues
Equipment Request
Password Reset

</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
                                               Summary

  This project highlights the comprehensive setup of osTicket, extending beyond basic installation to a fully configured support ticket system tailored to organizational needs. By setting up roles, departments, teams, user settings, agents, users, SLAs, and help topics, I ensured that the system is ready to manage and resolve support requests efficiently. This experience underscores my expertise in system administration, configuration management, and user support within a web-based application environment.
</p>
<br />
