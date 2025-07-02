<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
Welcome the last part of the osTicket tutorial. Here, we will show the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.

<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<h3>1. Intake</h3>

  - As an end-user, create the following ticket : "entire mobile/online banking system is down"
  - To create a ticket, go to http://localhost/osTicket/ and click Create a New Ticket
    (*You can use any of the two buttons*)

![image](https://github.com/user-attachments/assets/3a75994d-2171-4865-8c4e-c3f5eaea145c)

  - On contact information, you can use a user from the previous lab that we created.
  - Help topic : Report a problem
  - Issue Summary : entire mobile/online banking system is down
  - Click Create Ticket

![image](https://github.com/user-attachments/assets/c0a90283-ea85-4c57-a723-f66c6d8ecb1d)

![image](https://github.com/user-attachments/assets/04815619-0a93-4a53-ad50-3247a7d65491)


<br />

<h3>2. Assignment and Communication</h3>

  - As a Help Desk Agent (John), observe the ticket’s properties

    - Priority
  	- Department
  	- SLA
  	- Assigned To

  -  Go to http://localhost/osTicket/scp/login.php and log in as John (from the previous lab)

![image](https://github.com/user-attachments/assets/d22fcc7f-0dbf-42e1-8567-f492306276e2)


Set Properties to the ticket
Sev-A (1 hour, 24/7)
Online Banking Department

Attempt to observe the ticket again as “john”. Can you view or change?

Work the ticket to completion as jane

As an end-user, create the following ticket
accounting department needs adobe upgrade, broken

As a Help Desk Agent (john), observe the ticket’s properties
	Priority
	Department
	SLA
	Assigned To

Set Properties to the ticket
Sev-B (4 hours, 24/7)
Support

Work the ticket to completion as john

As an end-user, create the following ticket
CFO’s laptop will no longer turn on

As a Help Desk Agent (john), observe the ticket’s properties
	Priority
	Department
	SLA
	Assigned To

Set Properties to the ticket
Sev-B (4 hours, 24/7)
Support

Work the ticket to completion as john


Set Properties to all the tickets; do SEV-A (SysAdmins last), observe ticket becomes inaccessible
Switch to admin panel and assign yourself View-access to Sys Admins
Switch to agent panel and observe the escalated ticket
Observe that you can no longer make changes to it

Solve all of the tickets
Explain in most ticketing systems (probably this one too) there is an email capability so every time you update the ticket, the user gets a copy and they can respond

Explain ticket intake IRL:
Sometimes tickets get created via phone, chat app, email, web form, or maybe even you run into someone in your hall or they roll up on you at your desk.
A lot of the time people will randomize you and try to get you to fix stuff on the spot. It’s fine to fix things on the spot, but generally speaking, you want to create tickets for EVERYTHING you do. (metrics are important)
