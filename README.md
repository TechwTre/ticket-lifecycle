<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the ticket lifecycle from intake to resolution within the open-source help desk ticketing system osTicket.<br />
<br />
Part 1: Ticket Creation  
<br />
Part 2: Resolving Tickets and Troubleshooting Permissions 
<br />
Part 3: Assigning, escalating, and closing tickets 
<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Microsoft Azure Active Subscription (Creation of Reasearch Group, VMs, Virtual Networks, Subnets)
- Enable Internet Information Services(IIS)
- PHP Manager
- Rewrite Manager
- C++ Redistributbal
- MySQL Server
- Install osTicket
- Assigning Permissions
- osTicket
- Chief User: Tre
- Agents: jane.doe and john.doe

<h2>Part 1: Ticket Creation</h2>

Step 1: This is the Support center where users can create an account to submit Tickets. Click Open a New Ticket.
</p>

![image](https://github.com/TechwTre/ticket-lifecycle/assets/126909509/7ac0681a-0630-4522-872f-31d50288bce3)
</p>
<br />

Step 2: Fill out the Client form and Ticket information. Click create Ticket (ex: Jim Hardware, Tim Eugene)
</p>

![image](https://github.com/TechwTre/ticket-lifecycle/assets/126909509/a003dd57-7473-43c8-8614-27a857de3813)
</p>
<br />

Step 3: Client support Ticket request has been created
</p>

![image](https://github.com/TechwTre/ticket-lifecycle/assets/126909509/19c6cc0a-e241-46fe-bce3-0a2da32b71e7)
</p>
<br />

<h2>Part 2: Resolving Tickets/ Troubleshooting Permissions</h2>

Step 1: Help desk would navigate to "http://localhost/osTicket/scp/login.php" and enter credentials to begin resolving Tickets
</p>

![image](https://github.com/TechwTre/ticket-lifecycle/assets/126909509/4374b5ca-1838-4b70-8701-6df07aa65165)
</p>
<br />

Step 2: Once the permissions have been granted to the Help desk employee we can overview the Tickets that clients have submitted through our staff panel
</p>

![image](https://github.com/TechwTre/ticket-lifecycle/assets/126909509/49967e91-9b03-4de6-bc42-788ce124e2af)
</p>
<br />

Step 3: Logged out of the Agent panel to log in through the Admin panel to set up departments ex. (System Administrators)
</p>

![image](https://github.com/TechwTre/ticket-lifecycle/assets/126909509/bca5f385-b9ba-4721-b4d8-350f2d7e9ebd)
</p>
<br />

Step 4: Once the department has been created, we have now set agents in there appropriate destinations to have access to certain permissions 
</p>

![image](https://github.com/TechwTre/ticket-lifecycle/assets/126909509/63c495d1-10ff-48e4-931f-a2a6200f86ab)
</p>
<br />

Step 5: Here we can navigate to the "manage" tab in the Admin panel to set our Service Level Agreements for our Agents. This will aid in the organization of the Priority status of the tickets submitted through our system ex. (SEV-A, 1hr Grace Period)
</p>

![image](https://github.com/TechwTre/ticket-lifecycle/assets/126909509/8a4680b2-430a-47f0-9db8-7caede478ea3)
</p>
<br />

Step 6: Here we can configure our Help topics for each ticket that will come through our system to organize severity of the tickets to allow agents to know where focus should be in terms of the Tickets they may have to resolve for the day. ex. (Business Critical Outage)
</p>

![image](https://github.com/TechwTre/ticket-lifecycle/assets/126909509/001e26ba-86e3-448a-912b-480dca5b30a4)
</p>
<br />

Step 7: This is the dashboard for our agent Jane after we have signed out of the Admin panel back into the staff panel and granted proper permissions we can see the tickets that have come through to now allow Agents to perform their duties. 
</p>

![image](https://github.com/TechwTre/ticket-lifecycle/assets/126909509/008f1652-fd6c-4911-b9f1-53547f5e6a66)
</p>
<br />

<h2>Part 3: Assigning, Closing, Escalating Tickets</h2>

Step 1: Here we have the Ticket that was assigned to jane by the escalation engineer/queue manager. This is a moderate/normal business impacting incident,therefore we would change our Priority to match such. Then also change our Service Level Agreement to the second most urgent: SEV-B
</p>

![image](https://github.com/TechwTre/ticket-lifecycle/assets/126909509/7ef3f6d7-a98a-421e-b9fd-e547a06154bf)
</p>
<br />

Step 2: Jane acknowledges the ticket she was assigned in the dashboard after signing on. Reviewing the SEV-B she has a 4hr grace period to adhere to the ticket. Clarifying the proper information as a IT Helpdesk agent, the next objective is to diagnose and resolve the issue to complete the onboarding of John.
</p>

![image](https://github.com/TechwTre/ticket-lifecycle/assets/126909509/5e8cfce0-0604-4bf5-9770-ea0f2cee256c)
</p>
<br />

![image](https://github.com/TechwTre/ticket-lifecycle/assets/126909509/2cbc7e88-08e9-4fe7-af7b-9fbdeb77c3ee)
</p>
<br />

<h3>Approach to Resolution:</h3>

<h5> Initial Assessment:</h5> John needs to be Onboarded into the System with the correct permissons
</p>
<br />

Step 1: Sign into the Admin panel where we can add in our new agents. We then input personal info accordingly as well as create a username and password for the agent. Then select the status of the Agent
</p>

![image](https://github.com/TechwTre/ticket-lifecycle/assets/126909509/1bef1c27-5f78-41a4-b1a2-816d868b181a)
</p>
<br />

Step 2: Administrator grants access to the correct department that allows access to the tools/assignments corresponding to the proper role of the new IT HelpDesk agent.

![image](https://github.com/TechwTre/ticket-lifecycle/assets/126909509/99ddb98f-1d35-4227-b05c-3b40d218e8f2)
</p>
<br />

Step 3: Administrator then grants the IT Help desk agent the proper permissions based upon: User, Organizations, Knowledgebase, and Miscellaneous corresponding to the effective role.
</p>

![image](https://github.com/TechwTre/ticket-lifecycle/assets/126909509/91d40dae-6224-4f28-9dea-409697bd31b8)
</p>
<br />

Step 4: IT Help Desk agent has now been properly added to the correct team and onboarded into the system.
</p>

![image](https://github.com/TechwTre/ticket-lifecycle/assets/126909509/d345022c-1b17-4a26-b55e-72c548ee63b5)
</p>
<br />

Step 5: The IT Help desk agent then replies to the user informing them that the issue/task has been marked as resolved and then proceeds to close the Ticket.
</p>

![image](https://github.com/TechwTre/ticket-lifecycle/assets/126909509/5a4d8a19-60d8-453c-a504-587a5b3e4b44)
</p>
<br />

![image](https://github.com/TechwTre/ticket-lifecycle/assets/126909509/259a80d3-cec5-464f-8481-3bc369a35bd3)
</p>
<br />
