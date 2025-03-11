<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to create, work, and resolves tickets within osTicket](https://www.youtube.com)

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

<h2>Intake Tickets Examples</h2>

- Entire mobile banking system is down
- accounting department needs an adobe upgrade
- CFO's laptop won't turn on anymore
<h2></h2>
Lets create one of our example tickets
<p>
<img src="https://i.imgur.com/MHyXghN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />

<p>
<img src="https://i.imgur.com/pjtwbN0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />
<h2></h2>
Now if we log into osTicket as our help desk agent we can see the ticket we just made
<p>
<img src="https://i.imgur.com/wAqkxmI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />
<h2></h2>
If we look at the ticket we can see alot of information. Most of it we can edit/change if the person submitting the ticket accidentally entered something wrong (in this case it'd be the Help Topic...an entire mobile banking system being down is more serious than a personal computer problem). You can also make comments to communicate who the tickets being assigned to, what the causes could be, etc. 
<p>
<img src="https://i.imgur.com/QhChHH3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
For something this serious you'd probably want to contact this person quickly just to verify this is something that's still happening. 
</p>
<br />
Let's change this help topic and assign this ticket to the Sysadmins department. Notice how once you change the department you wont be able to even view the ticket anymore as the help desk agent.

<p>
<img src="https://i.imgur.com/73NxCa6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
They don't have the perms to be able to view the ticket. (this may not be true everywhere, but lets say it is for this example)
</p>
<br />
Now if we login as our Sysadmin account we can see the ticket again

<p>
<img src="https://i.imgur.com/hbt78wV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />
Here we've assigned it to our Sysadmin person in the online banking dept.
<h2></h2>
If we look at the comments made by the Sysadmin (Jane Doge).
<p>
<img src="https://i.imgur.com/yvblBVy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
We can see her giving updates as she's working through the issue. (In most ticketing systems there's an email capability so everytime an update is made the user gets a copy and can respond).
</p>
<br />

Issue is fixed so we'll change the status of this ticket to resolved
<p>
<img src="https://i.imgur.com/cz9e3UT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />

