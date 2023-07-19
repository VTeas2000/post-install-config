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

- Allow anyone to create tickets
- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents (workers)
- Configure Users (customers)
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
Log in at <a href="http://localhost/osTicket/scp/login.php">osTicket :: Agent Login</a> using your admin user credentials.
<img src="https://github.com/VTeas2000/post-install-config/assets/60052902/f854ebdc-1a0e-4ec6-9b60-880bad77fc2d" height="80%" width="80%" alt="Agent Login"/>
<br>Once logged in, click <b>Admin Panel</b> at the top right of the home screen.
</p>

<h3>Allow anyone to create tickets</h3>
<p>
On the Settings tab of the Admin Panel, select <b>Users</b>.
<br>For <b>Registration Required</b> under the Authentication Settings, ensure that "Require registration and login to create tickets" is not selected.
<img src="https://github.com/VTeas2000/post-install-config/assets/60052902/adfd0433-fc91-40d9-8de6-04e28d05e2d4" height="80%" width="80%" alt="Ticket Configuration"/>
</p>

<h3>Configure Roles</h3>
<p>
On the Agents tab of the Admin Panel, select <b>Roles</b>.
<br>Click <b>Add New Role</b>.
<br>I created a role named "Supreme Admin".
<img src="https://github.com/VTeas2000/post-install-config/assets/60052902/db5a05af-07f1-4dcc-ba71-55d9a001da05" height="80%" width="80%" alt="Role Name"/>
<br>Assign permissions for Tickets/Tasks/Knowledgebase. Then click "Add Role".
<img src="https://github.com/VTeas2000/post-install-config/assets/60052902/a138d8be-ac0f-403a-810b-a3b4f67bf97a" width="80%" alt="Role Permissions"/>
</p>

<h3>Configure Departments</h3>
<p>
On the Agents tab of the Admin Panel, select <b>Departments</b>.
<br>Click <b>Add New Department</b>.
<br>I created a department named "System Administrators".
</p>

<h3>Configure Teams</h3>
<p>
On the Agents tab of the Admin Panel, select <b>Teams</b>.
<br>Click <b>Add New Team</b>.
<br>I created a team named "Level II Support".
</p>

<h3>Configure Agents (workers)</h3>
<p>
On the Agents tab of the Admin Panel, select <b>Agents</b>.
<br>Click <b>Add New Agent</b>.
<br>I created an agent named "Jane Doe". Use any values for their credentials, but keep them in mind.
<img src="https://github.com/VTeas2000/post-install-config/assets/60052902/693ceea7-045a-4133-8dc3-5d025538e1ec" height="80%" width="80%" alt="Agent Name"/>
<br>Set the agent's password.
<img src="https://github.com/VTeas2000/post-install-config/assets/60052902/71a1889d-d9a3-452a-b279-4ea138987441" alt="Agent Password"/>
<br>Set the agent's department and role.
<img src="https://github.com/VTeas2000/post-install-config/assets/60052902/57afd8d2-2ee7-445d-8a34-280c724f37fb" alt="Agent Access"/>
<br>Set the agent's team. Then create the agent.
<img src="https://github.com/VTeas2000/post-install-config/assets/60052902/dadfba05-fa07-4c5c-b11f-9033769319d7" alt="Agent Team"/>
</p>
