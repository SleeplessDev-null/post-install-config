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

- Agent/Employee set up 
- Configuration for roles
- Department setup 
- SLA setup
- User Set up


<h3>This will be a continuation of setting up osTicket.Here will go over the basics of getting users,employees, roles,sla and overall configuration of osTicket set up in a simple and easy to follow manner.</h3>

<h2>Configuration Steps</h2>

<p align="center">
First log in with the password and username you set for yourself, back inside of the osticket installer. This is the interface for the osticket. :
<br />
<br />  
<img src="https://github.com/SleeplessDev-null/post-install-config/blob/main/PNG/Config%20roles.PNG?raw=true" height="90%" width="80%"  />
<br />
<br />
We will begin by setting up the roles for our agents/employees. Click the admin panel button next to your name and follow theses steps :
<br />
<br />
<img src="https://github.com/SleeplessDev-null/post-install-config/blob/main/PNG/Roles%201.PNG?raw=true" height="90%" width="80%"  />
<br />   
<img src="https://github.com/SleeplessDev-null/post-install-config/blob/main/PNG/Roles%202.PNG?raw=true" height="90%" width="80%"  />
<br />  
<br />
Here we will set up the first role which will be Supreme Admin follow the steps for how to set the permissions.:
<br />
<br />
<img src="https://github.com/SleeplessDev-null/post-install-config/blob/main/PNG/Roles%203.PNG?raw=true" height="90%" width="80%"  />
<br />  
<img src="https://github.com/SleeplessDev-null/post-install-config/blob/main/PNG/Roles%204.PNG?raw=true" height="90%" width="80%"  />
<br />
<br />
Save the changes and the roles are done. Now we move on to departments. While in the admin panel follow these steps .:
<br />
<br />
<img src="https://github.com/SleeplessDev-null/post-install-config/blob/main/PNG/Departments.PNG?raw=true" height="90%" width="80%"  />
<br />   
<img src="https://github.com/SleeplessDev-null/post-install-config/blob/main/PNG/Department%202.PNG?raw=true" height="90%" width="80%"  />
<br />
<br />
Save the department and move over to the teams section and create a online banking team.
<br />
<br />  
<img src="https://github.com/SleeplessDev-null/post-install-config/blob/main/PNG/Teams.PNG?raw=true" height="90%" width="80%"  />
<br />     
<img src="https://github.com/SleeplessDev-null/post-install-config/blob/main/PNG/Teams%201.PNG?raw=true" height="90%" width="80%"  />
<br />
<br />
In this setting leave the box unticked just so you don't have to use a real email when making your clients.
<br />
<br /> 
<img src="https://github.com/SleeplessDev-null/post-install-config/blob/main/PNG/Teams%202.PNG?raw=true" height="90%" width="80%"  />
<br />
<br />
Now we will move on to the creation of your agents/employees. In this section you can create the agent accounts and add them to different departments or teams.The information can be completely random just make sure the passwords and usernames are easy to remember for the purpose of the guide. Follow these steps.:
<br />
<br />
<img src="https://github.com/SleeplessDev-null/post-install-config/blob/main/PNG/Agents.PNG?raw=true" height="90%" width="80%"  />
<br />
<img src="https://github.com/SleeplessDev-null/post-install-config/blob/main/PNG/Agent%202.PNG?raw=true" height="90%" width="80%"  />
<br />  
<img src="https://github.com/SleeplessDev-null/post-install-config/blob/main/PNG/Agent%203.PNG?raw=true" height="90%" width="80%"  />
<br />   
<img src="https://github.com/SleeplessDev-null/post-install-config/blob/main/PNG/Agent%204.PNG?raw=true" height="90%" width="80%"  />
<br />
<br />
Uncheck the the boxes, this will make it so the password you set will be their main password. :
<br />
<br />  
<img src="https://github.com/SleeplessDev-null/post-install-config/blob/main/PNG/Agents%20%205.PNG?raw=true" height="90%" width="80%"  />
<br />
<br />
 Now we move on to users/clients. Start by going back to the agent panel and follow these steps :
<br />
<br />  
<img src="https://github.com/SleeplessDev-null/post-install-config/blob/main/PNG/Users.PNG?raw=true" height="90%" width="80%"  />
<br />   
<img src="https://github.com/SleeplessDev-null/post-install-config/blob/main/PNG/Users%201.PNG?raw=true" height="90%" width="80%"  />
<br />   
<img src="https://github.com/SleeplessDev-null/post-install-config/blob/main/PNG/User%201.PNG?raw=true"90%" width="80%"  />
<br />
<br />
The users you created should be in this panel when you are done creating them.:
<br />
<br />   
<img src="https://github.com/SleeplessDev-null/post-install-config/blob/main/PNG/Users%202.PNG?raw=true" height="90%" width="80%"  /> 
<br />
<br /> 
Now we move onto the SLA. The SLA means service-Level agreement. This is a agreement between service provider and a customer that define the level of service that the provider will deliver.
The SLA outlines specific metrics, such as response time, and resolution time, and includes consequences if the provider fails to meet those metrics. so we will make ours and give them a severity level based on the level of business impact they might have. Follow my steps and feel free to add more for practice. :
<br />
<br />
<img src="https://github.com/SleeplessDev-null/post-install-config/blob/main/PNG/SLA%201.PNG?raw=true" height="90%" width="80%"  />
<br />
<br /> 
Here you can give it a name, severity level, description,and a time limit.:
<br />
<br /> 
<img src="https://github.com/SleeplessDev-null/post-install-config/blob/main/PNG/SLA%202.PNG?raw=true" height="90%" width="80%"  />
<br />
<br /> 
After this is done we will move on to the last step which is help topics. This is how clients would lable a inquery or problem when reporting issues and this is how we set them up .:
<br />
<br />  
<img src="https://github.com/SleeplessDev-null/post-install-config/blob/main/PNG/Help%20Topics.PNG?raw=true" height="90%" width="80%"  />
<br />   
<img src="https://github.com/SleeplessDev-null/post-install-config/blob/main/PNG/Help%20topic%201.PNG?raw=true" height="90%" width="80%"  />
<br />
This how it should look after:
<br />
<br /> 
<img src="https://github.com/SleeplessDev-null/post-install-config/blob/main/PNG/Help%20topic%20last%20step%20.PNG?raw=true" height="90%" width="80%"  />
<br />
<br />


<h1>
 This is the end for the configuration setup of osTicket with many of the sections you can add more agents/employees to try and simulate a real working environment when using a ticket system. Next we will be working tickets to get the feel of how it would be in the real world.
</h1>
   


   
</p>
