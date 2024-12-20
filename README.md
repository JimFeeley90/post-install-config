# post-install-config

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

- Configure Roles (for grouping permissions)
- Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
- Configure Teams
- Configure Agents (workers)
- Configure Users (customers)
- Configure SLA
- Configure Help Topics (For when users create a ticket)


<h2>Configuration Steps</h2>

<p>
<img src=https://i.imgur.com/K7uGIqx.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src=https://i.imgur.com/tFtSX2r.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src=https://i.imgur.com/dLkj0CQ.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<h2>Define roles and permissions within osTicket: To define roles and permissions within osTicket, log in to the admin panel of your osTicket system. Navigate to the "Admin Panel" and select the "Manage" tab, then click on "Roles." Here, you can create new roles by clicking the "Add New Role" button. For each role, you can define specific permissions, such as access to certain tickets, ability to manage agents, and permission to configure settings. You can customize these permissions based on the role's responsibilities. After defining the roles, assign them to agents by going to the "Staff" section, editing an agent's profile, and selecting the appropriate role from the dropdown. This ensures that users have the appropriate level of access within osTicket.</h2>
</p>
<br />

<p>
<img src=https://i.imgur.com/tQD91E9.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src=https://i.imgur.com/i12sQm4.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src=https://i.imgur.com/2uJXyYF.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<h2>Setting up and managing departments in osTicket: To set up and manage departments in osTicket, log in to the admin panel and navigate to the "Admin Panel" > "Manage" > "Departments." Click on the "Add New Department" button to create a new department, giving it a name and optional description. You can also assign specific agents or teams to each department, ensuring that the right staff handle relevant tickets. After creating departments, you can manage them by editing, assigning additional agents, or setting up email forwarding to ensure that support requests are routed to the correct department. Departments help organize ticket management, making it easier to track and resolve issues by area of expertise.</h2>
</p>
<br />

<p>
<img src=https://i.imgur.com/asEGHIN.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src=https://i.imgur.com/3ucfYsT.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src= height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src=https://i.imgur.com/iVHPsBF.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>  
<p>
<h2>Setting up and managing teams in osTicket: To set up and manage teams in osTicket, log in to the admin panel and go to "Admin Panel" > "Manage" > "Teams." Click on the "Add New Team" button to create a new team, and give it a name and description. After creating a team, you can assign specific agents to it, ensuring that the right personnel are grouped together for specific tasks or support areas. Teams can be assigned to departments, allowing for better organization and ticket management. You can also edit teams later to add or remove agents, adjust their settings, or change their responsibilities, streamlining workflow and improving collaboration within osTicket.</h2>
</p>
<p>
<img src=https://i.imgur.com/5XpNAFA.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src=https://i.imgur.com/JEQ8VEa.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  <h2>Setting up and managing agents in osTicket: To set up and manage agents in osTicket, log in to the admin panel and navigate to "Admin Panel" > "Manage" > "Agents." Click on the "Add New Agent" button to create a new agent profile, filling in their name, email address, and role. You can assign agents to specific departments or teams, and set their permissions based on the responsibilities they will handle. Once added, you can edit an agent's profile to adjust their settings, such as their password, roles, and the departments they are associated with. Managing agents efficiently in osTicket ensures the right personnel are assigned to the appropriate tasks and support areas.</h2>
</p>
<p>
  <img src=https://i.imgur.com/FC4Ap1c.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src=https://i.imgur.com/jn2beDy.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src=https://i.imgur.com/XPB78kd.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src=https://i.imgur.com/dj7lRFI.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src=https://i.imgur.com/AAuWtn2.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p><p> <h2>Managing and configuring SLA's in osTicket: To manage and configure SLAs (Service Level Agreements) in osTicket, log in to the admin panel and go to "Admin Panel" > "Manage" > "SLA Plans." Click on the "Add New SLA" button to create a new SLA plan. Here, you can define key parameters such as response and resolution times based on ticket priorities (e.g., low, medium, high). You can also set up escalations for tickets that are nearing their deadlines. After creating an SLA plan, you can assign it to specific departments or ticket types. Configuring SLAs helps ensure timely responses and resolutions, improving customer satisfaction and ensuring that service standards are met consistently.</h2>
</p>
<p>
  <img src=https://i.imgur.com/N2GSBX8.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src=https://i.imgur.com/WhEkczM.png  height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src=https://i.imgur.com/cWcprEf.png  height="80%" width="80%" alt="Disk Sanitization Steps"/> 
  <img src=https://i.imgur.com/AyrMHwu.png  height="80%" width="80%" alt="Disk Sanitization Steps"/> 
  <h2>Managing and configuring help topics: To manage and configure help topics in osTicket, log in to the admin panel and navigate to "Admin Panel" > "Manage" > "Help Topics." Click on the "Add New Help Topic" button to create a new topic, where you can provide a title and description that guides users in selecting the appropriate issue category when submitting a ticket. You can customize help topics to match the common issues or requests your support team handles, improving ticket organization. After creating or editing help topics, they will appear as options for users when they create a new ticket, helping streamline the ticket submission process.</h2>
</p>
