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

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

Step 1: Log in to the Admin Panel

1. Open a web browser and navigate to the osTicket URL (e.g., `http://localhost/osticket`).
2. Log in using the administrator account credentials you provided during the installation.

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

Step 2: Configure Roles

1. In the sidebar, click on "Agents" and then select "Roles."
2. Create a role named "Supreme Admin" or as desired.

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

Step 3: Configure Departments

1. In the sidebar, click on "Agents" and then select "Departments."
2. Create departments such as "System Administrators" based on your organizational structure.

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

Step 4: Configure Teams

1. In the sidebar, click on "Agents" and then select "Teams."
2. Create teams such as "Level I Support" and "Level II Support."

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

Step 5: Allow anyone to create tickets

1. In the sidebar, click on "Settings" and then select "User Settings."
2. Set the "Registration Required" option to "Require registration and login to create tickets."

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

Step 6: Configure Agents (workers)

1. In the sidebar, click on "Agents" and then select "Add New."
2. Add agents such as "Jane" and "John" and specify their details and roles.

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

Step 7: Configure Users (customers)

1. In the agent panel, click on "Users" and then select "Add New."
2. Add users such as "Karen" and "Ken" and specify their details.

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

Step 8: Configure SLA

1. In the admin panel, click on "Manage" and then select "SLA."
2. Create SLAs such as "Sev-A" (1 hour, 24/7), "Sev-B" (4 hours, 24/7), and "Sev-C" (8 hours, business hours).

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

Step 9: Configure Help Topics

1. In the admin panel, click on "Manage" and then select "Help Topics."
2. Create help topics such as "Business Critical Outage," "Personal Computer Issues," "Equipment Request," and "Password Reset."

Remember to replace "localhost" with the appropriate hostname or IP address if accessing the osTicket installation from a different machine.

<h2>Configuration Steps</h2>
