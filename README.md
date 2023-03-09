<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
In this repository I will be going over Tickets and Ticket Lifecycles. I will be demonstrating how to practice creating tickets as an end user and  triaging and solving tickets as a help desk professional.<br />


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

<p>
<img src="https://i.imgur.com/mJVOxt7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
This is the end users osTicket screen. Here customers can open a new ticket. This is the URL for end users: http://localhost/osTicket/
  
Click on "Open a New Ticket".
</p>
<br />

<p>
<img src="https://i.imgur.com/FIrN2KM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here the credentials that were created for an end user (Karen or Ken) will be used to create the ticket.

Under the "Help Topic" drop-down menu there are a few options as well as the Help Topics that were created in the last section. 
  
For this particular ticket the help topic will be "Business Critical Outage".
  
End users are able to summarize the issue they are facing as well as give further details.
  
Click "Create Ticket".
</p>
<br />

<p>
<img src="https://i.imgur.com/fOI30fc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Because the extended access of Supreme Admin was not added to Jane Doe's account, tickets aren't showing up in her que. To fix this, log in to osTicket with the credentials that were created for the Admin.
  
Adnmin Panel > Agents > Settings > Jane Doe > Access > Extended Access > Support > Supreme Admin > Save Changes
  
Log out from the Admin account
</p>
<br />

<p>
<img src="https://i.imgur.com/VC1EzgT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Log in as the help desk professional Jane Doe.
</p>
<br />

<p>
<img src="https://i.imgur.com/q2jM6k5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now Jane Doe can see the ticket that was created!
  
Click on the ticket "Entire mobile banking is down"
</p>
<br />

<p>
<img src="https://i.imgur.com/wNBcmRi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here you can see the details of the ticket and change things like which department and who the ticket is assigned to, the SLA, the status, etc.
  
Change the Priority Level of the ticket to Emergency > type "Business Critical Outage in the note > Update
</p>
<br />

<p>
<img src="https://i.imgur.com/anLxINL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Assign the ticket to agent Jane Doe > Update
</p>
<br />

<p>
<img src="https://i.imgur.com/nW1C92k.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Since the priority of the ticket is "Emergency" because it is a Business Critical Outage, the SLA needs to be changed accoridingly.
  
Default SLA > SEV-A > type "Business Critical Outage" > Update
</p>
<br />

<p>
<img src="https://i.imgur.com/pm8OnnC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Because the ticket issue seems to be out of scope for the support department, the ticket needs to be assigned to the correct department. 
  
Department > System Administrators > type " Sys Admins responsible for monbile banking infrastructure" in the note > Transfer
</p>
<br />

<p>
<img src="https://i.imgur.com/X8t2Ubh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
If you scroll down through the ticket, you can see a thread of events done on the ticket. This keeps track of the status of who has been working on the issue and the status.
  
In the reply type "Coordinating with Sys Admnin Team to bring mobile banking back online" > keep ticket status to "Open" > Post Reply
</p>
<br />

<p>
<img src="https://i.imgur.com/3FGO1v4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Go back to the tickets tab and observe the changes that were made. You can see the the priority was changed to emergency, the ticket was assigned to Jane Doe, and there were some actions added to the thread of events. 
</p>
<br />

<p>
<img src="https://i.imgur.com/kyfG5f2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lets imagine that the ticket was solved. 
  
In the reply type "Jerry from System Engineering found and corrected failed load balancer. Mobile Banking should be back up." > Ticket Status > Resolved > Post Reply
</p>
<br />

<p>
<img src="https://i.imgur.com/sJ9eA8G.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once the ticket status is changed to resolve, it will take you back to the ticket que. There you can observe that the ticket has been removed from the que.
  
That marks the end of this demonstration of the lifecycle of a ticket! These steps can be used to create many more tickets to use as practice for navigating a ticketing system.
</p>
<br />
