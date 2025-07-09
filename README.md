<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
Welcome to the last part of the osTicket tutorial. Here, we will show the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket. 

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

<h4>Example 1 - "entire mobile/online banking system is down"</h4>

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
  - She may also set the SLA Plan to Sev-A due to its potential impact and severity

![image](https://github.com/user-attachments/assets/96e5987d-5411-4ea0-85ca-984cbcfe6426)

![image](https://github.com/user-attachments/assets/4fe0665e-08c1-46ef-9c8e-e6053da86281)

![image](https://github.com/user-attachments/assets/954a3782-b0cf-4007-ad6e-118d2f486d06)


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

<br />

<h4>Example 2 : "accounting department needs adobe upgrade, broken" </h4>

<h3>1. Intake</h3>

  - As an end user, go to http://localhost/osTicket/index.php and create the ticket
  - Click Open a New Ticket -> fill in the fields -> click Create Ticket

![image](https://github.com/user-attachments/assets/552700c8-2cfb-472f-ab6f-d5282d201734)

  - Fill in Issue Summary and description -> click Create Ticket

![image](https://github.com/user-attachments/assets/691df69a-5e07-4e11-a20e-c6dee36c9d9a)

  - After creating a ticket, you'll see a confirmation page

![image](https://github.com/user-attachments/assets/2bc0653b-e581-4a15-98a4-3ed4f77e9de1)

<br />

<h3>2. Assignment and Communication</h3>

  - As a Help Desk Agent (John), observe the ticket’s properties

    - Priority
    - Department
    - SLA
    - Assigned To

  -  Go to http://localhost/osTicket/scp/login.php and log in as John

![image](https://github.com/user-attachments/assets/414eaf99-317e-494a-a8ea-b7d16864cbbc)

  - Click the new ticket and observe
 
![image](https://github.com/user-attachments/assets/522678e1-9aef-473b-92f4-e89f6e164995)

![image](https://github.com/user-attachments/assets/e8c219a1-0c36-441b-b864-438cd602d505)

 - For example, upon reading the ticket, John may contact the user and ask for clarifications,
    set the SLA to Sev-C and leave a reason such as :

![image](https://github.com/user-attachments/assets/3df3b5d5-3f11-4492-88ac-81cb22a9d139)

![image](https://github.com/user-attachments/assets/a6bb7aa1-125b-443a-b368-ae907f42e407)

![image](https://github.com/user-attachments/assets/f47b8177-1326-4973-918b-8ea6e3c8112e)

![image](https://github.com/user-attachments/assets/e61d48b9-12d3-4539-882b-573183ddff7f)

  - He may also assign this to himself

![image](https://github.com/user-attachments/assets/3c93cac1-1cd0-49bf-93c5-ba39788780b2)

![image](https://github.com/user-attachments/assets/c170d563-2216-4ceb-9178-0c0cbead343f)

![image](https://github.com/user-attachments/assets/05bc49b4-a278-4bf2-b94a-fda32a84221b)

<br />

<h3>3. Working the Issue</h3>

  - As John, he might update the software and restart the computers and post a reply such as:

![image](https://github.com/user-attachments/assets/60acc62a-7117-4bcc-8440-35723b2e3b11)
 
![image](https://github.com/user-attachments/assets/3152c533-6d02-4a5d-a228-a8154df1e34d)


<h3>4. Resolution</h3>

 - After updating the software update/restart and reaching out to the user, he might post a reply such as:

![image](https://github.com/user-attachments/assets/2b64acdf-04bf-4ce1-8f79-16d8e3762186)

![image](https://github.com/user-attachments/assets/bf98d116-0c20-4c35-897e-8be8dfc91899)

  - Now that the issue is resolved, he may now close the ticket

![image](https://github.com/user-attachments/assets/c790e8a5-efea-4091-8f7c-8ef91aeb7b7c)

![image](https://github.com/user-attachments/assets/70283ec8-7bfe-4fdc-a986-6fa4dfeec5ca)

![image](https://github.com/user-attachments/assets/1f3861e2-7fe8-4bd2-b6c6-45359f515ca7)

![image](https://github.com/user-attachments/assets/0e72110f-7106-468f-b267-43aae91a56b3)

<br />

<h2>Hope you found this OsTicket guide helpful, cheers!</h2>
