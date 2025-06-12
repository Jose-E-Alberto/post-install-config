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

- Windows 10 Pro</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Login to the osTicket Admin Panel
- Configure Roles
- Configure Departments
- Configure Teams
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>

![image](https://github.com/user-attachments/assets/a03286c2-b4ba-42d5-92a7-da120cb67043)

</p>
<p>
Login to the osTicket Admin Panel.
</p>
<br />


<p>

![Screenshot 2025-06-12 175352](https://github.com/user-attachments/assets/2be18b34-2316-48f4-ab97-139f7ef6e804)

</p>
<p>
  
To create a new role:
- Make sure you are in the Admin panel (check the top-right of the screen to see which panel you are in)
- If it says "Agent," you are in the Admin panel
- Select the Agent tab > Roles > Add New Role
- Name: Supreme Admin (or any name you'd like)
- Select Permissions tab and check every box under the "Tickets," "Tasks," and "Knowledgebase" sections
- Select Add Role.
  
</p>
<br />

<p>
  
![Screenshot 2025-06-12 174624](https://github.com/user-attachments/assets/5ded1e6f-11cf-46b8-a4d6-81a323ad4f53)

</p>
<p>
  
To create a new department
- From the Admin panel
- Select the Agent tab > Departments > Add New Department
- Name: SysAdmin
- Select Create Department

</p>
<br />

<p>
  
![Screenshot 2025-06-12 174911](https://github.com/user-attachments/assets/29f06dbc-42bf-436f-b691-c3dd6b83ee93)

</p>
<p>
  
To create a new Team
- Select the Agent tab > Teams > Add New Team
- Name: Online Banking
- Go to the Members tab and you can select yourself in "Select Agent" dropdown menu
- Select Create Team
</p>
<br />

<p>
  
![Screenshot 2025-06-12 175059](https://github.com/user-attachments/assets/2da3c0ba-f651-4589-aa55-8b5aa0e4509a)

</p>
<p>
  
To allow anyone to create tickets
- From the Admin Panel. Seclect "Settings"
- Select "User Settings"
- UNCHECK: "registration required"
  - Make sure this box is NOT checked
    - Registration Required: Require registration and login to create tickets
</p>

<br />
  
![image](https://github.com/user-attachments/assets/2da98bb8-828d-4e4b-92e4-1407ed426162)

</p>
<p>

To add a new agent
- From the Admin Panel, Select the Agent tab > Add New Agents
- Name: Jane Doe (any name)
- Email : jane.doe(@)gmail.com (any email)
- Username: jane (any username)
- Click Set Password and uncheck the box that says "Send the Agent a Password Reset Email"
- Create a new password. Make sure to keep track on all passwords
- Uncheck the box that says "Require Password Change at Next Login"
- Select set

</p>
<br />

<p>
  
![image](https://github.com/user-attachments/assets/1f9205f7-eab4-4095-a5fe-5f89a5297f01)

</p>
<p>
  
- Select the Access tab
- Under Primary Department:
- Select the Department dropdown menu > SysAdmin
- Select the Role dropdown menu > Supreme Admin

To create another agent (John Doe)
- Follow the same steps as above, except make some changes to the Primary Department
- Select the Department dropdown menu > Support
- Select the Role dropdown menu > View Only

</p>
<br />

<p>
  
![image](https://github.com/user-attachments/assets/d913c24b-5114-41ac-9203-e70592a4cb1e)

</p>
<p>
To add users  
- From the Agen panel -> Select the Users tab -> Add User
- Email Address: any email you'd like
- Full Name: Karen (any name)
- Select Add User
  
</p>
<br />


<p>
  
![image](https://github.com/user-attachments/assets/85a775eb-6da8-41d6-96b8-c275cf857bd1)

</p>
<p>
  
To configure SLAs
- From Admin Panle -> Manage -> SLA -> Add New

Sev A
- Name: SEV-A
- Grace Period: 1 hour
- Schedule dropdown menu: 24/7
- Select Add Plan

Sev B
- Name: SEV-B
- Grace Period: 4
- Schedule dropdown menu: 24/7
- Select Add Plan

Sev C
- Name: SEV-C 
- Grace Period: 8
- Schedule dropdown menu: Monday - Friday 8AM - 5PM with U.S. Holidays
- Select Add Plan

</p>
<br />

<p>
  
![image](https://github.com/user-attachments/assets/8b5d08bd-8eb1-4a6e-a62b-a2a87acf34cc)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
