<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
Welcome the last part of the osTicket tutorial. Here, we will show the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket. 

*(note : these are only examples and ticket resolutions/SLAs will vary from organization to organization.)*

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


  - Click on the new ticket and observe.

![image](https://github.com/user-attachments/assets/175c84ac-5df6-4b25-b746-06fd0dc09f29)

![image](https://github.com/user-attachments/assets/8fd64081-82e9-4c31-be93-b0aba607c222)
	
  - Priority : Seeing that this is an important concern, click high and update

![image](https://github.com/user-attachments/assets/b88ad9f3-c3f9-4851-a074-3cd5546557e3)

  - Department : this has to be escalated to a System Administator, click System Administrator then transfer

![image](https://github.com/user-attachments/assets/4272dfcf-3735-4ca9-b1b7-82043430371d)

  - Attempt to observe the ticket again as “john”. Notice that the ticket is gone.

![image](https://github.com/user-attachments/assets/19647e76-0a17-49f4-b02d-ea3281e58a77)

<br />

<h3>3. Working the Issue</h3>

  - Work the ticket to completion as Jane (System Administrator)
     -  Go to http://localhost/osTicket/scp/login.php and log in as Jane and click the ticket

![image](https://github.com/user-attachments/assets/ba75ce73-ebf7-4a6c-ac81-1c70f3144acc)

![image](https://github.com/user-attachments/assets/878dceb2-5d80-4107-9784-788631b901db)

  - As Jane, observe that the ticket is now high priority and moved to your department.

![image](https://github.com/user-attachments/assets/96e5987d-5411-4ea0-85ca-984cbcfe6426)

 - For example, the system admin will look into this and look for a resolution. She may write a response such as:

![image](https://github.com/user-attachments/assets/689581c5-a982-4b51-a04e-80335ae62d30)

![image](https://github.com/user-attachments/assets/c5f53203-0274-43a3-9ca7-be41a71baf62)

<br />

<h3>4. Resolution</h3>

  - As Jane, come back with a resolution such as below then Post Reply

![image](https://github.com/user-attachments/assets/7250adfa-0966-41ec-9fd9-6f354935aaef)

![image](https://github.com/user-attachments/assets/b28e0a79-5824-4af6-a550-ba080848da75)

  - Now that the ticket is resolved, you can close the ticket

![image](https://github.com/user-attachments/assets/4367f7c0-1608-4ce4-aa4f-4eba7e6abb75)

  - After closing the ticket, hover on Open and click Open

![image](https://github.com/user-attachments/assets/5ea90cfd-2f3c-4837-8726-1ce6912e369a)

  - See that the ticket is no longer available

![image](https://github.com/user-attachments/assets/0ef9d2a0-5034-46fe-8e11-770200d05472)



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
