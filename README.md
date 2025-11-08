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
Configured </p>
- roles, teams, departments, users, SLA (service-level agreements), and ticket categorizations

<h2>Configuration Steps</h2>

<p>
<img width="600" alt="image" src="https://github.com/user-attachments/assets/8af2ceef-8588-4c21-a3c5-439f04e53248" />

</p>
<p>
1. I configured Roles (for grouping permissions) → Navigated to Admin Panel → Agents → Roles → Create role: Supreme Admin.
<p> This is mainly for assigning group permissions.
</p>
<br />

<p>
<img width="600" alt="image" src="https://github.com/user-attachments/assets/c93a52a8-1334-4773-8d29-1f76ec58fd07" />

</p>
<p>
2. I configured Departments (Ticket Visibility) → Navigated to Admin Panel → Agents → Departments → Create department: SysAdmins.
  <p> This setup allows tickets to be routed efficiently to the right personnel.
</p>
<br />

<p>
<img width="600" alt="image" src="https://github.com/user-attachments/assets/482cf39b-bc08-4aef-bf46-01edb4758c13" />

</p>
<p>
3. I configured Teams → Navigated to Admin Panel → Agents → Teams → Created team: Online Banking → Pulled agents from different departments as needed.
<p> This is to ensure tickets are accessible only to the appropriate team.


</p>
<br />

<p>
<img width="600" alt="image" src="https://github.com/user-attachments/assets/d335d9d0-53f8-42ae-8a8a-935176b7c019" />

</p>
<p>
4. I configured User Registration Settings (Ticket Access Control) → Navigated to Admin Panel → Settings → User Settings → Uncheck "Unregistered users can create tickets" → Require registration/login to create tickets. <p> This is so that anyone visiting the end user URL can create a ticket.
</p>
<br />

<p>
<img width="750" alt="image" src="https://github.com/user-attachments/assets/c7325150-cf8c-43d8-b227-bc518dd008b3" />

</p>
<p>
5. I configured Agents (workers) → Navigated to Admin Panel → Agents → Add New → Example: Jane (Dept: SysAdmins), John (Dept: Support).
<p> This involved assigning the correct permissions and roles so that each team could efficiently handle tickets relevant to them.
  
</p>
<br />

<p>
<img width="600" alt="image" src="https://github.com/user-attachments/assets/eaac9f09-e4d8-4735-a1aa-8c96b45051bc" />

</p>
<p>
6. I configured Users (customers) → Navigated to Agent Panel → Users → Add New → Example: Damian and Karen.
  <p> This allows us to create new end-users to allow them to submit tickets.
</p>
<br />

<p>
<img width="600" alt="image" src="https://github.com/user-attachments/assets/cfeba0da-e5bd-4a51-97af-46af13dc36ce" />

</p>
<p>
7. I configured SLA → Navigated to Admin Panel → Manage → SLA → Created policies: Sev-A (1 hr, 24/7), Sev-B (4 hrs, 24/7), Sev-C (8 hrs, Business Hours).
<p> This is to enforce ticket response from our agents to improve service accountability.
</p>
<br />

<p>
<img width="600" alt="image" src="https://github.com/user-attachments/assets/065cdd85-cfd7-4908-97a1-70ac60223a61" />

</p>
<p>
7. Finally, I configured Help Topics (For when users create a ticket) → Navigated to Admin Panel → Manage → Help Topics → Add: Business Critical Outage, Personal Computer Issues, Equipment Request, Password Reset, Other.
<p> This seperates tickets into topics such as Business Critical Outage, Personal Computer Issues, Equipment Request, Password Reset, and other to help agent categorize tickets and to improve the overall experience for end-users.
</p>
<br />

