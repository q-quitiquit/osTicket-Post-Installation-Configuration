<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post Install and Configuration</h1>
This tutorial outlines the Post installation and Configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop (Windows App)
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 11</b>

<h2>List of Prerequisites</h2>

- Azure Virtual Machine
- osTicket Installation files
- Heidi SQL

<h2>Installation Steps</h2>

In this lab we will make some configurations in order to use osTicket. We will provid Agents, roles, departments and teams. First we will configure roles, we will go to the admin panel > Agents > then roles. From there we will name it Supreme Admin
</p>
<br />

<img width="965" height="596" alt="Screenshot 2025-10-07 at 3 25 43 PM" src="https://github.com/user-attachments/assets/012901cd-33d2-4b4b-a93c-83689f43cecf" />
</p>
<br />

Next we will Configure Departments. Creating this will allow ticket visibility. Go into admin panel > agents > the departments, from there type in SysAdmins.
</p>
<br />

<img width="962" height="880" alt="Screenshot 2025-10-07 at 3 29 58 PM" src="https://github.com/user-attachments/assets/def6d28f-d1e5-4b3f-9881-0ca332ae6421" />
</p>
<br />

In this step we will configure teams. In the Admin Panel go to agents then teams. Name it Tech Support 2
</p>
<br />

<img width="958" height="713" alt="Screenshot 2025-10-07 at 3 58 54 PM" src="https://github.com/user-attachments/assets/abebb8e0-1b9f-43b4-a804-0a8cb075fd01" />
</p>
<br />

In order to allow anyone to create tickets we will  go into the Admin panel > Settings > User Settings > and then "UNCHECK" the Require registration and login to create tickets box. 
</p>
<br />

<img width="961" height="736" alt="Screenshot 2025-10-07 at 3 38 46 PM" src="https://github.com/user-attachments/assets/9bc037ea-89c9-4333-83cc-a1095f1ab872" />
</p>
<br />

Following that step we will create Agents. Go into the Admin Panel > Agents > then click Add New. For sample purposes we will Create Jane. We will then give her a Supreme Admin role, her Department would be SysAdmin and she would be part of the Tech Support 2 team, just incase tech support 1 can't fulfill the ticket. By doing this, she has access that a normal employee won't have.
</p>
<br />

<img width="956" height="840" alt="Screenshot 2025-10-07 at 3 49 51 PM" src="https://github.com/user-attachments/assets/3f160816-18e9-4823-beb4-bbf25c70ff62" />
</p>
<br />

Next we will create Users (customers). In order to do so you must be in the agent panel, go to users and click add new. For sample purposes we will create Ken.
</p>
<br />

<img width="1265" height="874" alt="Screenshot 2025-10-07 at 4 40 10 PM" src="https://github.com/user-attachments/assets/06a20acc-9e88-4c25-b2ca-aede0df437e4" />
</p>
<br />

SLA stands for Service Leve Agreement, it's a contract between a service provider and a client that defines the level of service expected, including metrics like uptime and response times. to configure SLA we will go into the Admin Panel, then Manage and click on SLA.
</p>
<br />

<img width="955" height="663" alt="Screenshot 2025-10-07 at 4 42 34 PM" src="https://github.com/user-attachments/assets/362fe679-aae5-4985-93c9-2f750f4b3336" />
</p>
<br />

The picture below shows the different SLA's we created. Each SLA has a severity, how long it takes to complete the ticket and the schedule of ticket will be shown on the agents dashboard.
</p>
<br />

<img width="956" height="421" alt="Screenshot 2025-10-07 at 4 46 31 PM" src="https://github.com/user-attachments/assets/2ca8e255-c806-4b80-8c5c-43fdc1bbfeb7" />
</p>
<br />

Lastly, We will configure a help topic. This is for when users create a ticket. Go into the Admin panel, click Manage, then go into help Topics. For example, Business Critical Outage, Personal Computer Issues, Equipment, and Passwords Resets.
</p>
<br />

<img width="955" height="632" alt="Screenshot 2025-10-07 at 4 50 31 PM" src="https://github.com/user-attachments/assets/011e32ff-d5f9-47a9-b12b-82fa7a992807" />
</p>
<br />
