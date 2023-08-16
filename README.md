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
- Configure Roles
<br />
- Configure Departments
<br />
- Configure Teams
<br />
- Configure Agents (workers)
<br />
- Configure Users (customers)
<br />
- Configure SLA
<br />
- Configure Help Topics
<br />

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/7pBu8IQ.png" height="60%" width="60%" alt="osTicket Interface"/>
</p>
<p>
This is what the interface will look like. 
<br />
There will be an admin panel and an agent panel, below are the instructions to which panel you will need in each section. 
<br />
Each section will have a description to which areas of the main interface you will navigate to and edit in order to configure the desired portion.
</p>
<br />

<h2>Configure Roles</h2>
<p>
Admin Panel -> Agents -> Roles
<br />
Supreme Admin
</p>
<br />

<h2>Configure Departments</h2>
<p>
Admin Panel -> Agents -> Departments
<br />
System Administrators
</p>
<br />

<h2>Configure Teams</h2>
<p>
Admin Panel -> Agents -> Teams
<br />
i. Level I Support
<br />
ii. Level II Support
</p>
<br />

<h2>Allow anyone to create tickets</h2>
<p>
a. Admin Panel -> Settings -> User Settings
<br />
b. Registration Required: Require registration and login to create tickets 
</p>
<br />

<h2>Configure Agents (workers)</h2>
<p>
Admin Panel -> Agents -> Add New
<br />
(Examples below)
<br />
i. Jane
<br />
ii. John
</p>
<br />

<h2>Configure Users (customers)</h2>
<p>
Agent Panel -> Users -> Add New
<br />
(Examples below)
<br />
i. Karen
<br />
ii. Ken 
</p>
<br />

<h2>Configure SLA</h2>
<img src= "https://i.imgur.com/Cz0YJLk.png" height="50%" width="50%" alt="Configure SLA"/>
<p>
Admin Panel -> Manage -> SLA
<br />
i. Sev-A (1 hour, 24/7)
<br />
ii. Sev-B (4 hours, 24/7)
<br />
iii. Sev-C (8 hours, business hours)
</p>
<br />

<h2>Configure Help Topics</h2>
<img src= "https://i.imgur.com/weaguRT.png" height="50%" width="50%" alt="Configure Help Topics"/>
<p>
a. Admin Panel -> Manage -> Help Topics
<br />
(Examples of help topics)
<br />
i. Business Critical Outage
<br /> 
ii. Personal Computer Issues
<br />
iii. Equipment Request
<br />
iv. Password Reset
</p>
<br />
