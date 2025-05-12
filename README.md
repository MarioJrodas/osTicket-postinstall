<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This procedure outlines how to configure osTicket and go over a few examples we can see in the workforce.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>osTicket Admin Panel Configuration Lab</h2>

We have installed osTicket and have access to the admin controls, let's set it up

If by chance you don't have osTicket installed, here is my link to install [osTicket installation lab](https://github.com/MarioJrodas/osticket-prereqs).

1. Log in to your admin account, click on the Admin Panel. You will notice other options appear.

2. Create roles that give different access levels for different groups. Groups help give acces to the agents in each group.

Create a Role:

Go to Admin Panel / Manage / Roles.

Create a new role called System Admins and give them all permissions.

Create a Group:

Go to Admin Panel / Manage / Groups.

Create a group called SYS Admin and assign the System Admins role to this group.

3. Create a Department for system admins.

Go to Admin Panel / Manage / Departments.

Create a new department called SYS Admins.

4. Create a Team
Teams allow you to pull agents from different departments into certain teams.

Go to Admin Panel / Manage / Teams.

Create a team called Warriors.

5. Adjust Ticket Registration Settings
 We want everyone to be able to register tickets.

Go to Admin Panel / Settings / Users.

Make sure the box labeled (Allow users to register tickets) is unchecked.

6. Create Agents
Now we will create a few agents (workers) to assign roles and teams.

Go to Admin Panel / Manage / Agents.

Click on Agents and add a new agent.

Agent 1: Stephen Curry

Role: Superior Admin (full access)

Team: Warriors

Agent 2: Kevin Durant

Role: Support (view access only)

Team: Warriors

Have a record of the email addresses for these agents, so they we can log into them.

7. Create a User
Let's create a user for ticket submission.

Go to the top-right corner and click on Agent Panel.

Navigate to Users and click Add New User.

Create a user with the name Lebron James 

8. Set up SLA (Service Level Agreements)
SLAs are used to notify agents how quickly a ticket should be handled.

Go to Admin Panel / Manage / SLA.

Create the following 3 SLAs:

SEV-A: Critical – HIGH PRIOTITY!!!!

SEV-B: Medium priority

SEV-C: Low priority

9. Create Help Topics
Help Topics guide users when they create tickets, taking them toward the correct category.

Go to Admin Panel / Manage / Help Topics.

Create the following Help Topics:

Personal Computer - log in issue

Equipment Request - Power cables





