<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post Installation Configuration</h1>
Tutorial for Configuration of ticket system operations.<br />
<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Documentation</h2>

- Roles: https://docs.osticket.com/en/latest/Admin/Agents/Roles.html
- Departments: https://docs.osticket.com/en/latest/Admin/Agents/Departments.html
- Teams: https://docs.osticket.com/en/latest/Admin/Agents/Teams.html
- Agents: https://docs.osticket.com/en/latest/Admin/Agents/Agents.html
- Users: https://docs.osticket.com/en/latest/Agent/Users/User%20Directory.html
- SLA: https://docs.osticket.com/en/latest/Admin/Manage/SLA%20Plans.html
- Help Topics: https://docs.osticket.com/en/latest/Admin/Manage/Help%20Topic.html

<h2>List of Prerequisites</h2>

- Microsoft Azure Active Subscription (Creation of Reasearch Group, VMs, Virtual Networks, Subnets)
- Enable Internet Information Services(IIS)
- PHP Manager
- Rewrite Manager
- C++ Redistributbal
- MySQL Server
- Install osTicket
- Assigning Permissions

<h2>Configuration Steps: 1 - 12</h2>

![image](https://github.com/jameswsm/post-install-config/assets/170709350/1d64c191-53c9-4c52-9eb8-7c0ea8c15a2e)
<p>
Step 1: Open a browser in the VM and enter http://localhost/osTicket/scp/login.php in the bar. Login with credentials we created. (ex: admin username: james)
</p>
<br />

![image](https://github.com/jameswsm/post-install-config/assets/170709350/f3199502-0c17-47da-b472-2e072e3b186b)
<p>
Step 2: Configure Roles. Admin Panel -> Agents -> Roles
</p>
<br />

![image](https://github.com/jameswsm/post-install-config/assets/170709350/41e39300-7161-4115-9c3e-a4fa9d998451)
![image](https://github.com/jameswsm/post-install-config/assets/170709350/24ff5995-367f-4a9a-84e4-457acf31807a)
<p>
Step 3: Admin Panel -> Add New Role -> Enter name (ex: Chief Admin) -> Permissions -> Allow All
</p>
<br />

![image](https://github.com/jameswsm/post-install-config/assets/170709350/6c34288c-2835-4b5e-b97b-4832fbf5db1d)
![image](https://github.com/jameswsm/post-install-config/assets/170709350/6eba1890-6d05-44e0-98a3-458b6a6797a1)
<p>
Step 4: Tasks -> Admin Panel -> Allow all -> Knowledgebase -> Check in Premade -> Click "Add Role"
</p>
<br />

![image](https://github.com/jameswsm/post-install-config/assets/170709350/88e06a2d-9be2-4d9f-8409-f4b7c3d8cbb2)
<p>
Step 5: Configure Deparments -> Add New Department -> set parameters. ex: Top Level Department(ex: System Administrators) -> Creat Dept
</p>
<br />

![image](https://github.com/jameswsm/post-install-config/assets/170709350/c1626932-8652-4d8b-9b1d-db54d74a9cec)
<p>
Step 6: Configure Teams -> Admin Panel -> Add New Team -> Fill out parameters (ex: Name: Level II Support, Members: James Milton) -> Create Team
</p>
<br />

![image](https://github.com/jameswsm/post-install-config/assets/170709350/5ce56878-ecc5-4b63-bc6d-756eebbd342d)
<p>
Step 6: Allow anyone to create a ticket. Admin Panel -> Settings -> Users -> Uncheck "Registration Required" -> Save Changes
</p>
<br />

![image](https://github.com/jameswsm/post-install-config/assets/170709350/d682d3cf-1894-4db5-8afb-33bc10341f22)
<p>
Step 7: Configure Agents -> Admin Panel -> Agents -> -> Fill out parameters -> ex:Add New Agent(ex: John Doe) -> Create
</p>
<br />

![image](https://github.com/jameswsm/post-install-config/assets/170709350/e124d7a5-bb4d-4259-a72a-6630630f0c4d)
<p>
Step 8: Configure Users -> Agent Panel -> Users -> Add User -> Fill out parameters -> ex:(Thomas Engine)
</p>
<br />

![image](https://github.com/jameswsm/post-install-config/assets/170709350/fb447a28-1ad4-4c9b-8b6e-0b638ad1ffd1)
<p>
Step 8: Configure SLA -> Admin Panel -> Manage -> SLA -> Add New SLA Plan -> Fill out Parameters -> ex:(SEV-A, SEV-B, SEV-C) -> Add Plan
</p>
<br />

![image](https://github.com/jameswsm/post-install-config/assets/170709350/d80d011c-10ff-4692-a87d-93d3f26044e6)
<p>
Step 8: Configure Help Topics -> Admin Panel -> Manage -> Help Topics -> Add New Help Topic -> Fill out Parameters -> ex:(Topic: Business Critical Outage) -> Add Topic
</p>
<br />


