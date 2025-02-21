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

- Configure Roles, Departments, and Teams
- Configure Agents and Users
- Configure SLA and Help Topics

<h2>Configuration Steps</h2>

![image](https://github.com/user-attachments/assets/1409cea8-a8cf-469c-a40b-95ebcc4747f4)

![image](https://github.com/user-attachments/assets/5f835e50-21a2-4a94-9992-d55b73d2d004)

![image](https://github.com/user-attachments/assets/13f6058e-f140-41df-ac7f-1c3cdb31145b)

<p>
We're first going to create some roles, departments, and teams. After we log into osTicket as our admin user, we'll go to admin panel, agents, and from there we can create what we need. We're going to create a supreme admin role that has all permissions, a SysAdmins department, and an online banking team for the purpose of pulling together people from different departments to deal with online banking. We're also going to allow anyone, including unregistered users, to create tickets. Just go to admin panel, settings, users, and uncheck the registration required box.
</p>
<br />

![image](https://github.com/user-attachments/assets/76fe5318-95f3-488b-8065-bcfe1bcbacbd)

![image](https://github.com/user-attachments/assets/390083e1-c5f8-4bbf-afef-dcc7b12bd658)

<p>
We're now going to create some agents and users. To create the agents, we go to admin panel, agents, and add new. We'll create Jane and John, using whatever emails you want, and whatever usernames and passwords as long as you can remember them. Jane will be in the SysAdmins department and Online Banking team and John will be in the Support department. To create some users, we will go to agent panel, users, and add new. We'll create Karen and Ken using whatever emails you want.
</p>
<br />

![image](https://github.com/user-attachments/assets/544e0d43-7b67-4c10-94e0-48da59274e0e)

![image](https://github.com/user-attachments/assets/eeb09b5e-43cc-4628-86d5-1dc0b92c02f5)

<p>
We're now going to create some SLAs. This basically helps us categorize tickets by their urgency. To do this, we go to admin panel, manage, and SLA. We'll create Sev-A, with a grace period of 1 hour on a 24/7 schedule, Sev-B, with a grace period of 4 hours on a 24/7 schedule, and Sev-C, with a grace period of 8 hours on a business hours schedule. We'll also create some help topics for users to categorize what kind of issue they are having. We'll go to admin panel, manage, and help topics. We'll create Business Critical Outage, Personal Computer Issues, Equipment Request, Password Reset, and Other.
</p>
<br />
