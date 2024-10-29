<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post Configuration Setup</h1>
</p>
This tutorial demonstrates the post configuration setup of the osTicket system.<br />

<p>

</p>
</p>
<p>
We’ve successfully set up osTicket from scratch, and now it’s time to move on to system administration and post-installation configurations. The first step is to create new roles within the help desk by navigating to Admin Panel → Agents → Roles, where we’ll set up a new role called Supreme Admin. Click "Add New Role" and enter the role’s name, then customize the permissions as needed. Since this role is for a Supreme Admin, we’ll grant full access to all features and settings. Keep in mind that roles determine what each agent can access, so not all agents will have unrestricted permissions—be careful to assign this role only to those who need it. If everything was done correctly, the new role will display on your screen, confirming that the Supreme Admin role is now successfully configured!
</p>
<img src="https://i.imgur.com/XHteqdt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
</p>
<p>
Under the Agents tab, click on "Departments" to create and manage departments within the help desk. Agents are assigned to specific departments based on their roles and responsibilities. In this example, we’ll create a "System Administrators" department to house the Supreme Admins. You can also configure other essential settings here, such as SLAs (Service Level Agreements), department managers, and email notifications, ensuring smooth operations and efficient task management.
</p>
<br />
<p>
<img src="https://i.imgur.com/dGK0RVM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After setting up a new department, the next step is to create a team. Teams allow you to group agents from different departments, enabling you to assemble specialized groups, such as an A-Team with top technicians from various areas. For example, you can create a help topic related to a specific product and assign it to a team of agents who specialize in that product. To set up a new team, navigate to Agents → Teams. A default Level I Support Team is already provided, but in this example, we’ll create a Level II Support Team for handling more advanced issues.
</p>
<br />
<p>
<img src="https://i.imgur.com/cYzWBD2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
With the new team set up, the next step is to enable a setting that allows anyone to create tickets. To do this, navigate to Admin Panel → Settings → User Settings.
</p>
<br />
<img src="https://i.imgur.com/H1q2Fdh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now it’s time to create agents, the employees responsible for resolving tickets within the help desk. Each agent is assigned a primary department and a primary role for handling tickets in that department. Agents can also be granted access to additional departments and may have different roles depending on the department they work in. Permissions, access, and team assignments are managed through the Agents tab.
</p>
<br />
<img src="https://i.imgur.com/8WTOSre.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After setting up agents, the next step is to create users. Users are customers who submit tickets when they encounter issues, and each user is identified by their email address. To create a new user, navigate to Agent Panel → Users → User Directory → Add New.
</p>
<br />
<img src="https://i.imgur.com/xOprA9f.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
SLA Plans define the time frame within which the help desk is expected to resolve specific tickets. To create an SLA Plan, go to Admin Panel → Manage → SLA Plans. Each plan includes a schedule, along with a grace period for resolving tickets within that timeframe. For example, the SEV-A plan operates 24/7 with a one-hour grace period.
</p>
<br />
<img src="https://i.imgur.com/LpjCaLd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Help topics assist users in categorizing their tickets. For example, we have created a help topic titled "Business Critical Outage," which can be used for various issues, such as widespread service disruptions or critical system failures.
</p>
<br />
<img src="https://i.imgur.com/kB7rts2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
