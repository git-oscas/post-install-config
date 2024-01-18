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
- Configure Departments
- Configure Teams
- Allow anyone to create tickets
- Configure Agents (workers)
- Configure Users (customers)
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

![image](https://github.com/git-oscas/post-install-config/assets/156957308/6a5e1287-d01a-4c62-879f-58c8baea80b1)

Created the role "Supreme Admin" and assigned all permissions necessary for an admin role

![image](https://github.com/git-oscas/post-install-config/assets/156957308/05fee627-8ad6-423f-a852-62844c3a6586)

Created the department "System Administrators" and configured dept. information

![image](https://github.com/git-oscas/post-install-config/assets/156957308/53b84aa8-9877-43ad-b152-e7a32c462295)

Created the team "Level II Support" and added myself as a member

![image](https://github.com/git-oscas/post-install-config/assets/156957308/f44e7760-782c-4f17-bb19-77a169b6e5b2)

Ensured anyone is able to create tickets within osTicket settings

![image](https://github.com/git-oscas/post-install-config/assets/156957308/48e6b770-345e-4999-b036-2fbd39ee9f3b)

Added agents "Jane Doe" & "John Doe" and configured: departments they have access to, permissions they have, and the team(s) they are assigned to

![image](https://github.com/git-oscas/post-install-config/assets/156957308/d1eb0f02-71a1-44f1-b753-b44fdf3519e0)

Added users "Karen Karen" & "Ken Ken" to manually simulate tickets

![image](https://github.com/git-oscas/post-install-config/assets/156957308/6334861b-b4b4-484a-a170-32c76a6bec23)

Configured an SLA with appropriate response times to each serverity

![image](https://github.com/git-oscas/post-install-config/assets/156957308/fcbbf181-ad51-4854-ba20-9142ffb2832c)

Added new "Help Topics" (as highlighted) and configured them to their appropriate priority & dept.


