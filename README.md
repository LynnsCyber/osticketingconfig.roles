<p align="center">
<img width="600" alt="image" src="https://github.com/user-attachments/assets/9922287d-17fd-4a61-bc48-c43b4b61bce5" />

</p>

<h1>Configure Roles in osTicket: Admin Panel</h1>
This tutorial demonstrates the configuration of roles in Osticket. These agents are given certain permissions/access due to the role they are assigned.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop
- Internet Information Services (IIS)
- osTicket v1.15.8

<h2>Operating Systems Used </h2>

- Windows 10(21H2)


<h1>Configuration Stages:</h1>

<h2>Log in to osTicket Admin Panel</h2>
<img src="https://i.imgur.com/sCcsTWe.png" height="80%" width="80%" alt="Online Image">


<ul>
  <li>Log in to osTicket Admin Panel</li>
  <li>Use an admin account to sign in.</li>
  <li>Navigate to Agent Panel Click on Admin Panel (top-right). Go to Agents > Roles.</li>
   ----------------------------------------------------------------------------------------
  </ul>

 <h2>Navigate to Agent Panel/Create New Role</h2>
<img src="https://i.imgur.com/tobk64t.png" height="80%" width="80%" alt="Online Image">
  <img src="https://i.imgur.com/s1Ej63B.png" height="80%" width="80%" alt="Online Image">
   <img width="600" alt="image" src="https://github.com/user-attachments/assets/8d39371f-dc6f-4670-9cba-5dcad5bd9af0" />
  

<ul>
  <li>Click on Agents Tab Below to Navigate to Roles tab.</li>
  <li>Before you create new role, the created roles I have circled are the different access you can give to agents</li>
  <li>Click Add New Role</li>
------------------------------------------------------------------------------------------
 </ul>

 <h2> Set Permissions</h2>
 <img width="600" alt="image" src="https://github.com/user-attachments/assets/51094201-8252-4c07-87e5-cc446c818e97" />
  <img width="600" alt="image" src="https://github.com/user-attachments/assets/7463d428-716b-4243-904d-ea636879b905" />
 <ul>
  <li>Enter a name for the role.</li>
  <li>Under Permissions, configure</li>
  <li>Tickets (view, edit, close, delete).</li>
  <li>Tasks (assign, complete).</li>
  <li>Knowledgebase (manage FAQs, categories).</li>
  <li>Departments (access control).</li>
   ----------------------------------------------------------------------------------------
  </ul>

<h2>Assign Role to Agents</h2>
<img width="600" alt="image" src="https://github.com/user-attachments/assets/66c6eec9-f054-49f8-bf40-ec25327db2bd" />
<img width="600" alt="image" src="https://github.com/user-attachments/assets/a93e7842-ed4b-4646-a5ba-a1dbf582f67e" />
<ul>
  <li>Go to Agents > Agents.</li>
  <li>Select an agent, click Access.</li>
  <li>Assign the newly created role to the agent.</li>
   ----------------------------------------------------------------------------------------
  </ul>
  
<h1>Save and Test👩‍💻</h1>
<h1>Test by logging in as an agent to ensure proper access.🤝📈📊</h1>






