<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### 

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>


<h2>Configuration Steps</h2>

<p>

</p>
<p>
Configure Roles
Admin Panel -> Agents -> Roles
Supreme Admin

</p>
<br />


</p>
<p>
Configure Departments
Admin Panel -> Agents -> Departments
System Administrators


</p>
<br />


</p>
<p>
Configure Teams
Admin Panel -> Agents -> Teams
Level I Support
Level II Support


</p>
<br />


<p>
Allow anyone to create tickets
Admin Panel -> Settings -> User Settings
Registration Required: Require registration and login to create tickets 

</p>
<br />


<p>
Configure Agents (workers)
Admin Panel -> Agents -> Add New
i.Jane
ii.John

</p>
<br />


<p>
Configure Users (customers)
Agent Panel -> Users -> Add New
i.Karen
ii.Ken


</p>
<br />


</p>
<p>
Ken
Configure SLA
Admin Panel -> Manage -> SLA
Sev-A (1 hour, 24/7)
Sev-B (4 hours, 24/7)
Sev-C (8 hours, business hours)


</p>
<br />


</p>
<p>
Configure Help Topics
Admin Panel -> Manage -> Help Topics
Business Critical Outage
Personal Computer Issues
Equipment Request
Password Reset

</p>
<br />

